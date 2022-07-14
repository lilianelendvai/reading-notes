# 201 Course: Class 4 Reading Notes

Why these topics matter: Linking pages is an essential part of the web, as the main purpose is to share and access information, which is what links allow for. For CSS, it's important to understand how content is positioned and how to alter the layout. With functions, we are starting to see the different ways they are structured and what their purpose is. And at Code Fellows, pair programming is a method used to increase collaboration, improve efficiency, prepare graduates for the work environment, and other beneficial outcomes.

## **Learn HTML**

1. To create a basic link, we wrap text or other content inside what element?

- We use the `<a>` element and `href` attribute (known as the Hypertext Reference, or target)

2. The `href` attribute contains what information?

- It contains the web address

3. What are some ways we can ensure links on our pages are accessible to all readers?

- Include keywords in the link text to describe what is being linked, which will increase accessibility with screen readers, search engines, and visual readers

## **CSS Layout**

1. What is meant by “normal flow”?

- Normal flow is how the webpage elements lay out if there are no changes to their layout

2. What are a few differences between `block-level` and `inline` elements?

- The content of `block-level` elements fills the available inline space of the parent element. It grows along the block dimension to accommodate its content, whereas inline elements are just the size of their content. You can't set the width or height of inline elements.

- Block-level elements are laid out in the black-flow direction based on the parent's writing mode. Each element will appear on a new line below the last and will be separated by the specified margin. Inline elements all sit along with any adjacent text content so long as there is space inside the parent block level element (overflowing content will move to a new line below).

3. ___ positioning is the default for every html element.

- Static

4. Name a few advantages to using absolute positioning on an element.

- An absolute positioned element sits on its own layer separate from everything else, which means there can be isolated UI features that won't interfere with the layout of other elements on the page

- The position of the element changes as `top`, `bottom`, `left`, and `right` specify the distance the element should be from each of the containing element's sides, which helps with resizing

5. What is a key difference between fixed positioning and absolute positioning?

- Fixed positioning differs in that it usually fixes an element in place relative to the visible portion of the viewpoint, whereas absolute positioning fixes an element in place relative to its nearest positioned ancestor.

## **Learn JS**

1. Describe the difference between a function declaration and a function invocation.

- Function declaration introduced an identifier to designate a function, and it can specify the types of the function parameters, known as the prototype 

- To execute a function, we need a function invocation, also known as a function call

- Definitions of function invocation and function declaration are from the following websites:

```

https://en.cppreference.com/w/c/language/function_declaration#:~:text=A%20function%20declaration%20introduces%20an,as%20well%20as%20file%20scope.

https://runestone.academy/ns/books/published/fopp/Functions/FunctionInvocation.html#:~:text=Defining%20a%20new%20function%20does,known%20as%20a%20function%20invocation.

```

2. What is the difference between a parameter and an argument?

- Parameters are valued that are included inside the function parentheses, which need to be specified when some functions are being invoked

- Parameters can sometimes be called arguments, properties, or attibutes

- Function parameters are the names listed in the function's definition

- Function arguments are the real values passed to the function

- Parameters are initialized to the values of the arguments supplied

- A parameter is a named variable passed into a function; an argument is a value passed as input to a function

Comparison of parameters and arguments come from the following website:

```

https://developer.mozilla.org/en-US/docs/Glossary/Parameter

```

## **Miscellaneous**

1. Pick 2 benefits to pair programming and reflect on how these benefits could help you on your coding journey.

- Greater efficiency: Pair programming means that two people will be looking at the same code but with different perspectives: one as the Driver, who is the one typing, and one as the Navigator, who is using words to guide the Driver. This increases the quality of the code and makes it ultimately more efficient, as you can come up with solutions together and reduce the amount of future troubleshooting and debugging. Having another person's perspective will help me on my coding journey, as I will be learning by taking turns as the Driver and the Navigator, and for having the person I'm partnering with do the same.

- Engaged collaboration: Working as a pair means that there's a level of accountability that isn't in place when it's a solo endeavor. You have someone else there who is reliant on you doing your part, and vice versa. This will help me on my coding journey, as it will help me focus and feel a greater sense of responsibility for doing my job. Also, having someone working alongside you means that you can tap into their knowledge and receive their help. 