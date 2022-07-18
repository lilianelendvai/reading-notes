# 201 Course: Class 6 Reading Notes

Why these topics matter: 

## **JavaScript Object Basics**

1. How would you describe an object to a non-technical friend you grew up with?

- It's a collection of information, including related data and/or functionality
- It can consist of several variables and functions

2. What are some advantages to creating object literals?

- It's when you've written out the object contents as you've come to create it
- This differes from objects instantiated from classes
- Object literals are better when you want to transfer a series of structures, related data items, as it's more efficient then to send a single object versus several items indivudally
- It's also easier to work with than an array in cases where you want to identify individual items by name

3. How do objects differ from arrays?

- Arrays store data in an ordered collection where the data can be accessed with an index
- Arrays are mutable, and data can be modified at any index
- Arrays are useful for when you have to store data in a particular order; otherwise, you can use an object

4. Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.

- It's an alternative way to accessing object properties
- Although dot notation is generally preferred, as it's more succinct and easier to read, there are some cases that necessitate brackets, such as when an object property name is defined at runtime: you can pass the name as a variable inside the brackets

5. Evaluate the code below. What does the term `this` refer to and what is the advantage to using `this`?

-  `this` enables you to use the same method definition for every object you create

- `this` is the keyword referring to the current object the code is being written inside
- In the example,  `this` referring to members of the object, with the object being `dog`


## **Introduction to the DOM**

1. What is the DOM?

- The Document Object Model (DOM) is a program interface for web documents which represents the page so that programs can make changes to the document, such as structure, style, and content
- DOM represents the document as nodes and objects so that programming languages can interact with the array

2. Briefly describe the relationship between the DOM and JavaScript.

- The code can be written in JavaScript but use DOM to access the document and its elements
- DOM isn't a programming language
- The document as a whole can be accessed and manipulated using the DOM and a scripting language like JavaScript
- DOM is a Web API used to build websites