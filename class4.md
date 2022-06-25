# Class 4 Reading Notes

## **Wireframe and Design**

### **Intro to Wireframing**
- Wireframing is a practice allowing people (primarily UX Designers) to define and plan the information hierarchy of their design for a website, app, or product
- User research helps the designer or clients focus on how the user will process information on a site
- Wireframing shows where all the information is going to go in plain black and white diagrams; without the distraction of colors, typeface choices or text, wireframing lets the designer plan the layout and interaction of the interface
- Some people draw their wireframes by hand, whereas others feel more comfortable using software like Invision or Balsamiq (there are many available)


### **6 Steps to make a Wireframe**

1. Do your research: create user personas, define use cases, dig into prevailing UX trends and best practices
2. Prepare your research for quick reference: make a cheatsheet to help you keep track of important quantitative and qualitative data
3. Make sure you have your user flow mapped out: good information architecture = happy customers = increases in revenue = happy managers
4. Draft, don't draw. Sketch, don't illustrate: wireframing is for outlining and representing features and formats, not for illustrating fine detail
5. Add some detail and get testing: add informational details to prepare the wireframe for its upgrade (think usability convention, calls-to-action, trust-building elements, and tooltips)
6. Start turning your wireframes into prototypes: after feedback from your first prototype, you can develop high-fidelity prototypes

### **3 Key Wireframe Principles**

1. Clarity: wireframes should answer what the site page is, what the user can do there, and if it satisfies their needs
2. Confidence: increase user confidence through easy navigation and clear call-to-actions
3. Simplicity: cut the 'fluff' so users get less distracted

---

## **Mozilla HTML Basics**

### **What is HTML?**

- HyperText Markup Language (HTML) is the code that's used to structure a web page and its content
- HTML is a markup language that defines the structure of your content
- HTML consists of elements, which are used to enclose/wrap different parts of the content to make them appear or act a certain way
- Enclosing tags affect words or images, such as making it a hyperlink, italicizing, changing font size

#### *Anatomy of an HTML element*
1. The opening tag: consists of the name of the element wrapped in opening and closing angle brackets
2. The closing tag: same as opening tag except it includes a forward slash before the element name; this is where the element ends
3. The content: the content of the element
4. The element: the opening tag, the closing tag, and the content all together

#### *Attributes*

- Attributes contain extra information about the element that you don't want to appear in the actual content. Attributes should always have:
1. A space between it and the element name (or the previous attribute, if the element already has one or more attributes)
2. The attribute name followed by an equal sign
3. The attribute value wrapped by opening and closing quotation marks

#### *Nesting Elements*

- Nesting is putting elements inside other elements
- Elements have to open and close correctly so that they are clearly inside or outside one another

#### *Empty Elements*

- Empty elements are when some elements have no content

#### *Anatomy of an HTML document*

- `<!DOCTYPE html>` makes sure your document behaves correctly
- `<html></html>` wraps all the content on the entire page and is sometimes known as the root element
- `<head></head>` acts as a container for the content you want to include on the HTML page that isn't the content you are showing to your page's viewers
- `<meta charset="utf-8"> makes it so it can now handle any textual content you might put in it
- `<body></body>` contains all the content you want to show to web users when they visit your page

### **Images**
- The `<img>` element embeds an image into our page in the position it appears via the `src` (source) attribute, which contains a path to our image file
- The `alt` (alternative) attribute allows you to specify descriptive text for users who cannot see the image
-  


### **Marking up Text**

#### *Headings*

- Heading elements allow you to specify that certain parts of your content are headings or subheadings
- HTML contains 6 heading levels, `<h1>-<h6>`
- Headings are used for accessibility and other reasons such as SEO, so create a meaningful sequence of headings
- Anything in HTML between `<!--` and `-->` is an HTML comment, meaning the browser will ignore the comments as it renders the code

#### *Paragraphs*

- `<p>` elements are for containing paragraphs of a text and are used frequently

#### *Lists*

- Unordered lists are where order doesn't matter; they are wrapped in a `<ul>` element
- Ordered lists are where the order of the items does matter; they are wrapped in an `<ol>` element
- Each item inside the list is put inside an `<li>` (list item) element

### **Links**
 - Links are what makes the web the web
 - To add a link, use the element `<a>` ("a" short for "anchor")
 - give the `<a>` element an `href` attribute (href = hypertext reference)

---

## **Semantics**

- Semantics refers to the meaning of a piece of code, such as its purpose or effect
- HTML should be coded to represent the data and not its default presentation styling; CSS is for presentation (how it looks)
- Some benefits of writing semantic markup include helping visually impaired users to navigate a page, making it easier to find blocks of meaningful code, and improving SEO
- There are roughly 100 semantic elements, such as ` <article>, <header>, <footer>, <section>, and <details>`

