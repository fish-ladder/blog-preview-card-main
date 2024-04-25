# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page


### Links

- Solution URL: [https://github.com/fish-ladder/blog-preview-card-main]
- Live Site URL: [https://fish-ladder.github.io/blog-preview-card-main/]

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- Media queries

### What I learned

I learned that the Figma files are very usefuly for determining the exact dimensions of elements.

I felt more comfortable using Flexbox for basic layout tasks.

I did run into an issue where using auto margins on the main card (with the body set to display: flex) pushed the attribution section too far down on the screen. I fixed this by setting the attribution to use auto margins as well. 

After laying out and styling everything I noticed that the font-size in the desktop version was larger. To fix this, I switched from px to em units for the font-size of the main text elements so that I could use a media query to increase the parent font-size and therefore also the children font-size.

### Continued development

I would like to get more comfortable with media queries and also container queries.

I need to establish good workflow for font-sizes. I think I will try setting the basic font-sizes in :root as custom properties in rem units so that I can easily scale them as needed. (thanks to a Kevin Powell youtube video for this idea)

### Useful resources

- [https://www.sitepoint.com/understanding-and-using-rem-units-in-css/] This was great for helping me understand rem (and also em).

## Author

- Frontend Mentor - [@yfish-ladder](https://www.frontendmentor.io/profile/fish-ladder)

## Acknowledgments

- Kevin Powell and his videos (again)
- freeCodeCamp for getting me started
- Becca for her very old MacBook Air
- Kubuntu for working well on a very old MacBook Air
- VS Code for being awesome and free.