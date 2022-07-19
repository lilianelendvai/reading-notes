# 201 Course: Class 7 Reading Notes

Why these topics matter: Domain modeling is important, as it becomes a way for stakeholders of various backgrounds to form a common vocabulary to address a specific coding problem. HTML tables make it easier to display matrixes of data, similarly to excel. Constructors create a consistent structure of objects. An object inheriting properties from another object reduces issues around data and logic duplication.

## **Domain Modeling**

1. Explain why we need domain modeling.

- It can verify and validate the understanding of a specific problem among stakeholders from a variety of backgrounds
- It defines a common vocabulary that can be used for both technical and business teams

## **HTML Table Basics**

1. Why should tables not be used for page layouts?

- Table layouts are generally more complex with their markup structure, making the code harder to write, maintain, and bug

2. List and describe 3 different semantic HTML elements used in an HTML <table>.

- `<th>` are used to define rows used as headers in a table
- `<tr>` is a row in the table which includes a series of cells
- `<td>` is an actual cell in the table

## **Introducing Constructors**

1. What is a constructor and what are some advantages to using it?

- A constructor is a function called using the keyword `new`
- The constructor will create a new object; bind `this` to the new object, allowing you to refer to `this` in your constructor code; run the code in the constructor; and return a new object
- It reduces the chance of making mistakes between similar objects being created

2. How does the term `this` differ when used in an object literal versus when used in a constructor?

- In an object literal, `this` holds the actual reference to its own object
- In a constructor, `this` will reference objects that are being created by the constructor

## **Introduction to the DOM**

1. Explain prototypes and inheritance via an analogy from your previous work experience.

- In my role as a recruiter, it's important to keep track of data regarding a candidate, such as what job they interviewed for, how far along they got in the interview process, a copy of their resume, and other pieces of data tied to them. If we had a candidate for one search, and they also became a candidate for another, we make sure to take the candidate information from the first search and copy it to the second. So the second search will have the candidate information, and we can then modify it as we'd like within that specific project. This is similar to the idea of prototypes and inheritance in JavaScript: the candidate in the original search is the prototype, and the candidate in the new search will have inherited properties from the candidate information in the first search.