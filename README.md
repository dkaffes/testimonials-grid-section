# Frontend Mentor - Testimonials grid section solution

This is a solution from Dimitris Kaffes to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7).

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

## Overview

Mobile first design approach was followed for this challenge.

A modern CSS reset (by Andy Bell) was implemented.

A good Grid practice takes place on this challenge. Flexbox adds to the overall layout structure.

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![Screenshot of the solution](./images/screenshot-solution.jpg)

### Links

- Solution URL: [testimonials-grid-section solution on Github](https://github.com/dkaffes/testimonials-grid-section)
- Live Site URL: [testimonials-grid-section live site](https://dkaffes.github.io/testimonials-grid-section/)

## My process

A mobile first design approach was followed, with the HTML structure taking into account the desktop layout as well.

Custom properties were used for the colors and font-weights.

Grid layout was used for the `.cards-container` and Flexbox for the `.card` and the `.profile-container`.

In my first solution approach I used `grid-template-areas` but after some research in the Discord #help channel of the FrontEndMentor community, I finally used `grid-auto-flow: dense;` for the desktop Grid version.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

The `grid-auto-flow: dense;` property was something new to me and also fun to work with.

### Continued development

Further improve my knowledge on the Grid related properties.

### Useful resources

- [MDN grid-auto-flow](https://developer.mozilla.org/en-US/docs/Web/CSS/grid-auto-flow) - This helped me understand how to use the property so as to nail the design.

## Author

- Frontend Mentor - [@dkaffes](https://www.frontendmentor.io/profile/dkaffes)

## Acknowledgments

Thanks to [Alex](https://www.frontendmentor.io/profile/AlexKMarshall) and his useful comments on the #help Discord channel, I implemented `grid-auto-flow: dense;` for this challenge.
