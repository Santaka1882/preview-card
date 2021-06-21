# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

### Screenshot

![Solution](./design/preview_card_1920.png)

### Links

- Live Site URL: [https://santaka1882.github.io/preview-card/](https://santaka1882.github.io/preview-card/)

## My process

### Built with

- Semantic HTML5 markup
- Vanilla CSS
- Flexbox
- Mobile-first workflow

### What I learned

The thing that tooke me more time and effort to do was the image and the purple color on it. The solution was very simple. I use this code for all the section:

```css
.image-container .image {
  width: 100%;
  min-height: 247px;
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
  background-image: linear-gradient(
    hsla(277, 79%, 38%, 0.5), 
    hsl(277, 79%, 38%, 0.5)
  ), url("../images/image-header-mobile.jpg");
}
```
The height stays at 0 no matter what, so i use the propety max-height to declare it. For the color i use the image as the background of the container an use a linear gradient which is not a gradient but it works as expected.

### Useful resources

- [Google](https://www.google.com/) - This is the MVP for problem solving

## Author

- Frontend Mentor - [@https://www.frontendmentor.io/profile/Santaka1882](https://www.frontendmentor.io/profile/Santaka1882)
- Twitter - [@Santaka1234](https://www.twitter.com/Santaka1234)
