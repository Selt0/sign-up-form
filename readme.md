# The Odin Project - Sign-up Form

This is a solution to the [Sign-up Form on The Odin Project](https://www.theodinproject.com/lessons/node-path-intermediate-html-and-css-sign-up-form). 

## Overview

A simple sign-up form for an imaginary serice.

### Screenshot

![](./assets/Screen%20Shot%202022-07-01%20at%202.02.07%20PM.png)

### Links

- Live Site URL: [https://selt0.github.io/sign-up-form/](https://selt0.github.io/sign-up-form/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

I downloaded a font and used @font-face to implement it in my project. I was also curious on implementing a phone number field and a quick google search introduced me to "tel"

```html

<div class="form-control">
    <label for="phoneNumber">Phone Number</label>
    <input type="tel" name="phoneNumber" id="phoneNumber" pattern="[0-9]{3}-[0-9]{3}-[0-9]{4}">
</div>

```

```css
@font-face {
    font-family: Norse Bold;
    font-style: bold;
    src: url('/assets/Norse-Bold.otf');
}
```
## Author

- Website - [Michael Martinez](https://michael-martinez.netlify.app/)
- Twitter - [@MMocomochi](https://twitter.com/MMocomochi)
