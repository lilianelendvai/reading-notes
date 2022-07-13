# 201 Course: Class 3 Reading Notes

Why these topics matter: Ordered and unordered lists in HTML help to organize information, where the order of the information being presented either matters or doesn't. Boxes are key to making more complex layouts with CSS and aligning items. And in JavaScript, arrays, operators and expressions, conditionals, and loops all are important parts to storing data, accessing it, and manipulating it to get the desired outcome.

## **Learn HTML**

1. When should you use an `unordered list` in your HTML document?

- It should be used when the order doesn't matter, such as when there isn't a numerical ordering

2. How do you change the `bullet style` of unordered list items?

- The bullet style comes from the associated CSS, using the `list-style-type` property

3. When should you use an `ordered list` vs an `unordered list` in your HTML document?

- An orded list should be used instead of an unordered list when the order does matter, such as in a recipe or with directions

4. Describe two ways you can change the numbers on `list items` provided by an `ordered list`?

- One is by using the CSS `list-style-type` property, and another is to specify a `type` attribute on an enclosed `<li>` element

## **Learn CSS**

1. Describe the CSS properties of `margin` and `padding` as characters in a story. What is their role in a story titled: “The Box Model”?

- Content and Border, two top models at The Box Agency, have always been the stars of the show. They're visible to international audiences who eagerly tune in to see what these two icons are displaying next: maybe Content is setting a new trend for color and style, or Border is embracing a thicker and seductive silhouette. Border and Content, the faces of The Box... but what would they be without their assistants, Padding and Margin? Padding works to keep Content's and Border's stories separate enough so that they have room to shine, although sometimes, Padding helps them to collaborate and put on events where the celebrities stand side by side. And Margin's in charge of crowd control, keeping them away from all the other agencies that are trying to encroach on The Box and steal the spotlight from Border and Content. Margin and Padding don't get much recognition, but they knew that, without them, The Box wouldn't be what it is today. They're the real MVPS for protecting Content's and Border's boundaries, which has let their careers on the screen flourish.

2. List and describe the four parts of an HTML elements box as referred to by the `box model`.

- Content box: The area where content is displayed
- Padding box: It sits around the content as white space
- Border box:It wraps the content and the padding
- Margin box: The outermost layer that goes around the border, padding, and content. It's whitespace between the box and other elements.

## **Learn JS**

### **JavaScript Basics**

1. What `data types` can you store inside of an `Array`?

- An array may contain data of any type, such as strings, numbers, booleans, objects, functions, and other arrays

2. Is the `people` array a valid JavaScript array? If so, how can I access the values stored? If not, why?

```
 const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];

```

- It is a valid array called a multidimensional arrage (an array inside an array). Chaining two sets of square brackets together allows one to access an item inside the array

3. List five shorthand operators for assignment in JavaScript and describe what they do.

- Assignment Operators: Assigns a value with `=`
- Arithmetic Operators: Takes numerical values as their operands and returns a single numberical value... `++`, `--`, and `**` are examples
- Comparison Operators: Compares its operands and returns a logical value depending on if its true... `==`, `!=`, and `===` are examples
- String Operators: The concatenation operator `+` concatenates 2 strings together, returning a string that is their union
- Conditional (ternary) Operators: The only JavaScript operator that takes three operands, and the operator can have one of two values based on a condition

4. Read the code below and evaluate the last `expression` and explain what the result would be and why.

```

let a = 10;
 let b = 'dog';
 let c = false;

 // evaluate this
 (a + c) + b;

```

- The result would be `10dog`, as false = 0, so 10 + 0 + dog = 10dog

5. Describe a real world example of when a conditional statement should be used in a JavaScript program.

- A real world example could be asking the user if they're sleepy. If true, they should go to sleep. If false, they can binge watch a show and feel guilty later. This example would include an `if...else` statement, which is the most common type of conditional statement

6. Give an example of when a `Loop` is useful in JavaScript.

- A loop would be useful for a repetitive task, such as running a basic calculation, like adding a series of numbers