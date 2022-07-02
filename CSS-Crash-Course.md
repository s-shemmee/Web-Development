# CSS

*CSS stands for Cascading Style Sheets. It is the technology to learn after HTML. It is used for styling our HTML. For example, we can use CSS to space our content, colours, fonts, etc.*

## CSS Syntax

<img src="https://www.w3schools.com/css/img_selector.gif">

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
- `text-align` is a property, and `center` is the property value

### CSS Selectors

*CSS selectors are used to "find" (or select) the HTML elements you want to style.*

> We can divide CSS selectors into five categories:

- Simple selectors (select elements based on name, id, class)
- Combinator selectors (select elements based on a specific relationship between them)
- Pseudo-class selectors (select elements based on a certain state)
- Pseudo-elements selectors (select and style a part of an element)
- Attribute selectors (select elements based on an attribute or attribute value)
This page will explain the most basic CSS selectors.

#### The CSS id Selector

*The id selector uses the id attribute of an HTML element to select a specific element.*

*The id of an element is unique within a page, so the id selector is used to select one unique element!*

*To select an element with a specific id, write a hash `(#)` character, followed by the id of the element.*

> Example

- The CSS rule below will be applied to the HTML element with id="para1": 

```css
#para1 {
  text-align: center;
  color: red;
}
```

### The CSS class Selector

*The class selector selects HTML elements with a specific class attribute.*
*To select elements with a specific class, write a period (.) character, followed by the class name.*

> Example
- In this example all HTML elements with class="center" will be red and center-aligned: 

```css
.center {
  text-align: center;
  color: red;
}
```

*You can also specify that only specific HTML elements should be affected by a class.*

> Example
- In this example only <p> elements with class="center" will be red and center-aligned: 

```css
p.center {
  text-align: center;
  color: red;
}
```

*HTML elements can also refer to more than one class.*

> Example
- In this example the <p> element will be styled according to class="center" and to class="large": 

```html
<p class="center large">This paragraph refers to two classes.</p>
```

### The CSS Universal Selector

*The universal selector `(*)` selects all HTML elements on the page.*

> Example
- The CSS rule below will affect every HTML element on the page: 

```css
* {
  text-align: center;
  color: blue;
}
```

### The CSS Grouping Selector

*The grouping selector selects all the HTML elements with the same style definitions.*

- Look at the following CSS code (the h1, h2, and p elements have the same style definitions):

```css
h1 {
  text-align: center;
  color: red;
}

h2 {
  text-align: center;
  color: red;
}

p {
  text-align: center;
  color: red;
}
```

- It will be better to group the selectors, to minimize the code.

- To group selectors, separate each selector with a comma.

> Example
- In this example we have grouped the selectors from the code above: 

```css
h1, h2, p {
  text-align: center;
  color: red;
}
```

#### All CSS Simple Selectors

- #id	`#firstname`	Selects the element with id="firstname"
- .class	`.intro`	Selects all elements with class="intro"
- element.class	`p.intro`	Selects only `<p>` elements with class="intro"
- *	`*`	Selects all elements
- element	`p`	Selects all `<p>` elements
- element,element,..	`div, p`	Selects all `<div>` elements and all `<p>` elements

## CSS Comments

*Comments are used to explain the code, and may help when you edit the source code at a later date.*

*Comments are ignored by browsers.*

*A CSS comment is placed inside the `<style>` element, and starts with `/*` and ends with `*/`*

> Example

```css
/* This is a single-line comment */
p {
  color: red;
}
```

## The CSS Box Model

*In CSS, the term "box model" is used when talking about design and layout.*

*The CSS box model is essentially a box that wraps around every HTML element. It consists of: margins, borders, padding, and the actual content. The image below illustrates the box model:*

<img src="https://workshub.imgix.net/6de1028c70660d608da27ce471210788?auto=format&crop=entropy&fit=crop">

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
