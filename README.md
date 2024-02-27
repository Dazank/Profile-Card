# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)



## Overview

### The challenge

- Build out the project to the designs provided

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

I learned how to use multiple background images with CSS, how to position said images with the image-position property and about the alpha value for opacity. I also improved my positioning a bit.

I'm particularly proud of how this CSS created a seamless background:

```css
body{background: url(./images/bg-pattern-top.svg), url(./images/bg-pattern-bottom.svg), hsl(185, 75%, 39%); 
background-repeat: no-repeat, no-repeat;
background-position:  -400px -500px, 750px 200px;}
```

### Useful resources

- [Example resource 1](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_backgrounds_and_borders/Using_multiple_backgrounds) - This helped me understand the concept of multiple backgrounds and how to apply them.
