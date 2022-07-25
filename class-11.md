# 201 Course: Class 6 Reading Notes

## **Video and Audio Content**

1. Explain how the ability to use video and audio on the web has evolved since the early 2000s.

- The early 2000s were the first time we had the badwidth fast enough to support any kind of video. Native web technologies then didn't have the ability to embed video and audio on the Web, so proprietary (or plug-in based) technologies became popular for handling the content. This led to issues with HTML/CSS features, security, and accessibility.
- A few years later, the HTML5 specification had added featues including the `<audio>` and `<video>` elements and JavaScript APIs for controlling them.

2. Describe the use of the `src` and `controls` attributes in the `<video>` element.

- `src` attribute contains a path to the video one wants to embed
- `controls` is what control the video and audio playback; at minimum, the interface must have the abiltiy to start and stop the media and adjust the volume

3. Why is it important to have fallback content inside the `<video>` element?

- It will be displayed if the browser accessing the page doesn't support the `<video>` element
- This allows the user to at least access it regardless of what browser they're using

4. Write a very short story where `<audio>` and `<video>` are characters.

- `<audio>` and `<video>` become 80s icons (please swap `audio` for `radio`):

``` 
https://www.youtube.com/watch?v=W8r-tXRLazs
```

## **A Complete Guide To Grid**

1. How does Grid layout differ from Flex?

- Grid layout is two dimensional, whereas Flex is one dimensional

2. Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences.

- Grid Container: It's the parent of all the grid items; the element on which `display: grid` is applied

- Grid Item: The children/direct descendants of the grid container

- Grid Line: Vertical or horizontal dividing lines that make up the structure of the grid

## **Responsive Images**

1. Besides making a site visually appealing across different screen sizes, why should developers make images responsive?

- Resolution switching problem: there is no need to embed such large images on the page on a mobile screen, and small images look grainy when displayed larger than their original size

2. Define the following `<img>` attributes `srcset` and `sizes`. Write an example of how they are used.

- `srcset` defines the set of images allowed for the browser to choose between and the size of each image 

- `sizes` defines a set of media conditions and indicates what image size would be best for certain media conditions are met

3. How is `srcset` more helpful for responsive images than CSS or JavaScript?

- The browser starts to load the page in a specific order. It downloads (preloads) any images before the main parser has started to load and interpret the page's CSS and JavaScript. This reduces page load times but makes responsive images a challenge: you couldn't load the <img> element then detect the viewport wideth with JavaScript and then dynamically change the source image to a smaller one if desired. `srcset` is the solution to this problem.