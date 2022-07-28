# 201 Course: Class 14a Reading Notes

## **CSS Transforms**

1. What does a CSS transform allow the developer to do to an element?

- The  transform CSS property allows the developer to rotate, scale, skew, or translate an element
- Answer for number one originates from:
```
https://developer.mozilla.org/en-US/docs/Web/CSS/transform
```

2. Provide an example of a transform and how you could see that being used on a website.

- The transform property accepts a handful of different values, one being the rotate value
- The rotate value allows you to rotate an object between 0 to 360 degrees.
- A positive value will rotate the element clockwise, and a negative value will rotate it counterclockwise
- Example code taken from: 
```
https://learn.shayhowe.com/advanced-html-css/css-transforms/
```

HTML:
```
<figure class="box-1">Box 1</figure>
<figure class="box-2">Box 2</figure>
```

CSS:
```
.box-1 {
  transform: rotate(20deg);
}
.box-2 {
  transform: rotate(-55deg);
}
```

## **CSS Transitions & Animations**

1. What does a CSS transition allow the developer to do to an element?

- CSS transitions allow the developer to alter the appearance and behavior of an element whenever a state change occurs (this could include hover, targeted, active, or focused on)

2. How does a CSS animation differ from a CSS transition?

- Animation allows the developer to alter the appearance and behavior of an element in multiple keyframes
- Differs from transitions, as transitions provide a change from one state to another, whereas animations can set multiple points of transition upon different keyframes

## **8 Simple CSS3 transitions that will wow your users**

1. What are some benefits to using CSS transitions on websites?

- It will excite users, increase engagement, and increase conversions (a measurable way to demonstrate the value of the website for the business's top line)

2. How this topic fit in with your long-term goals?

- It's important, when I design webpages in the future, to think about the user's experience and how to capture their attention, especially in a highly competitive and overly saturated market 
- Transitions bring movement to the page, which will better engage the user and keep them paying more attention to the content