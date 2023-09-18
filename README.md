# class-01.md
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

