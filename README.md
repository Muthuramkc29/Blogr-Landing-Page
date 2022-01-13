# Frontend Mentor - Blogr landing page solution

This is a solution to the [Blogr landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blogr-landing-page-EX2RLAApP). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Links

- Live Site URL: https://blogr-landing-page-junior.netlify.app/

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- Bootstrap5

### What I learned

Major Learnings - To position and to make an (position: absolute) element responsive.

```
```css

.mob-div {
    margin-top: 0;
    border: 1px solid white;
}

.empty {
    // border: 1px solid magenta;
    width: 300px;
    height: 10rem;
    position: relative;
    margin-left: auto;
    margin-right: auto;


    &__img {
        position: absolute;
        z-index: 1;
        top: 5%;
        left: 0;
        height: 300px;
    }
}

```
```js
const proudOfThisFunc = () => {
  console.log('🎉')
}
```

### Continued development

Concepts - to be comfortable - Css Grid properties