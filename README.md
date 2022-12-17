# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![screenshot](threeColumnScreenshot.jpg)

### Links

- Solution URL: [frontendmentor.io/solutions/3column-preview-card-component-mRZ55chx53](https://www.frontendmentor.io/solutions/3column-preview-card-component-mRZ55chx53)
- Live Site URL: [vejtheguy.github.io/3-column-preview-card-component-main](https://vejtheguy.github.io/3-column-preview-card-component-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

This was my first project incorporating 'clamp' to help keep the entire page fully responsive without using any '@media queries'.  I have also started to add hidden 'screen reader only' text to help explain elements on the page.

```html
<h1 class="sr-only">Three column preview card</h1>
<button>Learn More<span class="sr-only">about sedans</span></button>
```

```css
.component-text {
    margin-bottom: clamp(25px, 5vw, 70px);
}
```
### Useful resources

- [Flexbox Holy Albatross](https://heydonworks.com/article/the-flexbox-holy-albatross/) - Super cool thing you can do with flex-basis to control the flexbox from row to column.

## Author

- CodePen - [@vejtheguy](https://codepen.io/vejtheguy)
- Frontend Mentor - [@vejtheguy](https://www.frontendmentor.io/profile/vejtheguy)
- Twitter - [@aworthlessgamer](https://twitter.com/aworthlessgamer)

## Acknowledgments

Thank you Vanza Setia for the tip about flexbox! [@vanzasetia](https://www.frontendmentor.io/profile/vanzasetia)