# Frontend Mentor - Social proof section solution

This is a solution to the [Social proof section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-proof-section-6e0qTv_bA). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the section depending on their device's screen size

### Screenshot

![](./screenshots/mobile.png)
![](./screenshots/desktop.png)

### Links

- Solution URL: [https://www.frontendmentor.io/solutions/social-proof-section-built-with-flexbox-grid-and-sass-v6kZXG56h](https://www.frontendmentor.io/solutions/social-proof-section-built-with-flexbox-grid-and-sass-v6kZXG56h)
- Live Site URL: [https://fem-social-proof-section-xi.vercel.app/](https://fem-social-proof-section-xi.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- Flexbox
- CSS Grid
- Mobile-first workflow
- SASS

### What I learned

With this project I was keen to reinforce my new knowledge of CSS Grid. I have to say I am really enjoying getting to grips with it and I really can see what people mean when they've been saying how powerful it is!
One new trick I learnt with this project was forcing all the grid cells in a row in my grid layout to all take the same height - from the design, I felt that the review cards all needed to stay the same height throughout (rather than changing with their content and sometimes ending up being slightly different heights). I found a great solution on Stack Overflow that helped me out (find the link to the Stack Overflow solution in my useful resources section below). The solution was to add: grid-auto-rows: 1fr; which would force all the grid cells in that row track to take the max-content of the tallest item (the max-content becomes one fraction, therefore we can use 1fr).

```css
.reviews {
  display: grid;
  grid-auto-rows: 1fr;
  gap: 1.23em;
}
```

### Continued development

I don't feel like I am using SASS effectively at the moment. Possibly because I have so far just been using it on smaller projects, but I would like to start using it more effectively in the future and make use of mixins and functions etc.

Other than that, I need to be building projects more regularly to practice everything I am learning.

### Useful resources

- [Stack Overflow solution](https://stackoverflow.com/questions/44488357/equal-height-rows-in-css-grid-layout) - This is the Stack Overflow solution that helped me force all the grid cells in a row to be the same height.

## Author

- Frontend Mentor - [@claire-ca](https://www.frontendmentor.io/profile/claire-ca)
