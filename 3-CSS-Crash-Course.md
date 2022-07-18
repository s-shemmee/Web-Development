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

#### The CSS class Selector

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

#### The CSS Universal Selector

*The universal selector `(*)` selects all HTML elements on the page.*

> Example
- The CSS rule below will affect every HTML element on the page: 

```css
* {
  text-align: center;
  color: blue;
}
```

#### The CSS Grouping Selector

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

## CSS Colors

*Colors are specified using predefined color names, or RGB, HEX, HSL, RGBA, HSLA values.*

### CSS Color Names

*In CSS, a color can be specified by using a predefined color name:*

> Ex : 

- Tomato,Orange,Dodger,Blue,MediumSea,Green,Gray,SlateBlue,Violet,LightGray

### CSS Background Color

*You can set the background color for HTML elements:*

```html
<h1 style="background-color:DodgerBlue;">Hello World</h1>
<p style="background-color:Tomato;">Lorem ipsum...</p>
```

### CSS Text Color

*You can set the color of text:*

```html
<h1 style="color:Tomato;">Hello World</h1>
<p style="color:DodgerBlue;">Lorem ipsum...</p>
<p style="color:MediumSeaGreen;">Ut wisi enim...</p>
```

### CSS Border Color

*You can set the color of borders:*

```html
<h1 style="border:2px solid Tomato;">Hello World</h1>
<h1 style="border:2px solid DodgerBlue;">Hello World</h1>
<h1 style="border:2px solid Violet;">Hello World</h1>
```

### CSS Color Values

*In CSS, colors can also be specified using RGB values, HEX values, HSL values, RGBA values, and HSLA values:*

- Same as color name "Tomato":

```html
<h1 style="background-color:rgb(255, 99, 71);">...</h1>
<h1 style="background-color:#ff6347;">...</h1>
<h1 style="background-color:hsl(9, 100%, 64%);">...</h1>
Same as color name "Tomato", but 50% transparent:
<h1 style="background-color:rgba(255, 99, 71, 0.5);">...</h1>
<h1 style="background-color:hsla(9, 100%, 64%, 0.5);">...</h1>
```

## CSS Backgrounds

*The CSS background properties are used to add background effects for elements.*

### CSS background-color

*The `background-color` property specifies the background color of an element.*

> Example
- The background color of a page is set like this:

```css
body {
  background-color: lightblue;
}
```
- Or

```css
h1 {
  background-color: green;
}

div {
  background-color: lightblue;
}

p {
  background-color: yellow;
}
```

#### Opacity / Transparency

*The `opacity` property specifies the opacity/transparency of an element. It can take a value from 0.0 - 1.0. The lower value, the more transparent:*

```css
div {
  background-color: green;
  opacity: 0.3;
}
```

#### Transparency using RGBA

*If you do not want to apply opacity to child elements, like in our example above, use RGBA color values. The following example sets the opacity for the background color and not the text:*

*An RGBA color value is specified with: rgba(red, green, blue, alpha). The alpha parameter is a number between 0.0 (fully transparent) and 1.0 (fully opaque).*

```css
div {
  background: rgba(0, 128, 0, 0.3) /* Green background with 30% opacity */
}
```

### CSS background-image

*The background-image property specifies an image to use as the background of an element.*

*By default, the image is repeated so it covers the entire element.*

> Example
- Set the background image for a page: 

```css
body {
  background-image: url("paper.gif");
}
```

- The background image can also be set for specific elements, like the <p> element:

> Example

```css
p {
  background-image: url("paper.gif");
}
```

### CSS background-repeat

*By default, the `background-image` property repeats an image both horizontally and vertically.*

*Some images should be repeated only horizontally or vertically, or they will look strange, like this:*

> Example

```css
body {
  background-image: url("gradient_bg.png");
}
```

- If the image above is repeated only horizontally (background-repeat: repeat-x;), the background will look better:

> Example

```css
body {
  background-image: url("gradient_bg.png");
  background-repeat: repeat-x;
}
```
> Tip: To repeat an image vertically, set background-repeat: repeat-y;

#### CSS background-repeat: no-repeat

*Showing the background image only once is also specified by the `background-repeat` property:*

> Example

- Show the background image only once:

```css
body {
  background-image: url("img_tree.png");
  background-repeat: no-repeat;
}
```

- In the example above, the background image is placed in the same place as the text. We want to change the position of the image, so that it does not disturb the text too much.

#### CSS background-position

*The `background-position` property is used to specify the position of the background image.*

> Example

- Position the background image in the top-right corner: 

```css
body {
  background-image: url("img_tree.png");
  background-repeat: no-repeat;
  background-position: right top;
}
```

### CSS background-attachment

*The `background-attachment` property specifies whether the background image should scroll or be fixed (will not scroll with the rest of the page):*

> Example
- Specify that the background image should be fixed:

```css
body {
  background-image: url("img_tree.png");
  background-repeat: no-repeat;
  background-position: right top;
  background-attachment: fixed;
}
```

## CSS Borders

*The CSS border properties allow you to specify the style, width, and color of an element's border.*

### CSS Border Style

*The `border-style` property specifies what kind of border to display.*

*The following values are allowed:*

- `dotted` : Defines a dotted border
- `dashed` : Defines a dashed border
- `solid` : Defines a solid border
- `double` : Defines a double border
- `groove` : Defines a 3D grooved border. The effect depends on the border-color value
- `ridge` : Defines a 3D ridged border. The effect depends on the border-color value
- `inset` : Defines a 3D inset border. The effect depends on the border-color value
- `outset` : Defines a 3D outset border. The effect depends on the border-color value
- `none` : Defines no border
- `hidden` : Defines a hidden border

*The `border-style` property can have from one to four values (for the top border, right border, bottom border, and the left border).*

> Example

```css
p.dotted {border-style: dotted;}
p.dashed {border-style: dashed;}
p.solid {border-style: solid;}
p.double {border-style: double;}
p.groove {border-style: groove;}
p.ridge {border-style: ridge;}
p.inset {border-style: inset;}
p.outset {border-style: outset;}
p.none {border-style: none;}
p.hidden {border-style: hidden;}
p.mix {border-style: dotted dashed solid double;}
```

### CSS Border Width

*The `border-width` property specifies the width of the four borders.*

*The width can be set as a specific size (in px, pt, cm, em, etc) or by using one of the three pre-defined values: thin, medium, or thick:*

> Example

- Demonstration of the different border widths:

```css
p.one {
  border-style: solid;
  border-width: 5px;
}

p.two {
  border-style: solid;
  border-width: medium;
}

p.three {
  border-style: dotted;
  border-width: 2px;
}

p.four {
  border-style: dotted;
  border-width: thick;
}
```

### CSS Border Color

*The border-color property is used to set the color of the four borders.*

> The color can be set by:

- name : specify a color name, like "red"
- HEX : specify a HEX value, like "#ff0000"
- RGB : specify a RGB value, like "rgb(255,0,0)"
- HSL : specify a HSL value, like "hsl(0, 100%, 50%)"
- transparent

> Note: If border-color is not set, it inherits the color of the element.

> Example

- Demonstration of the different border colors:

```css
p.one {
  border-style: solid;
  border-color: red;
}

p.two {
  border-style: solid;
  border-color: green;
}

p.three {
  border-style: dotted;
  border-color: blue;
}
```

### CSS Border - Individual Sides

*From the examples on the previous pages, you have seen that it is possible to specify a different border for each side.*

*In CSS, there are also properties for specifying each of the borders (top, right, bottom, and left):*

> Example

```css
p {
  border-top-style: dotted;
  border-right-style: solid;
  border-bottom-style: dotted;
  border-left-style: solid;
}
```

### CSS Rounded Borders

*The border-radius property is used to add rounded borders to an element:*

```css
p {
  border: 2px solid red;
  border-radius: 5px;
}
```

## CSS Margins

*The CSS `margin` properties are used to create space around elements, outside of any defined borders.*

*With CSS, you have full control over the margins. There are properties for setting the margin for each side of an element (top, right, bottom, and left).*

### Margin - Individual Sides

*CSS has properties for specifying the margin for each side of an element:*

- `margin-top`
- `margin-right`
- `margin-bottom`
- `margin-left`

*All the margin properties can have the following values:*

- auto : the browser calculates the margin
- length : specifies a margin in px, pt, cm, etc.
- % : specifies a margin in % of the width of the containing element
- inherit : specifies that the margin should be inherited from the parent element

>Tip: Negative values are allowed.

> Example

- Set different margins for all four sides of a <p> element:

```css
p {
  margin-top: 100px;
  margin-bottom: 100px;
  margin-right: 150px;
  margin-left: 80px;
}
```

- Use the margin shorthand property with four values:

```css
p {
  margin: 25px 50px 75px 100px;
}
```

### The auto Value

*You can set the margin property to auto to horizontally center the element within its container.*

*The element will then take up the specified width, and the remaining space will be split equally between the left and right margins.*

> Example

- Use margin: auto:

```css
div {
  width: 300px;
  margin: auto;
  border: 1px solid red;
}
```

### The inherit Value

*This example lets the left margin of the `<p class="ex1">` element be inherited from the parent element (`<div>`):*

> Example

```css
- Use of the inherit value:

div {
  border: 1px solid red;
  margin-left: 100px;
}

p.ex1 {
  margin-left: inherit;
}
```

## CSS Padding

*The CSS padding properties are used to generate space around an element's content, inside of any defined borders.*

*With CSS, you have full control over the padding. There are properties for setting the padding for each side of an element (top, right, bottom, and left).*

### Padding - Individual Sides

*CSS has properties for specifying the padding for each side of an element:*

- `padding-top`
- `padding-right`
- `padding-bottom`
- `padding-left`

*All the padding properties can have the following values:*

- length : specifies a padding in px, pt, cm, etc.
- % : specifies a padding in % of the width of the containing element
- inherit : specifies that the padding should be inherited from the parent element

> Note: Negative values are not allowed.

> Example

- Set different padding for all four sides of a <div> element:  

```css
div {
  padding-top: 50px;
  padding-right: 30px;
  padding-bottom: 50px;
  padding-left: 80px;
}
```
- If the `padding` property has four values:

- padding: 25px 50px 75px 100px;
  - top padding is 25px
  - right padding is 50px
  - bottom padding is 75px
  - left padding is 100px

> Example

- Use the padding shorthand property with four values:

```css
div {
  padding: 25px 50px 75px 100px;
}
```

## CSS Height, Width and Max-width

- `height`	Sets the height of an element
- `max-height`	Sets the maximum height of an element
- `max-width`	Sets the maximum width of an element
- `min-height`	Sets the minimum height of an element
- `min-width`	Sets the minimum width of an element
- `width`	Sets the width of an element

### CSS height and width Values

*The height and width properties may have the following values:*

- `auto` : This is default. The browser calculates the height and width
- `length` : Defines the height/width in px, cm etc.
- `%` : Defines the height/width in percent of the containing block
- `initial` : Sets the height/width to its default value
- `inherit` : The height/width will be inherited from its parent value

> Example
- Set the height and width of a `<div>` element:

```css
div {
  height: 200px;
  width: 50%;
  background-color: powderblue;
}
```

- This `<div>` element has a height of 100 pixels and a max-width of 500 pixels: 

```css
div {
  max-width: 500px;
  height: 100px;
  background-color: powderblue;
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

#### position : static

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

#### position : relative

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

#### position : fixed

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

#### position : fixed

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

#### position : sticky

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
