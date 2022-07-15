# 201 Course: Class 5 Reading Notes

Why these topics matter: As we learn how to build out websites, it's important to think about how to make it more aesthetically pleasing. We can improve the visual aspect of the website / what the user sees by knowing how to incorporate images of different types and use CSS to affect the look of our content (such as color, font, and size).

## **HTML Media**

1. What is a real world use case for the `alt` attribute being used in a website?

- If the browser doesn't support the image type, then the `alt` attribute will provide the user with a description of the image

2. How can you improve accessibility of images in an HTML document?

- The `alt` attribute increases accessibility: for example, if a user is visually impaired and uses a screen reader to read the web out to them, the alt text will describe the image

3. Provide an example of when the `figure` element would be useful in an HTML document.

- The `<figure>` and `<figurecaption>` elements provide a semantic container for figures, meaning that they link the figure to the caption

- If you have a picture of a person, for example, and want to caption it with their name and contact information, a `figure` element would be used.

4. Describe the difference between a `gif` image and an `svg` image, pretend you are explaining to an elder in your community.

- Both a `gif` and a `svg` can be animated, which means they  can look like a few seconds of a video on loop.
- `svg` is better to use when you care about the resolution of the image (meaning you want it to look crisp when you zoom in or out on it).
`svg` is not ideal when you have a raster format, meaning a photograph or another complex vector illustration. That would make it too large of a file
-`gif` format has been used for decades, so they are very common
`gif` is known for its simplicity and compatibilty and is a common choice for simple images and animations
-`gif` isn't resolution-dependent, meaning that it will look pixelated/grainy when zoomed in on, so it's not ideal for when you need a high-resolution solution

Additional information about GIFs and SVGs came from the following website:

```

https://www.sarasoueidan.com/blog/svg-vs-gif #:~:text=GIF%2C%20just%20like%20other%20image,clear%20on%20any%20screen%20resolution.

```

5. What image type would you use to display a screenshot on your website and why?

- You should use PNG or WebP, as you want to maintain the quality of the image, and those two image types are lossess formats (meaning the image is reduced without quality loss)

## **Learn CSS**

1. Describe the difference between foreground and background colors of an HTML element, pretend you are talking to someone with no technical knowledge.

- Foreground colors are the colors we think of when we have content (referred to as an element). It's the color of whatever we've added, such as what we've written or drawn in.
- Background colors are the ones that go behind the foreground colors. 
- The background color is like the large cloth canvas that goes behind you on your school picture day, and you positioned in front of the colorful canvas are the foreground color.

2. Your friend asks you to give his colorless blog website a touch up. How would you use color to give his blog some character?

- I would work with him to find the right colors for his website, which includes using resources on color theory, picking a base color, fleshing out the palette, and ensuring the color tries to prevent accessibility problems

3. What should you consider when choosing fonts for an HTML document?

- It's important to stick with web safe fonts, which are ones that are generally available across all operating systems
- The 5 generic names for fonts include `serif`, `sans-serif`, `monospace`, `cursive`, and `fantasy`.

4. What do `font-size`, `font-weight`, and `font-style` do to HTML text elements?

- `font-size` determines the size of the font
- `font-weight`sets how bold the text is
- `font-style` turns italic text on or off

5. Describe two ways you could add spacing around the characters displayed in an `h1` element.

- `letter-spacing` and `word-spacing` allow one to set the spacing between words and letters