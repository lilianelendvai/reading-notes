# 201 Course: Class 1 Reading Notes

## **Getting Started**

1. Compose a short poem describing how HTTP sends data between computers.

Mighty HTTP,

Take thy message and send it at lightning speed;

Give voice to my greatest desires -

I, the Client,

Rely upon your powers of translation.

Command the Server to do thy bidding

Oh, great Application Protocol, 

Use your wily charm: 

Bridge the divide from browser to DNS server.

Speak true, dear Hypertext Transfer Protocol!

Cross the TCP/IP for me

And utter those sweet words of "200 OK"

Carry forth thy data packets

And teach me the meaning of a complete web page


2. Describe how HTML, CSS, and JS files are "parsed" in the browser.

- When a browser sends requests to servers for HTML files, those files typically include `<link>` elements (for external CSS stylesheets) and `<script>` elements (for external JavaScript scripts)
- Parsing is when the browser turns the data it receives over the network into the DOM and CSSOM, which is used by the renderer to paint a page to the screen
- The files are parsed in a particular order: HTML first, then external CSS stylesheets, then JavaScript scripts
- The browser generates an in-memory DOM tree from the parsed HTML and then an in-memory CSSOM structure from the parsed CSS; it then compiles and executes the parsed JavaScript
- The browser builds the DOM tree, applies the styles from the CSSOM tree, and executes the JavaScript, leading to the page content the user sees

3. How can you find images to add to a Website?

- Google images is a way to find images, but to reduce the likelihood of violating copyright, use Google's license filter: tools -> usage rights -> creative commons licenses

4. How do you create a `String` vs a `Number` in JavaScript?

- Enclose the value in single quotation marks to signify it's a string
- ex: let exampleVariable = `Eleven`;
- Numbers don't have quotes around them
- ex: let exampleVariable = 11;

5. What is a `Variable` and why are they important in JavaScript?

- A variable is a container to store a value
- It is a named reference to a value; that way, an unpredictable value can be accessed through a predetermined name
- Declare a variable with the `let` keyword, followed by the name you give to the variable

## **Introduction to HTML**

1. What is an HTML attribute?

- It contains extra info about the element that won't appear in the content
-  A piece of markup language that adjusts the behavior or display of an HTML element

2. Describe the Anatomy of an HTML element.

- Element: the opening tag, content, and closing tag
- Opening Tag: The name of the element wrapped in opening and closing angle brackets
- Content: The content of the element
- Closing Tag: The same as the opening tag plus a slash forward before the element name


3. What is the Difference between `<article>` and `<section>` element tags?

- `<article>` encloses a block of related content that makes sense on its own and doesn't require the rest of the page
- `<section>` is more of grouping together a single part of the page and typically has a heading, and it usually has a single piece of functionality

4. What Elements does a “typical” website include?

- header: a section across the top that typically stays the same from one webpage to another
- navigation bar: links to main sections of the site
- main content: where most of the content goes and varies from page to page
- sidebar: peripheral information that can go with the main content or be separate
- footer: a section across the bottom of the page that contains usually secondary information 

5. How does metadata influence Search Engine Optimization?

- Metadata - the data that describes data - can be useful for SEO, as it can specify a description to use keywords relating to the content of one's page, therefore having it appear higher in relevant searches by search engines

6. How is the `<meta>` HTML tag used when specifying metadata?

- ex: `<meta charset="utf-8">` is an element that specifies the document's character encoding (the character set the document can use)


## **Miscellaneous**

### **How to start to design a Website**

1. What is the first step to designing a Website?

- Instead of immediately turning to the technical, first figure out what you want to accomplish: create your goals and vision, AKA project ideation

2. What is the most important question to answer when designing a Website?

- It is: What exactly do I want to accomplish?

### **Semantics.**

1. Why should you use an `<h1>` element over a `<span>` element to display a top level heading?

- An `<h1>` element is a semantic element, meaning it gives the text it wraps around a role, so screen readers will understand its meaning, search engines will consider it an important keyword, developers will better understand the type of data it is, and more 
`<span>` has no semantic value, so it doesn't come with the benefits listed above

2. What are the benefits of using semantic tags in our HTML?

- Search engines will see it as important and have it influence the page's search rankings
- Screen readers will use it to help those visually impaired navigate the page
- It makes it easier to find blocks of meaningful code
- Developers get a better idea of the type of data that is populated
- Semantic naming mirrors proper custom element/component naming

### **What is JavaScript?**

1. Describe 2 things that require JavaScript in the Browser?

- When a web page does more than just display static information, so: display timely content updates, interactive maps, animated graphics, scrolling videos, etc.

2. How can you add JavaScript to an HTML document?

- Internal JavaScript: use `<script>` `</script>` element, and add JavaScript inside of it
- External JavaScript: create a new file in the same directors as your HTML file, call it `script.js`, and replace any `<script>` elements with `<script src="script.js"></script>`
- Inline JavaScript: considered bad practice and inefficient