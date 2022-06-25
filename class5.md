# Class 5 Reading Notes

## **What is CSS?**

### **What CSS is for**

- Cascading Style Sheets (CSS) is a language for specifying how documents are presented to users, such as their styling and lay out
- A document is usually a text file structured using a markup language; HTML is the most common markup language, but there are others such as SVG or XML
- Presenting a document to a user means converting it into a form usable by your audience; browsers are designed to present documents visually
- A browser is sometimes called a user agent

### **CSS Syntax**

- CSS is a rule-based language, meaning that rules are defined by specifying groups of styles that should be applies to particular elements or groups of elements on your web page
- Inside a set of curly braces `{}`, there will be one or more declarations, which take the form of property and value pairs
- CSS properties have different allowable values, and a CSS stylesheet will contain main rules written one after the other

### **CSS Modules**

- Since styling using CSS is extensive, the language is broken down into modules
- It's helpful if you have awareness about properties and where they're likely to be found among other similar things, and therefore, probably in the same specification

### **CSS Specifications**

- All web standard technologies are defined in giant documents called specifications/"specs" which are published by standards organizations
- Specifications define precisely how the technologies are supposed to behave
- The CSS Working Group develop and specify new CSS features

### **Browser support information**

- The code has been written to turn the instruction in our CSS file into something that can be output to the screen
- The browser support status is shown on every MDN CSS property page in a table named "Browser compatibility"

---

## **How to Add CSS**

There are three ways of inserting a style sheet: External CSS, Internal CSS, and Inline CSS
1. External CSS: with an external style sheet, you can change the look of an entire website by changing one file; each HTML must include a reference to the external style sheet file inside the <link> element, inside the head section; an external style sheet must be saved with a `.css` extension
2. Internal CSS: internal style sheet may be used if a single HTML page has a unique style; the internal style is defined inside the <style> element inside the head section
3. Inline CSS: inline style may be used to apply a unique style for a single element; to use inline styles, add the style attribute to the relevant element

- With multple style sheets, if some properties have been defined for the same selector (element) in different style sheets, the value from the last read style sheet will be used
If there is more than one style specified for an HTML element, all the styles in a page will "cascade" into a new "virtual" style sheet by the following rules, where number one has the highest priority

---

## **CSS Color**

Property Values:
- Color: specifies the text color
- Initial: sets this property to its default value
- Inherit: inherits this property from its parent element
