# Frontend Mentor - FAQ accordion card solution

This is a solution to the [FAQ accordion card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/faq-accordion-card-XlyjD0Oam). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

This challenge was to build out this FAQ accordion card and get it looking as close to the design as possible.

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See hover states for all interactive elements on the page
- Hide/Show the answer to a question when the question is clicked
- Complete the challenge without using JavaScript

### Screenshot

![](./screenshot.png)

### Links

- Solution URL: [Github](https://github.com/FlexAgrume/fm-faq-accordion-card)
- Live Site URL: [Vercel](https://fm-faq-accordion-card-flexagrume.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

This challenge was an opportunity to discover :

- The HTML Details Element

```html
<details>
    <summary>Details</summary>
    Something small enough to escape casual notice.
</details>
```

- The scrollbar-width property in CSS

```css
.p {
  scrollbar-width: thin;
}
```

- How to custom scrollbars in Webkit (e.g. ::-webkit-scrollbar)

```css
.p::-webkit-scrollbar {
  background: transparent;
  width: 0px;
}
```

- How to select an element based on the presence of a given attribute

```css
.details[open] {
  color:red;
}
```

### Useful resources

- [CSS-Tricks - box-sizing](https://css-tricks.com/box-sizing/)
- [CSS-Tricks - A Complete Guide to CSS Gradients](https://css-tricks.com/a-complete-guide-to-css-gradients/)
- [CSS-Tricks - A Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- [CSS-Tricks - box-shadow](https://css-tricks.com/snippets/css/css-box-shadow/)
- [CSS-Tricks - Custom Scrollbars in Webkit](https://css-tricks.com/custom-scrollbars-in-webkit/)
- [CSS-Tricks - scrollbar-width](https://css-tricks.com/almanac/properties/s/scrollbar-width/)
- [MDN Web Docs - font-size](https://developer.mozilla.org/fr/docs/Web/CSS/font-size)
- [MDN Web Docs - Attribute Selectors](https://developer.mozilla.org/en-US/docs/Web/CSS/Attribute_selectors)
- [BEM — Block Element Modifier](http://getbem.com/)

## Author

- Frontend Mentor - [@flexagrume](https://www.frontendmentor.io/profile/flexagrume)
- Twitter - [@flexagrume](https://www.twitter.com/flexagrume)