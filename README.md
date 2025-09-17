# TOP_HTML_Boilerplate

A basic HTML boilerplate

An HTML document is like an infinitely stackable sandwich sandwich - a sandwich made of sandwiches, which can each made of other sandwiches.

Consider this: a basic sandwich has two slices of bread (like opening and closing tags) with filling in between (the content). The bread defines where the sandwich starts and ends, and the filling gives it meaning (is an empty pair of bread slices really a sandwich?).

Change the bread - rye, sourdough, potato - and the sandwich takes on new qualities. It is the same with tags. Most breads (and tags) work best with certain content.

Now's the exciting part. If I take a PB&Honey sandwich and squeeze it between two slices of a Spam-and-mayo sandwich, I’ve made a sandwich sandwich! And I can keep layering and get creative: a chicken sandwich on top of a black bean & cabbage sandwich sandwich, all wrapped between two buttered slices of toast? Still a valid sandwich sandwich.

That’s how HTML works. You can stack and nest various elements within others and still create a single, valid document.

!DOCTYPE html<br>
Defines the version of HTML that the browser should render. For HTML5, the version is defined simply by using "html".

html<br>
The html tag is the root element of the web page. All other elements are child elements of html.

lang="en"<br>
The lang attribute inside of the html tag is used to declare the language of the webpage. It is used by search engines, web browsers, and accessibility tools and addons.

head<br>
It's maybe a little more helpful to think of this as the "mind" rather than "head". The head element acts as a container for the webpage's metadata and information used to render the page properly.

meta<br>
This is a void element (self closing) and does not require a meta tag. It is used to define the webpage's metadata, including character set, page description, keywords, author, and viewport settings. It is used by the browser, search engines, and other web services.

charset="UTF-8"<br>
The charset attribute specifies the character (text) encoding for the HTML document. The "UTF-8" character set is encouraged by the HTML5 specification and covers almost every character and symbol used throughout the world.

title<br>
The title element is used to provide webpages with the title that you see on your browser's tab! Without it, the title would default to the page's file name (in this case, "index.html").

body<br>
The body element is used as a container for all of the webpage's content - text, images, links, videos, etc.
