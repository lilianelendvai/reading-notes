# 201 Course: Class 9 Reading Notes

## **HTML Forms**

1. Why are forms so important in web development?

- Web forms are a way for the user to interact with the website or application; forms allow for users to enter data

2. When designing a form, what are some key things to keep in mind when it comes to user experience?

- Keep the form smaller and simpler when possible to reduce frustrating (and losing) users
- Prioritize scannability and readability
- Take into consideration the attention of span of users and how it decreases, ex: put optional things at the end of forms

3. List 5 form elements and explain their importance.

- Text box input: `input` is used to capture text such as the user's name, email, address, or other types of text:
-  `<input type="text" name="first_name">`
- Password input: does the same as the text box input but doesn't show the text as the user types:
- `<input type="password" name="password">`
- Text area: a large amount of text can be entered by the user:
- `<textarea name="comment"></textarea>`
- Drop Down: a specific list of options that a user can choose:
```
<select name="weapon">
    <option value="throwing_stars">Throwing Stars</option>
    <option value="sword">Sword</option>
    <option value="staff">Staff</option>
</select>`
```
- Check box: a box the user can click and be checked or unchecked:
- `<input type="checkbox" name="valid_ninja"> Are You a Ninja?`

Question three answers derived from: `https://devdojo.com/guide/html/form-elements`

## **Learn JS**

1. How would you describe events to a non-technical friend?

- Events are actions or occurrences that happen in the system you're programming
- The system tells you about events so your code can react to them
The system produces/fires a signal when an event occurs, and provides a way for action to be automatically taken

2. When using the `addEventListener()` method, what 2 arguments will you need to provide?

- The name of the event we want to register this handler for, and the code that comprises the handler function we want to run in response to it

3. Describe the event object. Why is the target within the event object useful?

- It is a parameter automatically passed to event handlers to provide extra features and information
- The `target` property of the event object is always a reference to the element the event occurred upon

4. What is the difference between event bubbling and event capturing?

- The `capturing` phase is when the browser checks if the element's outer-most ancestor (<html>) has a click event handler registered on it for the capturing phase
- If so, it runs
- Afterwards, it moves on to the next element inside <html> and does the same thing
- This repeats until it reaches the direct parent of the element that was actually clicked
- The `bubbling` phase is the opposite of the capturing phase:
- The browser checks if the direct parent of the clicked element has a click event handler registered on it for the bubbling phase
- If so, it runs
- Afterwards, it moves on to the next immediate ancestor element and does the same thing
This repeats until it reaches the <html> element