# Question Week1 



When a user enters an URL into the browser, the browser sends a request to the server for the desired webpage. The server then sends back the webpage, which is composed of HTML, CSS, and JavaScript files.

The main functionality of the browser is to display webpages to the user. It does this by using a rendering engine to process the HTML, CSS, and JavaScript files and render the webpage on the user's screen.

The high level components of a browser include the user interface, rendering engine, network stack, and JavaScript engine.

The rendering engine is responsible for displaying the webpage on the user's screen. It uses parsers to interpret and process the HTML, CSS, and JavaScript files and construct the webpage.

HTML parser is used to interpret the HTML code, it converts the HTML code into a tree structure called the Document Object Model (DOM). CSS parser is used to interpret the CSS code, it applies the CSS styles to the elements of the DOM tree. JavaScript parser is used to interpret the JavaScript code, it adds dynamic functionality to the webpage.

Script processors are responsible for executing JavaScript code. They use the JavaScript engine to execute the JavaScript code.

The tree construction is the process by which the browser builds the Document Object Model (DOM) tree from the HTML code.

The order of script processing is as follows:

The browser starts by loading the HTML code and building the DOM tree.
It then loads the CSS code and applies the styles to the elements of the DOM tree.
Finally, it loads the JavaScript code and executes it, adding dynamic functionality to the webpage.

Layout and Painting is the final step in displaying the webpage on the user's screen. The browser uses the information in the DOM tree and the styles specified in the CSS code to determine the layout of the webpage. It then paints the elements of the webpage on the user's screen.

