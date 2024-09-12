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

### Links

- Solution URL: [my solution](https://your-solution-url.com)
- Live Site URL: [Live site](https://ratsagi.github.io/productPreviewCard-fem/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned
I learned how to use media-query and mobile-first workflow. 
```css
@media(min-width:23.43em){
  .product{
        display:flex;
        background-color:var(--cream);
        max-width: 34rem;
        
    }
}
```
Also find out how to limit the size of text to place it correctly by using max-inline-size:
```css 
.product__title{
      max-inline-size: 10ch;
    }
```
### Continued development

I will continue to explore responsive web design and apply them in future projects. 


## Author
- Frontend Mentor - [@ratsagi](https://www.frontendmentor.io/profile/ratsagi)
