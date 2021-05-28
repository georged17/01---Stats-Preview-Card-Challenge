# Frontend Mentor - Stats preview card component solution

This is my solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). 

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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Media queries


### What I learned

I started this project after I learned to work with Figma, and thought it would be a good idea to recreate this design. I did that relatively fast, one thing led to another, and I started coding it as well!

I think I did a pretty good job. There are two things I'm not sure of though. 

1) If I made the images responsive the right way
2) Did I use media queries the right way semantically speaking?
3) Why won't the card stop growing in size after the last media query.

```css
.Mobile-Image{
    width: 100%;
    height: 20rem;
    background-image: url(./image-header-mobile.jpg);
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center center;
}

.Mobile-Overlay{
    width: 100%;
    height: 20rem;
    background-color: hsl(277, 64%, 61%);
    opacity: 0.4;
}
```


## Author

- Frontend Mentor - [@georged17](https://www.frontendmentor.io/profile/georged17)


## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.

**Note: Delete this note and edit this section's content as necessary. If you completed this challenge by yourself, feel free to delete this section entirely.**
