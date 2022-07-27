# 201 Course: Class 13 Reading Notes

## **Local Storage and How To Use It On Websites**

1. Why would a developer use local storage for a web application?

- A major problem with using HTTP as the main transport layre of the web is that it's stateless, meaning that when an application is used and then closed, its state is reset the next time it's opened

- But if you close an application on your desktop and re-open it, its most recent state is restored

- This explains why developers need to store the state of the interface somewhere; it's normally done server-side with checking the user name to know which state to revert to

- If you don't want to force people to sign up, local storage is useful: there's be a key on the user's computer that is read when the user returns

2. What information should not be stored in local storage?

- sensitive information (it has no form of data protection and can be accessed by any code on the web page)
- above 5MB
Response to question 2 based upon the article: 
```
https://blog.logrocket.com/localstorage-javascript-complete-guide/
```

3. Local storage can store what type of data? How would you convert it to that type before storing?

- You can only store strings in the different keys
- Can be worked around by using the native `JSON.stringify()` and `JSON.parse()` methods