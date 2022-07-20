# 201 Course: Class 8 Reading Notes

Why these topics matter: Flexbox allows us to design the layout of groups of items in one dimension. It's a layout method for arranging rows or columns, and flexbox makes layout tasks much easier in comparison to tools such as floats and positioning.

## **Learn CSS - Flexbox**

1. Flexbox is designed for one-dimensional content. Explain what this means.

- It means that layouts are processed one dimension at a time, such as a row or a column

2. Explain the difference between the main axis and cross axis.

- A main axis is the one set by your  `flex-direction` property: if it's `row`, then your main axis is along the row, and if it's `column`, your main axis is along the column
- Cross axis runs in the other direction of the main axis (they're perpendicular)

3. How can using certain properties of flexbox negatively impact accessibility?

- Properties that reorder the visual display separately from how things are ordered in the HTML document can negatively impact accessibility
- `row reverse` and `column-reverse` are examples where reordering happens for the visual order but not the logal order; the logical order is the one a screen reader will read out

## **CSS Layout - Flexbox**

1. What are some advantages of using flexbox over float?

- Vertically centering a block of content inside its parent.
- Making all the children of a container take up an equal amount of the available width/height, regardless of how much width/height is available.
- Making all columns in a multiple-column layout adopt the same height even if they contain a different amount of content.
- Answers above taken from:
```

https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox#why_flexbox

```

2. How does this topic connect with your long term goals?

- As we learn how to build web pages, it's important to have better control over where the content is located and how it is manipulated. Flexbox is available in most new browsers and more easily than floats or positioning allows for certain outcomes. Flexbox is a more recent tool that is increasing in popularity, so it's important to learn