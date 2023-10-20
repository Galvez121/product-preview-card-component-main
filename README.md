# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

After trying to center the div using justify-content: center; and align-content: center; properties I have not been able to center all the content in the middle of the website. As a result, I used margin auto to center the container.

I had troubles using the img and border-radious, but I found how to fix it with the next properties:

```css
img {
  width: 100%;
  border-top-left-radius: inherit;
  border-bottom-left-radius: inherit;
}
```

After finishing the desktop design, I have decided to make this design responsive. In that way, it would be possible to use it on any phone.

I was not sure how to change the pictures when I used responsive. I did it with display:none, but I did not think that is the best way to do it. That is my solution for now.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

I learned how to add specific fonts to my website.

I learned how to use the pseudo-class :nth-of-type. In addition, I learned how to use responsive.

-

### Continued development

I need to keep practicing flex-box.
I continue to struggle with the position of the elements.

## Author

- Instagram - [@juan_gszs](https://www.instagram.com/juan_gszs/)
- Frontend Mentor - [@Galvez121](https://www.frontendmentor.io/profile/Galvez121)
- Github - [@Galvez121](https://github.com/Galvez121)w.twitter.com/yourusername)

\
