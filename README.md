# Frontend Mentor - QR code component solution

This is a solution to the [Stats Preview Card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

Hi! This is my attempt at the Stats preview card component challenge.

Following on from my previous attempt at the 3-column preview card component challenge, I once again went for a mobile-first approach and worked my way up. I also used SASS again and modularised my structure into a main file, and partials for config (variables) and media queries.

### Screenshot

Desktop

![](./screenshots/screenshot_desktop.jpg)

Mobile

![](./screenshots/screenshot_mobile.jpg)

### Links

- Solution URL: [Here!](https://github.com/sheronimo/frontendmentor-statscard)
- Live Site URL: [Here!](https://sheronimo.github.io/frontendmentor-statscard/)

## My process

1. I went for a mobile-first approach, styling the card components as they appeared vertically.
2. Only after fine-tuning the spacing and layout of the components to match the design images as much as possible did I then work on media queries for larger screens. CSS Grid was very useful in this regard, as it would only be a matter of changing `grid-template-columns` and adding an `order` to match the desktop design.
3. Once again, for the styling, I used SASS and attempted to modularise my structure into a main file and partials for: config (variables) and media queries.
4. Another round of fine-tuning spacing and sizing. I would ensure as much accuracy as possible by importing the design images and my screenshots into Photoshop and comparing directly.
5. At the very end, adding and styling the attribution.

### Built with

- Semantic HTML5 markup
- SASS
- Flexbox
- Grid

### What I learned

I mainly learned about how to work with background images inside `div`s, especially when it came to their sizing as the screen size stretched. Quite a lot of fiddling was required to get them to look and change without messing up anything else in the layout.

Additionally, I also learned about how to work with adding a background image and color together and blending them, as it didn't quite look like an overlay.

## Author

- Github - [sheronimo](https://github.com/sheronimo)
- Frontend Mentor - [@sheronimo](https://www.frontendmentor.io/profile/sheronimo)
