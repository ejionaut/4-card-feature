# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)


## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![4 panel scr](https://github.com/ejionaut/4-card-feature/blob/main/images/4%20panel.png)

### Links

- Solution URL: [FrontEnd Mentor](https://www.frontendmentor.io/solutions/four-card-feature-using-grid-and-flex-TWBH-R1-cK)
- Live Site URL: [Netlify](https://radiant-lamington-52b76e.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

To properly align the content in mobile view instead of using vh appearently its better to use percentages.
For EX: 

```css
 body {
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
  }

 @media (max-width: 50em) {
    body {
      height: 100%;
    }
}
```

### Continued development

I'm currently used to how CSS and HTML works but I am learning better practices to further refine my skills then move on to javascript.

## Author

- Frontend Mentor - [@ejionaut](https://www.frontendmentor.io/profile/ejionaut)

