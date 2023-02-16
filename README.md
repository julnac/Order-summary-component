# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)

## Overview

### The challenge

Users should be able to:

- See hover states for interactive elements

### Screenshot

![](./images/screenshot.png)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

This project was a grate start form me. I've learned about flexbox, shadow casting in css and much more. 

Here are some examples of code:

```html
  <div class="plan">
    <div class="current_plan">
      <div class="icon"></div>
      <div class="type">
        <h2>Annual Plan</h2>
        <p>$59.99/year</p>
      </div>
    </div>
    <a href="#">Change</a>
  </div>
```
```css
.plan {
    background-color: var(--very_pale_blue);
    border-radius: 10px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 15px;
}
```
