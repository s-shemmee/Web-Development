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
#### The src Attribute

*The `<img>` tag is used to embed an image in an HTML page. The `src` attribute specifies the path to the image to be displayed:*

```HTML
<img src="img_girl.jpg">
```
> There are two ways to specify the URL in the `src` attribute:

1. **Absolute URL** - Links to an external image that is hosted on another website. Example: src="https://www.w3schools.com/images/img_girl.jpg".

*Notes*: External images might be under copyright. If you do not get permission to use it, you may be in violation of copyright laws. In addition, you cannot control external images; it can suddenly be removed or changed.

2. **Relative URL** - Links to an image that is hosted within the website. Here, the URL does not include the domain name. If the URL begins without a slash, it will be relative to the current page. Example: src="img_girl.jpg". If the URL begins with a slash, it will be relative to the domain. Example: src="/images/img_girl.jpg".

*Tip*: It is almost always best to use relative URLs. They will not break if you change domain.

#### The width and height Attributes

*The `<img>` tag should also contain the width and height attributes, which specifies the width and height of the image (in pixels):*

```HTML
<img src="img_girl.jpg" width="500" height="600">
```
#### The alt Attribute

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

*You should always include the `lang` attribute inside the `<html>` tag, to declare the language of the Web page. This is meant to assist search engines and browsers.*

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

## The title Attribute

*The `title` attribute defines some extra information about an element.*

> The value of the title attribute will be displayed as a tooltip when you mouse over the element:

```HTML
<p title="I'm a tooltip">This is a paragraph.</p>
```

## Heading

*HTML defines six levels of headings. A heading element implies all the font changes, paragraph breaks before and after, and any white space necessary to render the heading. The heading elements are H1, H2, H3, H4, H5, and H6 with H1 being the highest (or most important) level and H6 the least. For example:*

```HTML
<H1>This is a top level heading</H1> Here is some text.
<H2>Second level heading</H2> Here is some more text.
```
## Paragraph

*A paragraph always starts on a new line, and is usually a block of text.The HTML `<p>` element defines a paragraph.*

*A paragraph always starts on a new line, and browsers automatically add some white space (a margin) before and after a paragraph.*

```HTML
<p>This is a paragraph.</p>
<p>This is another paragraph;
  Lorem ipsum dolor sit amet consectetur adipisicing elit. Omnis officiis minus corporis atque quia ducimus vero voluptate ad quaerat magni fugit odio, voluptatum accusamus amet beatae nostrum sapiente dignissimos deleniti.</p>
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

