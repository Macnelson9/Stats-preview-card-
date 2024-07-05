# Stats-preview-card-
This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

Phewww! I had to go back and relearn alot of things on HTML and CSS like semantic HTML, centering things using margin: 0 auto; using percentages instead of fixed values to improve responsiveness and more about responsive designs. Glad that I got to pull it off in the end.

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

## My process

I started off by building the desktop version before mobile in order to ensure I get as close to the design as possible.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

I learnt how to add an overlay to an image.

To see how you can do same, see code snippets below:

```html
<div class="image-container">
  <img src="./images/image-header-mobile.jpg" alt="mobile-image" />
  <div class="overlay"></div>
</div>
```

```css
.image-container {
  position: relative;
  width: 50%;
}

.image-container .overlay {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-color: #aa5cdb91;
  filter: contrast(150%);
  filter: saturate(100%);
}
```

## Author

- Frontend Mentor - [@macnelson9](https://www.frontendmentor.io/profile/macnelson9)
- X - [@macnelson92](https://www.x.com/macnelson92)
