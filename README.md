# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)


## Overview

### The challenge

Users should be able to:

- See hover states for interactive elements

### Screenshot

![](./![alt text](image.png))


### Links

- Solution URL: (https://github.com/korcakSEA/order-summary-component-main.git)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

MY major learnings while working through this project is that min-height trick is a classic lifesaver for responsive layouts.

You see the code snippets below:

```css
body{
    font-family: var(--primary-font);
    font-weight: 500;
    min-height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: var(--primary-blue-tint);
    background-image: url("./images/pattern-background-mobile.svg");
    background-repeat: no-repeat;
    background-position: left top;
    background-size: contain;
}
```


### Useful resources

- [Example resource 1](https://www.joshwcomeau.com/css/center-a-div/) - This site helped me to understand centering divs. with the animation you can easily understand the approaches

## Author

- Frontend Mentor - [@korcakSEA](https://www.frontendmentor.io/profile/korcakSEA)
