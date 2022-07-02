# CSS

*CSS stands for Cascading Style Sheets. It is the technology to learn after HTML. It is used for styling our HTML. For example, we can use CSS to space our content, colours, fonts, etc.*

## CSS Syntax

[CSS Syntax](https://www.w3schools.com/css/img_selector.gif)

- The selector points to the HTML element you want to style.

- The declaration block contains one or more declarations separated by semicolons.

- Each declaration includes a CSS property name and a value, separated by a colon.

- Multiple CSS declarations are separated with semicolons, and declaration blocks are surrounded by curly braces.

> Example

```css
p {
  color: red;
  text-align: center;
}
```

> Example Explained

- `p` is a selector in CSS (it points to the HTML element you want to style: `<p>`).
- `color` is a property, and `red` is the property value
- `text-align` is a property, and `center` is the property value\

## The CSS Box Model

*In CSS, the term "box model" is used when talking about design and layout.*

*The CSS box model is essentially a box that wraps around every HTML element. It consists of: margins, borders, padding, and the actual content. The image below illustrates the box model:*

[CSS Box Model](https://workshub.imgix.net/6de1028c70660d608da27ce471210788?auto=format&crop=entropy&fit=crop)

> Explanation of the different parts:

- `Content` : The content of the box, where text and images appear
- `Padding` : Clears an area around the content. The padding is transparent
- `Border` : A border that goes around the padding and content
- `Margin` : Clears an area outside the border. The margin is transparent

*The box model allows us to add a border around elements, and to define space between elements.*

```css
div {
  width: 300px;
  border: 15px solid green;
  padding: 50px;
  margin: 20px;
}
```

## CSS positioning 

*CSS positioning helps you manipulate an element to different locations such as fixed, relative, absolute, static, sticky, etc. The image below shows us CSS positions.*

### The position Property

*The position property specifies the type of positioning method used for an element.*

> There are five different position values:

- `static`
- `relative`
- `fixed`
- `absolute`
- `sticky`

- Elements are then positioned using the top, bottom, left, and right properties. However, these properties will not work unless the `position` property is set first. They also work differently depending on the position value.

#### position: static;

*HTML elements are positioned static by default.*

*Static positioned elements are not affected by the top, bottom, left, and right properties.*

*An element with position: static; is not positioned in any special way; it is always positioned according to the normal flow of the page:*

- This <div> element has position: static;

> Here is the CSS that is used:

```css
div.static {
  position: static;
  border: 3px solid #73AD21;
}
```

#### position: relative;

*An element with `position: relative;` is positioned relative to its normal position.*

*Setting the top, right, bottom, and left properties of a relatively-positioned element will cause it to be adjusted away from its normal position. Other content will not be adjusted to fit into any gap left by the element.*

- This <div> element has position: relative;

> Here is the CSS that is used:

```css
div.relative {
  position: relative;
  left: 30px;
  border: 3px solid #73AD21;
}
```

#### position: fixed;

*An element with position: fixed; is positioned relative to the viewport, which means it always stays in the same place even if the page is scrolled. The top, right, bottom, and left properties are used to position the element.*

*A fixed element does not leave a gap in the page where it would normally have been located.*

> Notice the fixed element in the lower-right corner of the page. Here is the CSS that is used:

```css
div.fixed {
  position: fixed;
  bottom: 0;
  right: 0;
  width: 300px;
  border: 3px solid #73AD21;
}
```

#### position: fixed;

*An element with `position: fixed;` is positioned relative to the viewport, which means it always stays in the same place even if the page is scrolled. The top, right, bottom, and left properties are used to position the element.*

*A fixed element does not leave a gap in the page where it would normally have been located.*

> Notice the fixed element in the lower-right corner of the page. Here is the CSS that is used:

```css
div.fixed {
  position: fixed;
  bottom: 0;
  right: 0;
  width: 300px;
  border: 3px solid #73AD21;
}
```

#### position: sticky;

*An element with `position: sticky;` is positioned based on the user's scroll position.*

*A sticky element toggles between `relative` and `fixed`, depending on the scroll position. It is positioned relative until a given offset position is met in the viewport - then it "sticks" in place (like position:fixed).*

> In this example, the sticky element sticks to the top of the page (top: 0), when you reach its scroll position.

```css
div.sticky {
  position: -webkit-sticky; /* Safari */
  position: sticky;
  top: 0;
  background-color: green;
  border: 2px solid #4CAF50;
}
```

### All CSS Positioning Properties
	
- `bottom` :	Sets the bottom margin edge for a positioned box
- `clip`	: Clips an absolutely positioned element
- `left`	: Sets the left margin edge for a positioned box
- `position` :	Specifies the type of positioning for an element
- `right`	: Sets the right margin edge for a positioned box
- `top`	: Sets the top margin edge for a positioned box
