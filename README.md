# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![Screenshot](./design/desktop-preview.jpg)

### Links

- Solution URL: [solution URL](https://github.com/chanwinharold/product-preview-card-component-main/)
- Live Site URL: [live site URL](https://product-preview-card-component-main-two-gamma.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

```css
.proud-of-this-css {
  @media screen and (min-width: 0px) and (max-width: 768px) {
    main {
      max-width: 375px;
      flex-direction: column;
    }
  }

  @media screen and (min-width: 768px) and (max-width: 1440px) {
    main {
      width: 75%;
      height: auto;
      flex-direction: row;
    }
    main img {
      border-radius: 10px 0 0 10px;
    }
  }
}
```
## Author

- Frontend Mentor - [@chanwinharold](https://www.frontendmentor.io/profile/chanwinharold)
