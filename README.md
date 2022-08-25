# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
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

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- BEM

### What I learned

The big takeaway for me in this exercise is how can elements be grouped together in order to achieve a certain layout. In this project, the central cards remain on top of each other while the first and last cards are aligned in the center.

It took me a while to figure out that if I grouped the central cards together, they won't be affected by the flexbox when I set it on larger screens and since they are already block in the mobile design, there is no need to change it.

Another is that I learned more about the borders even though I didn't use it to the final product.

I found out that using border on only side also affects whats on the other sides as well. My inital plan was to use borders to the accent colors in the cards but the ends ended up unlike what was on the design.

I ended up using a div positioned on top of the card and used the overflow to hide the excess div.

### Continued development

I had fun and learned a lot in applying flexbox in my projects. It is an easy way to layout. I plan to practive more on different applications of flexbox or grid in the future projects.

## Author

- Frontend Mentor - [@jayrnoel](https://www.frontendmentor.io/profile/jayrnoel)
