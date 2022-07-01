# HTML <img width="40" src="https://media.giphy.com/media/5Lmn42BCOy99RaGRP7/giphy.gif"/>
*HTML İs an acronym which stands for Hyper Text Markup Language which is used for creating web pages and web applications. Let's see what is meant by Hypertext Markup Language, and Web page.*

## What is HTML

- *Hyper Text* : HyperText simply means "Text within Text." A text has a link within it, is a hypertext. Whenever you click on link which brings you to a new webpage, you have clicked on a hypertext. HyperText is a way to link two or more web pages (HTML documents) with each other.
- *Markup language* : A markup language is a computer language that is used to apply layout and formatting conventions to a text document. Markup language makes text more interactive and dynamic. It can turn text into images, tables, links, etc.
- *Web Page* : A web page is a document which is commonly written in HTML and translated bya web browser. A web page can be identified by entering an URL. A Web page can be of the static or dynamic type. With the help of HTML only, we can create static web pages.

**Hence, HTML is a markup language which is used for creating attractive web pages with the help of styling, and which looks in a nice format on a web browser. An HTML document is made of many HTML tags and each HTML tag contains different content.**

>Let's see a simple example of HTML.

```HTML
<!DOCTYPE>  
<html>  
 <head>  
   <title>Web page title</title>  
 </head>  
 <body>  
   <h1>Write Your First Heading</h1>  
   <p>Write Your First Paragraph.</p>  
 </body>  
</html>
```
## Description of HTML Example

- *!DOCTYPE* : It defines the document type or it instruct the browser about the version of HTML.

- *HTML* : This tag informs the browser that it is an HTML document. Text between html tag describes the web document. It is a container for all other elements of HTML.
except <!IDOCTYPE>

- *head* : it should be the first element inside the HTML element, which contains the metadata(information about the document). It must be closed before the body tag opens.

- *title* : As its name suggested, it is used to add title of that HTML page which appears at the top of the browser window. It must be placed inside the head tag and should close immediately. (Optional)

- *body* : Text between body tag describes the body content of the page that is visible to the end user. This tag contains the main content of the HTML document.

- *h1* : Text between H1 tag describes the first level heading of the webpage.

- *p* : Text between P tag describes the paragraph of the webpage.

## Brief History of HTML

*In the late 1980's, a physicist, Tim Berners-Lee who was a contractor at CERN, proposed a system for CERN researchers. In 1989, he wrote a memo proposing an internet based hypertext system.*

*Tim Berners-Lee is a known as the father of HTML.The first available description of HTML was a document called “HTML Tags” proposed by Tim in late 1991. The latest version of HTML is HTML5, wich we will learn laterin this tutorial.*

## HTML Versions

Since the time HTML was invented there are lots of HTML.versions in market, the brief introduction about the HTML version is given below:

- *HTML 1.0* : The first version of HTML was 1.0,wich was the barebones version of HTML language, and it was released in 1991.

- *HTML 2.0* : This was the next version which was released in 1995, and it was standard language version for website design. HTML 2.0 was able to support extra features such as form-based file upload, form elements such as text box,option button,ect.

- *HTML 3.2* : HTML 3.2 version was published by W3C in early 1997. This version was capable of creating tables and providing support for extra options for form elements. It can also support a web page with complex mathematical equations. It became an official standard for any browser till January 1997. Today it is practically supported by most of the browsers.

- *HTML 4.01* : HTML 4.01 version was released on December 1999, and it is a very stable version of HTML language. This version is the current official standard, and it provides added support for stylesheets (CSS) and scripting ability for various multimedia elements.

- *HTML5* : HTML5 is the newest version of HyperText Markup language. The first draft of this version was announced in January 2008. There are two major organizations one is W3C (World Wide Web Consortium), and another one is WHATWG( Web Hypertext Application Technology Working Group) which are involved in the development of HTML 5 version, and still, it is under development.

## Features of HTML

1) It is a very easy and simple language. It can be easily understood and modified.

2) It is very easy to make an effective presentation with HTML because it has a lot of formatting tags.

3) it is a markup language,so it provides a flexible way to design web pages along with the text.

4) It facilitates programmers to add a link on the web pages (by html anchor tag), so it enhances the interest of browsing of the user.

5) It is platform-independent because it can be displayed on any platform like Windows, Linux, and Macintosh, etc.

6) It facilitates the programmer to add Graphics, Videos, and Sound to the web pages which makes it more attractive and interactive.

7) HTML is a case-insensitive language, which means we can use tag either in lower-case or upper-case.

**NOTE: It is recommended to write all tags in lower-case for consistency, readability, etc**

## HTML-Tag syntax

*HTML is using tags for its syntax. A tag is composed with special characters: `<`,`>` and `/`. They are interpreted by softwares to compose an HTML element.*

### Decomposition of HTML elements

*HTML elements usually come in tag pairs.*

<img src="https://www.w3.org/community/webed/wiki/images/3/39/Elements.png">

> For opening a simple element with a start tag

- it starts with `<`
then a list of characters without space, the tagname (or element)
ends usually with a `>`.
Then closing the simple element with an end tag

- it starts with `</`
then the same list of characters without space, the tagname (or element)
ends usually with a `>`.

> If the tagname is "cite", then you get

```HTML
<cite></cite>
```
> Some elements do not have an end tag (because they are implied by the following tags). For example you might have seen:

```HTML
<br>
```

## Heading

*HTML defines six levels of headings. A heading element implies all the font changes, paragraph breaks before and after, and any white space necessary to render the heading. The heading elements are H1, H2, H3, H4, H5, and H6 with H1 being the highest (or most important) level and H6 the least. For example:*

```HTML
  <h1>Hello World</h1>
  <h2>Hello World</h2>
  <h3>Hello World</h3>
  <h4>Hello World</h4>
  <h5>Hello World</h5>
  <h6>Hello World</h6>
```
## Paragraph

*A paragraph always starts on a new line, and is usually a block of text.The HTML `<p>` element defines a paragraph.*

*A paragraph always starts on a new line, and browsers automatically add some white space (a margin) before and after a paragraph.*

```HTML
<p>This is a paragraph.</p>
<p>This is another paragraph;Lorem ipsum dolor sit amet consectetur adipisicing elit. Omnis officiis minus corporis atque quia ducimus vero voluptate ad quaerat magni fugit odio, voluptatum accusamus amet beatae nostrum sapiente dignissimos deleniti.</p>
<p>
This paragraph
contains a lot of lines
in the source code,
but the browser
ignores it.
</p>

<p>
This paragraph
contains         a lot of spaces
in the source         code,
but the        browser
ignores it.
</p>  
```
## HTML Elements

### HTML Formatting Elements


> Formatting elements were designed to display special types of text:

- `<b>` - Bold text
- `<strong>` - Important text
- `<i>` - Italic text
- `<em>` - Emphasized text
- `<mark>` - Marked text
- `<small>` - Smaller text
- `<del>` - Deleted text
- `<ins>` - Inserted text
- `<sub>` - Subscript text
- `<sup>` - Superscript text

### HTML Quotation and Citation Elements

*In this chapter we will go through the `<blockquote>`,`<q>`, `<abbr>`, `<address>`, `<cite>`, and `<bdo>` HTML elements.*

*The HTML `<blockquote>` element defines a section that is quoted from another source.*

> Browsers usually indent `<blockquote>` elements.

```HTML
<p>Here is a quote from WWF's website:</p>
<blockquote cite="http://www.worldwildlife.org/who/index.html">
For 50 years, WWF has been protecting the future of nature.
The world's leading conservation organization,
WWF works in 100 countries and is supported by
1.2 million members in the United States and
close to 5 million globally.
</blockquote>
```

### HTML `<q>` for Short Quotations

*The HTML `<q>` tag defines a short quotation.*

>Browsers normally insert quotation marks around the quotation.

```HTML
<p>WWF's goal is to: <q>Build a future where people live in harmony with nature.</q></p>
```

### HTML `<abbr>` for Abbreviations

*The HTML `<abbr>` tag defines an abbreviation or an acronym, like "HTML", "CSS", "Mr.", "Dr.", "ASAP", "ATM".*

*Marking abbreviations can give useful information to browsers, translation systems and search-engines.*

*Tip: Use the global title attribute to show the description for the abbreviation/acronym when you mouse over the element.*

```HTML
<p>The <abbr title="World Health Organization">WHO</abbr> was founded in 1948.</p>
```

### HTML `<address>` for Contact Information

*The HTML `<address>` tag defines the contact information for the author/owner of a document or an article.*

*The contact information can be an email address, URL, physical address, phone number, social media handle, etc.*

*The text in the `<address>` element usually renders in italic, and browsers will always add a line break before and after the `<address>` element.*

```HTML
Example
<address>
Written by John Doe.<br>
Visit us at:<br>
Example.com<br>
Box 564, Disneyland<br>
USA
</address>
```

### HTML `<cite>` for Work Title

*The HTML `<cite>` tag defines the title of a creative work (e.g. a book, a poem, a song, a movie, a painting, a sculpture, etc.).*

> Note: A person's name is not the title of a work.

*The text in the `<cite>` element usually renders in italic.*

```HTML
<p><cite>The Scream</cite> by Edvard Munch. Painted in 1893.</p>
```

### HTML `<bdo>` for Bi-Directional Override

*BDO stands for Bi-Directional Override.*

*The HTML `<bdo>` tag is used to override the current text direction:*

```HTML
<bdo dir="rtl">This text will be written from right to left</bdo>
```

## HTML Block and Inline Elements

*Every HTML element has a default display value, depending on what type of element it is.*

- There are two display values: block and inline
- A block-level element always starts on a new line and takes up the full width available
- An inline element does not start on a new line and it only takes up as much width as necessary
- The `<div>` element is a block-level and is often used as a container for other HTML elements
- The `<span>` element is an inline container used to mark up a part of a text, or a part of a document

**Block-level Elements**

*A block-level element always starts on a new line, and the browsers automatically add some space (a margin) before and after the element.*

*A block-level element always takes up the full width available (stretches out to the left and right as far as it can).*

> Two commonly used block elements are: `<p>` and `<div>`.

- The `<p>` element defines a paragraph in an HTML document.

- The `<div>` element defines a division or a section in an HTML document.

> Here are the block-level elements in HTML:

```HTML
<address> <article> <aside> <blockquote> <canvas> <dd> <div> <dl> <dt> <fieldset> <figcaption> <figure> <footer> <form> <h1>-<h6> <header> <hr> <li> <main> <nav> <noscript> <ol> <p> <pre> <section> <table> <tfoot> <ul> <video>
```

**Inline Elements**

> An inline element does not start on a new line.

> An inline element only takes up as much width as necessary.

> This is a `<span>` element inside a paragraph.

```HTML
<a> <abbr> <acronym> <b> <bdo> <big> <br> <button> <cite> <code> <dfn> <em> <i> <img> <input> <kbd> <label> <map> <object> <output> <q> <samp> <script> <select> <small> <span> <strong> <sub> <sup> <textarea> <time> <tt> <var>
```

### The `<div>` Element

*The `<div>` element is often used as a container for other HTML elements.*
*The `<div>` element has no required attributes, but `style`, `class` and `id` are common.*

> When used together with CSS, the `<div>` element can be used to style blocks of content:

```HTML
<div style="background-color:black;color:white;padding:20px;">
  <h2>London</h2>
  <p>London is the capital city of England. It is the most populous city in the United Kingdom, with a metropolitan area of over 13 million inhabitants.</p>
</div>
```

### The `<span>` Element

*The `<span>` element is an inline container used to mark up a part of a text, or a part of a document.*

*The `<span>` element has no required attributes, but `style`, `class` and `id` are common.*

> When used together with CSS, the `<span>` element can be used to style parts of the text:

```HTML
<p>My mother has <span style="color:blue;font-weight:bold">blue</span> eyes and my father has <span style="color:darkolivegreen;font-weight:bold">dark green</span> eyes.</p>
```
## HTML Form

*An HTML form is used to collect user input. The user input is most often sent to a server for processing.*

```html
<form>
.
form elements
.
</form>
```

### The `<input>` Element

*The HTML `<input>` element is the most used form element.*

*An `<input>` element can be displayed in many ways, depending on the type attribute.*

> Here are some examples:

- ```html<input type="text">```	: Displays a single-line text input field
- ```html<input type="radio">``` : Displays a radio button (for selecting one of many choices)
- ```html<input type="checkbox">``` :	Displays a checkbox (for selecting zero or more of many choices)
- ```html<input type="submit">``` :	Displays a submit button (for submitting the form)
- ```html<input type="button">``` :	Displays a clickable button

#### Text Fields

*The `<input type="text">` defines a single-line input field for text input.*
```html
<form>
  <label for="fname">First name:</label><br>
  <input type="text" id="fname" name="fname"><br>
  <label for="lname">Last name:</label><br>
  <input type="text" id="lname" name="lname">
</form>
```

#### The `<label>` Element

- Notice the use of the `<label>` element in the example above.

- The `<label>` tag defines a label for many form elements.

- The `<label>` element is useful for screen-reader users, because the screen-reader will read out loud the label when the user focus on the input element.

- The `<label>` element also help users who have difficulty clicking on very small regions (such as radio buttons or checkboxes) - because when the user clicks the text within the `<label>` element, it toggles the radio button/checkbox.

- The for attribute of the `<label>` tag should be equal to the id attribute of the `<input>` element to bind them together.

#### Radio Buttons

- The `<input type="radio">` defines a radio button.

*Radio buttons let a user select ONE of a limited number of choices.*

Example
A form with radio buttons:

<p>Choose your favorite Web language:</p>

```html
<form>
  <input type="radio" id="html" name="fav_language" value="HTML">
  <label for="html">HTML</label><br>
  <input type="radio" id="css" name="fav_language" value="CSS">
  <label for="css">CSS</label><br>
  <input type="radio" id="javascript" name="fav_language" value="JavaScript">
  <label for="javascript">JavaScript</label>
</form>
```

#### Checkboxes
- The `<input type="checkbox">` defines a checkbox.

*Checkboxes let a user select ZERO or MORE options of a limited number of choices.*

> Example
- A form with checkboxes:

```html
<form>
  <input type="checkbox" id="vehicle1" name="vehicle1" value="Bike">
  <label for="vehicle1"> I have a bike</label><br>
  <input type="checkbox" id="vehicle2" name="vehicle2" value="Car">
  <label for="vehicle2"> I have a car</label><br>
  <input type="checkbox" id="vehicle3" name="vehicle3" value="Boat">
  <label for="vehicle3"> I have a boat</label>
</form>
```

#### The Submit Button

- The `<input type="submit">` defines a button for submitting the form data to a form-handler.

*The form-handler is typically a file on the server with a script for processing input data.*

*The form-handler is specified in the form's action attribute.*

> Example
- A form with a submit button:

```html
<form action="/action_page.php">
  <label for="fname">First name:</label><br>
  <input type="text" id="fname" name="fname" value="John"><br>
  <label for="lname">Last name:</label><br>
  <input type="text" id="lname" name="lname" value="Doe"><br><br>
  <input type="submit" value="Submit">
</form>
```

#### The Name Attribute for `<input>`

*Notice that each input field must have a `name` attribute to be submitted.*

*If the `name` attribute is omitted, the value of the input field will not be sent at all.*

> Example
- This example will not submit the value of the "First name" input field: 

```html
<form action="/action_page.php">
  <label for="fname">First name:</label><br>
  <input type="text" id="fname" value="John"><br><br>
  <input type="submit" value="Submit">
</form>
```

## HTML Attributes

*HTML attributes provide additional information about HTML elements.*

- All HTML elements can have attributes
- Attributes provide additional information about elements
- Attributes are always specified in the start tag
- Attributes usually come in name/value pairs like: `name="value"`

### The href Attribute

*The `<a>` tag defines a hyperlink. The `href` attribute specifies the URL of the page the link goes to:*

```HTML
<a href="https://www.w3schools.com">Visit W3Schools</a>
```
### The src Attribute

*The `<img>` tag is used to embed an image in an HTML page. The `src` attribute specifies the path to the image to be displayed:*

```HTML
<img src="img_girl.jpg">
```
> There are two ways to specify the URL in the `src` attribute:

1. **Absolute URL** - Links to an external image that is hosted on another website. Example: src="https://www.w3schools.com/images/img_girl.jpg".

> *Notes*: External images might be under copyright. If you do not get permission to use it, you may be in violation of copyright laws. In addition, you cannot control external images; it can suddenly be removed or changed.

2. **Relative URL** - Links to an image that is hosted within the website. Here, the URL does not include the domain name. If the URL begins without a slash, it will be relative to the current page. Example: src="img_girl.jpg". If the URL begins with a slash, it will be relative to the domain. Example: src="/images/img_girl.jpg".

> *Tip*: It is almost always best to use relative URLs. They will not break if you change domain.

### The width and height Attributes

*The `<img>` tag should also contain the width and height attributes, which specifies the width and height of the image (in pixels):*

```HTML
<img src="img_girl.jpg" width="500" height="600">
```
### The alt Attribute

*The required `alt` attribute for the `<img>` tag specifies an alternate text for an image, if the image for some reason cannot be displayed. This can be due to slow connection, or an error in the `src` attribute, or if the user uses a screen reader.*

```HTML
<img src="img_girl.jpg" alt="Girl with a jacket">
```

> See what happens if we try to display an image that does not exist:

```HTML
<img src="img_girl.jpg" alt="Girl with a jacket">
```
### The style Attribute

*The `style` attribute is used to add styles to an element, such as color, font, size, and more.*

```HTML
<p style="color:red;">This is a red paragraph.</p>
```
### The Lang Attribute

**You should always include the `lang` attribute inside the `<html>` tag, to declare the language of the Web page. This is meant to assist search engines and browsers.**

> The following example specifies English as the language:

```HTML
<!DOCTYPE html>
<html lang="en">
<body>
...
</body>
</html>
```
*Country codes can also be added to the language code in the `lang` attribute. So, the first two characters define the language of the HTML page, and the last two characters define the country.*

> The following example specifies English as the language and United States as the country:

```HTML
<!DOCTYPE html>
<html lang="en-US">
<body>
...
</body>
</html>
```

### The `title` Attribute

**The `title` attribute defines some extra information about an element.**

> The value of the title attribute will be displayed as a tooltip when you mouse over the element:

```HTML
<p title="I'm a tooltip">This is a paragraph.</p>
```

## HTML Images

**Images can improve the design and the appearance of a web page.**

### HTML Images Syntax

*The HTML `<img>` tag is used to embed an image in a web page.*

*Images are not technically inserted into a web page; images are linked to web pages. The `<img>` tag creates a holding space for the referenced image.*

*The `<img>` tag is empty, it contains attributes only, and does not have a closing tag.*

- The `<img>` tag has two required attributes:

> `src` - Specifies the path to the image
> `alt` - Specifies an alternate text for the image

```HTML
<img src="img_chania.jpg" alt="Flowers in Chania">
```

## HTML Links

**Links are found in nearly all web pages. Links allow users to click their way from page to page.**

> The HTML `<a>` tag defines a hyperlink. It has the following syntax:

```HTML
<a href="https://www.w3schools.com/">Visit W3Schools.com!</a>
```

- The most important attribute of the <a> element is the href attribute, which indicates the link's destination.

- The link text is the part that will be visible to the reader.

- Clicking on the link text, will send the reader to the specified URL address.

> By default, links will appear as follows in all browsers:

- An unvisited link is underlined and blue
- A visited link is underlined and purple
- An active link is underlined and red

> HTML Links - The target Attribute

*By default, the linked page will be displayed in the current browser window. To change this, you must specify another target for the link.*

> The `target` attribute specifies where to open the linked document.

> The `target` attribute can have one of the following values:

- `_self` - Default. Opens the document in the same window/tab as it was clicked
- `_blank` - Opens the document in a new window or tab
- `_parent` - Opens the document in the parent frame
- `_top` - Opens the document in the full body of the window

> Absolute URLs vs. Relative URLs

- Both examples above are using an **absolute URL** (a full web address) in the `href` attribute.

- A local link (a link to a page within the same website) is specified with a **relative URL** (without the `"https://www"` part):

```HTML
<h2>Absolute URLs</h2>
<p><a href="https://www.w3.org/">W3C</a></p>
<p><a href="https://www.google.com/">Google</a></p>

<h2>Relative URLs</h2>
<p><a href="html_images.asp">HTML Images</a></p>
<p><a href="/css/default.asp">CSS Tutorial</a></p>
```

- Use the `<a>` element to define a link
- Use the `href` attribute to define the link address
- Use the target attribute to define where to open the linked document
- Use the `<img>` element (inside `<a>`) to use an image as a link
- Use the `mailto:` scheme inside the `href` attribute to create a link that opens the user's email program
 
```HTML
<a href="default.asp">
<img src="smiley.gif" alt="HTML tutorial" style="width:42px;height:42px;">
</a>

<a href="mailto:someone@example.com">Send email</a>

<button onclick="document.location='default.asp'">HTML Tutorial</button>

<a href="https://www.w3schools.com/html/" title="Go to W3Schools HTML section">Visit our HTML Tutorial</a>
```

## HTML Tables

*HTML tables allow web developers to arrange data into rows and columns.*

```html
<table>
  <tr>
    <th>Company</th>
    <th>Contact</th>
    <th>Country</th>
  </tr>
  <tr>
    <td>Alfreds Futterkiste</td>
    <td>Maria Anders</td>
    <td>Germany</td>
  </tr>
  <tr>
    <td>Centro comercial Moctezuma</td>
    <td>Francisco Chang</td>
    <td>Mexico</td>
  </tr>
</table>
```

### HTML Table Tags

- `<table>`	Defines a table
- `<th>`	Defines a header cell in a table
- `<tr>`	Defines a row in a table
- `<td>`	Defines a cell in a table
- `<caption>`	Defines a table caption
- `<colgroup>`	Specifies a group of one or more columns in a table for formatting
- `<col>`	Specifies column properties for each column within a <colgroup> element
- `<thead>`	Groups the header content in a table
- `<tbody>`	Groups the body content in a table
- `<tfoot>`	Groups the footer content in a table

## HTML Lists

*HTML lists allow web developers to group a set of related items in lists.*

```html
An unordered HTML list:

- Item
- Item
- Item
- Item

An ordered HTML list:

1. First item
2. Second item
3. Third item
4. Fourth item
```

### Unordered HTML List

*An unordered list starts with the `<ul>` tag. Each list item starts with the `<li>` tag.*

- The list items will be marked with bullets (small black circles) by default:

```html
<ul>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul>
```

### Ordered HTML List

*An ordered list starts with the `<ol>` tag. Each list item starts with the `<li>` tag.*

- The list items will be marked with numbers by default:

```html
<ol>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>
```

### HTML List Tags

- `<ul>`	Defines an unordered list
- `<ol>`	Defines an ordered list
- `<li>`	Defines a list item
- `<dl>`	Defines a description list
- `<dt>`	Defines a term in a description list
- `<dd>`	Describes the term in a description list

## HTML Layout Elements and Techniques

### HTML Layout Elements

*HTML has several semantic elements that define the different parts of a web page:*

<div align="center">
  <img width="50px" src="https://www.w3schools.com/html/img_sem_elements.gif"/>
</div>

- `<header>` : Defines a header for a document or a section
- `<nav>` : Defines a set of navigation links
- `<section>` : Defines a section in a document
- `<article>` : Defines an independent, self-contained content
- `<aside>` : Defines content aside from the content (like a sidebar)
- `<footer>` : Defines a footer for a document or a section
- `<details>` : Defines additional details that the user can open and close on demand
- `<summary>` : Defines a heading for the `<details>` element

### HTML Layout Techniques

*There are four different techniques to create multicolumn layouts. Each technique has its pros and cons:*

- CSS framework
- CSS float property
- CSS flexbox
- CSS grid

