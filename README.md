# class-01.md
# class-01.md

## 1.Compose a short poem describing how HTTP sends data between computers.
The browser sends an HTTP request message to the server, asking it to send a copy of the website to the client (you go to the shop and order your goods). This message, and all other data sent between the client and the server, is sent across your internet connection using TCP/IP.

If the server approves the client's request, the server sends the client a "200 OK" message, which means "Of course you can look at that website! Here it is", and then starts sending the website's files to the browser as a series of small chunks called data packets (the shop gives you your goods, and you bring them back to your house).

The browser assembles the small chunks into a complete web page and displays it to you (the goods arrive at your door — new shiny stuff, awesome!).

## 2.Describe how HTML, CSS, and JS files are “parsed” in the browser.
- The browser parses the HTML file first, leading to the recognition of any `<link>`-element references to external CSS stylesheets and any `<script>`-element references to scripts.
- As the browser parses the HTML, it sends requests back to the server for any CSS files it has found from `<link>` elements, and any JavaScript files it has found from `<script>` elements. It then parses the CSS and JavaScript.
- The browser generates an in-memory DOM tree from the parsed HTML, an in-memory CSSOM structure from the parsed CSS, and compiles and executes the parsed JavaScript.
- As the browser builds the DOM tree, applies the styles from the CSSOM tree, and executes the JavaScript, a visual representation of the page is painted to the screen, and the user sees the page content and can begin to interact with it.

## 3. How can you find images to add to a Website?
Stock Photo Websites: These websites offer high-quality images, often both free and paid.

## 4.How do you create a String vs a Number in JavaScript?
JavaScript strings are for storing and manipulating text.

| Variable | Explanation                                                                                   | Example                                       |
|----------|-----------------------------------------------------------------------------------------------|-----------------------------------------------|
| String   | This is a sequence of text known as a string. To signify that the value is a string, enclose it in single or double quote marks. | `let myVariable = 'Bob';` or `let myVariable = "Bob";` |
| Number   | This is a number. Numbers don't have quotes around them.                                      | `let myVariable = 10;`                        |

## 5.What is a Variable and why are they important in JavaScript?
A variable is a container that stores values. Variables are fundamental building blocks in JavaScript (and most programming languages). They provide a way to label, store, and manipulate data, making code more efficient, readable, and organized. Without variables, programming tasks would be cumbersome, repetitive, and error-prone.

## Introduction to HTML

### 1. What is an HTML attribute?
An HTML attribute provides additional information about an HTML element and helps define its properties or behavior. `<tagname attribute_name="attribute_value">Content</tagname>`

### 2. Describe the Anatomy of an HTMl element.
The anatomy of an HTML element encompasses its opening tag, closing tag, element name, content, and any attributes, all of which work together to define the element's structure, content, and behavior in a web document. `<elementName attribute1="value1" attribute2="value2">Content</elementName>`

### 3. What is the Difference between <article> and <section> element tags?
The `<section>` element defines a section in a document. Examples of where a `<section>` element can be used include chapters, introductions, news items, and contact information. The `<article>` element specifies independent, self-contained content. Examples of where the `<article>` element can be used include forum posts, blog posts, user comments, product cards, and newspaper articles.

### 4. What Elements does a “typical” website include?
- **header**: `<header>`
- **navigation bar**: `<nav>`
- **main content**: `<main>`, with various content subsections represented by `<article>`, `<section>`, and `<div>` elements.
- **sidebar**: `<aside>`; often placed inside `<main>`.
- **footer**: `<footer>`

### 5. How does metadata influence Search Engine Optimization?
Search engines crawl your web pages to recognize keywords and other information. Then, they compare that with the metadata to organize your web page in the SERP. Using metadata boosts your SEO efforts because it’s written in the search engine’s language. This helps search engines better understand the topic of your web pages and content. It also helps them display more relevant results to searchers.

### 6. How is the <meta> HTML tag used when specifying metadata?
HTML `<meta>` tag is used to represent the metadata about the HTML document. It specifies page description, keywords, copyright, language, author of the documents, etc. The metadata does not display on the webpage, but it is used by search engines, browsers, and other web services which scan the site or webpage to know about the webpage.























1-Compose a short poem describing how HTTP sends data between computers.
The browser sends an HTTP request message to the server, asking it to send a copy of the website to the client (you go to the shop and order your goods). This message, and all other data sent between the client and the server, is sent across your internet connection using TCP/IP.
If the server approves the client's request, the server sends the client a "200 OK" message, which means "Of course you can look at that website! Here it is", and then starts sending the website's files to the browser as a series of small chunks called data packets (the shop gives you your goods, and you bring them back to your house).
The browser assembles the small chunks into a complete web page and displays it to you (the goods arrive at your door — new shiny stuff, awesome!).

2-Describe how HTML, CSS, and JS files are “parsed” in the browser.
-The browser parses the HTML file first, and that leads to the browser recognizing any <link>-element references to external CSS stylesheets and any <script>-element references to scripts.
-As the browser parses the HTML, it sends requests back to the server for any CSS files it has found from <link> elements, and any JavaScript files it has found from <script> elements, and from those, then parses the CSS and JavaScript.
-The browser generates an in-memory DOM tree from the parsed HTML, generates an in-memory CSSOM structure from the parsed CSS, and compiles and executes the parsed JavaScript.
-As the browser builds the DOM tree and applies the styles from the CSSOM tree and executes the JavaScript, a visual representation of the page is painted to the screen, and the user sees the page content and can begin to interact with it.
3-How can you find images to add to a Website?
Stock Photo Websites: These websites offer high-quality images, often both free and paid.
4-How do you create a String vs a Number in JavaScript?
JavaScript strings are for storing and manipulating text.
| Variable | Explanation                                                                                   | Example                                       |
|----------|-----------------------------------------------------------------------------------------------|-----------------------------------------------|
| String   | This is a sequence of text known as a string. To signify that the value is a string, enclose it in single or double quote marks. | `let myVariable = 'Bob';` or `let myVariable = "Bob";` |
| Number   | This is a number. Numbers don't have quotes around them.                                      | `let myVariable = 10;`                        |

5-What is a Variable and why are they important in JavaScript?
Variable is  containers that store values.variables are fundamental building blocks in JavaScript (and most programming languages). They provide a way to label, store, and manipulate data, making code more efficient, readable, and organized. Without variables, programming tasks would be cumbersome, repetitive, and error-prone.


Introduction to HTML
1-What is an HTML attribute?
An HTML attribute provides additional information about an HTML element and helps define its properties or behavior.
<tagname attribute_name="attribute_value">Content</tagname>

All HTML elements can have attributes
The href attribute of <a> specifies the URL of the page the link goes to
The src attribute of <img> specifies the path to the image to be displayed
The width and height attributes of <img> provide size information for images
The alt attribute of <img> provides an alternate text for an image
The style attribute is used to add styles to an element, such as color, font, size, and more
The lang attribute of the <html> tag declares the language of the Web page
The title attribute defines some extra information about an element
2-Describe the Anatomy of an HTMl element.
The anatomy of an HTML element encompasses its opening tag, closing tag, element name, content, and any attributes, all of which work together to define the element's structure, content, and behavior in a web document.
<elementName attribute1="value1" attribute2="value2">Content</elementName>

3-What is the Difference between <article> and <section> element tags?
The <section> element defines a section in a document.
Examples of where a <section> element can be used:

Chapters
Introduction
News items
Contact information
The <article> element specifies independent, self-contained content.
Examples of where the <article> element can be used:

Forum posts
Blog posts
User comments
Product cards
Newspaper articles

4-What Elements does a “typical” website include?
header: <header> .
navigation bar: <nav> .
main content: <main> , with various content subsections represented by <article> , <section> , and <div> elements.
sidebar: <aside> ; often placed inside <main> .
footer: <footer> .

5-How does metadata influence Search Engine Optimization?
Search engines crawl your web pages to recognize keywords and other information. Then, they compare that with the metadata to organize your web page in the SERP. Using metadata boosts your SEO efforts because it’s written in the search engine’s language. This helps search engines better understand the topic of your web pages and content. It also helps them display more relevant results to searchers.
6-How is the <meta> HTML tag used when specifying metadata?
HTML <meta> tag is used to represent the metadata about the HTML document. It specifies page description, keywords, copyright, language, author of the documents, etc.

The metadata does not display on the webpage, but it is used by search engines, browsers and other web services which scan the site or webpage to know about the webpage.
1. <meta charset="utf-8">  
It defines the character encoding. The value of charset is "utf-8" which means it will support to display any language.

2. <meta name="keywords" content="HTML, CSS, JavaScript, Tutorials">  
It specifies the list of keyword which is used by search engines.

3. <meta name="description" content="Free Online tutorials">  
It defines the website description which is useful to provide relevant search performed by search engines.

4. <meta name="author" content="thisauthor">  
It specifies the author of the page. It is useful to extract author information by Content management system automatically.

5. <meta name="refresh" content="50">  
It specifies to provide instruction to the browser to automatically refresh the content after every 50sec (or any given time).

6. <meta http-equiv="refresh" content="5; url=https://www.javatpoint.com/html-tags-list">    
In the above example we have set a URL with content so it will automatically redirect to the given page after the provided time.

7. <meta name="viewport" content="width=device-width, initial-scale=1.0">  
It specifies the viewport to control the page dimension and scaling so that our website looks good on all devices. If this tag is present, it indicates that this page is mobile device supported.

