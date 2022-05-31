# The 4 Layers Of The Web
***The browser sends an HTTP request message to the server, asking it to send a copy of the website to the client (you go to the shop and order your goods). This message, and all other data sent between the client and the server, is sent across your internet connection using TCP/IP.***

> How does the web work step by step?

![Image result for how the web works](https://res.cloudinary.com/academind-gmbh/image/upload/f_auto,q_auto:eco/dpr_2.0,w_400,c_limit,g_center/v1/academind.com/content/tutorials/how-the-web-works/how-the-web-works-big-picture)

> Let's have a look at all four steps.
- Step 1 - URL Gets Resolved.
- Step 2 - Request Is Sent.
- Step 3 - Response Is Parsed.
- Step 4 - Page Is Displayed.
- Server-side.
- Browser-side.

# The 3 Layers Of The Front-end
- HTML: The Structure Layer.
- CSS: The Styles Layer.
- JavaScript: The Behavior Layer.

![Image result for the 3 layer of the Front end](https://miro.medium.com/max/1400/1*xPzUFLBLfZ4AqXTPaK9B1g.jpeg)

# Web Developer Tool : CMS (Content Management System)
***A content management system, often abbreviated as CMS, is software that helps users create, manage, and modify content on a website without the need for specialized technical knowledge.***

***In simpler language, a content management system is a tool that helps you build a website without needing to write all the code from scratch (or even know how to code at all).***

*Exemples: Wix, WordPress,...*

# Web Developer Tool : In-Browser Tool
***Every modern web browser includes a powerful suite of developer tools. These tools do a range of things, from inspecting currently-loaded HTML, CSS and JavaScript to showing which assets the page has requested and how long they took to load.***

![Image result for in-bowser developer tool](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/What_are_browser_developer_tools/devtools_63_inspector.png)

# Web Developer Tool : Online Tools

![Image result for online developer tools](https://www.turing.com/blog/wp-content/uploads/2022/01/Tools-for-testing.jpg)

***Modern trends and webapps have dramatically changed the way web developers can build. Obviously you need some type of IDE to code new files and save them for deployment. But what about just testing your code snippets? There are more tools available now than ever before!***
***All of these apps require an Internet connection, and some of the more advanced editors offer pro plans to upgrade your account features. But most of these tools will surely come in handy when you’re scrambling to debug a block of JavaScript or PHP.***

# Web Developer Tool : Integrated Developement Environmemt (IDE)
***An integrated development environment (IDE) is a software suite that consolidates basic tools required to write and test software. Developers use numerous tools throughout software code creation, building and testing. Development tools often include text editors, code libraries, compilers and test platforms.***

![Image result for web development ide](https://miro.medium.com/max/1400/1*hCOOFW4sQi1jz7-2u1sJGQ.png)

# HTML(HyperText Markup Language)
***HTML is the most basic building block of the Web. It defines the meaning and structure of web content.***

***"Hypertext" refers to links that connect web pages to one another, either within a single website or between websites. Links are a fundamental aspect of the Web. By uploading content to the Internet and linking it to pages created by other people, you become an active participant in the World Wide Web.***

***HTML uses "markup" to annotate text, images, and other content for display in a Web browser. HTML markup includes special "elements" such as head, title, body, header, footer, article, section, p, div, span, img, aside, audio, canvas, datalist, details, embed, nav, output, progress, video, ul, ol, li and many others.***
  
***An HTML element is set off from other text in a document by "tags", which consist of the element name surrounded by "<" and ">". The name of an element inside a tag is case insensitive. That is, it can be written in uppercase, lowercase, or a mixture. For example, the <title> tag can be written as <Title>, <TITLE>, or in any other way. However, the convention and recommended practice is to write tags in lowercase.***

## Document Type Definition (DTD)
***a DTD defines the structure and the legal elements and attributes of an XML document.***
  
  >How to translate HTML code to a page
  
- Strict
- Transional
- Frameset
  
## Head: The Document Metadata (Header) element
***The <head> HTML element contains machine-readable information (metadata) about the document, like its title, scripts, and style sheets.***

***In HTML, the doctype is the required "!DOCTYPE html" preamble found at the top of all documents. Its sole purpose is to prevent a browser from switching into so-called "quirks mode" when rendering a document; that is, the "!DOCTYPE html" doctype ensures that the browser makes a best-effort attempt at following the relevant specifications, rather than using a different rendering mode that is incompatible with some specifications.***
  
*Exemple*
  
```html
<!doctype html>
<html>
  <head>
    <meta charset="UTF-8">
    <link rel="stylesheet" href="styles.css">
    <title>Document title</title>
  </head>
</html>
```

### Definition and Usage
  
- The meta tag defines metadata about an HTML document. Metadata is data (information) about data.
- meta tags always go inside the <head> element, and are typically used to specify character set, page description, keywords, author of the document, and viewport settings.
- Metadata will not be displayed on the page, but is machine parsable.
- Metadata is used by browsers (how to display content or reload page), search engines (keywords), and other web services.
- There is a method to let web designers take control over the viewport (the user's visible area of a web page), through the <meta> tag (See "Setting The Viewport" example below).
- The link tag defines the relationship between the current document and an external resource.
- The link tag is most often used to link to external style sheets or to add a favicon to your website.
- The link element is an empty element, it contains attributes only.
- The title tag defines the title of the document. The title must be text-only, and it is shown in the browser's title bar or in the page's tab.
- The title tag is required in HTML documents!
- The contents of a page title is very important for search engine optimization (SEO)! The page title is used by search engine algorithms to decide the order when listing pages in search result.
  
## Body: The Document (Body) element
***The body HTML element represents the content of an HTML document,such as headings, paragraphs, images, hyperlinks, tables, lists, etc. There can be only one body element in a document.***

*Exemple*
*Exemple*

```html
<html>
  <head>
    <title>Document title</title>
  </head>
  <body>
    <h1>This is a heading</h1>
    <p>This is a paragraph.</p>
  </body>
</html>
```

# Text and Lists
  
***p: The Paragraph element***

*The p HTML element represents a paragraph. Paragraphs are usually represented in visual media as blocks of text separated from adjacent blocks by blank lines and/or first-line indentation, but HTML paragraphs can be any structural grouping of related content, such as images or form fields.*
  
*Exemple*
  
```html
<html>
  <head>
    <title>Document title</title>
  </head>
  <body>
    <p>Geckos are a group of usually small, usually nocturnal lizards. They are found on every continent except Australia.</p>
    <p>Some species live in houses where they hunt insects attracted by artificial light.</p>
  </body>
</html>
```
  
***HTML Formating Elements***

- b : Bold text
- strong : Important text
- i : Italic text
- em : Emphasized text
- mark : Marked text
- small : Smaller text
- del : Deleted text
- ins : Inserted text
- sub : Subscript text
- sup : Superscript text

 
