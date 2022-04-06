# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

### The challenge

- Built out the project for both mobile and desktop screen sizes of 1440px and 375px 

### Screenshot

![Mobile version](disc/screenshots/Profile-Card-Component-mobile.png)
![Desktop version](disc/screenshots/Profile-Card-Component-desktop.png)

### Links

- Solution URL: [GitHub](https://github.com/olisa187/Profile-card-component)
- Live Site URL: [Profile-card-component website](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Desktop-first workflow

### What I learned

During this project build up I did try different styling that I have not tried before and they include the use of the ::before pseudo-element, the transform scale key / value to the applied CSS property.

To see how you can add code snippets, see below:


```css
.card::before{
	content: "";
	position: absolute;
	top: 0;
	min-width: 100%;
	min-height: 35%;
	background: url(images/bg-pattern-card.svg) no-repeat;
	background-size: cover;
	border-top-right-radius: 1em;
	border-top-left-radius: 1em;
	z-index: -1;
}
```

### Continued development

Still working on the use of Block Element Modifiers method for my naming convention during my web page build up.

### Useful resources

- [Mutiple background](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Backgrounds_and_Borders/Using_multiple_backgrounds) - This helped me to understand how to use two or more different background-images together with a background-color.

- [Multiple Backgrounds](https://www.w3schools.com/css/css3_backgrounds.asp) - This is an amazing article which helped me finally understand the use of mutiple background. I'd recommend it to anyone still learning this concept.

- [Backgrounds](https://css-tricks.com/css-basics-using-multiple-backgrounds/)

## Author

- Frontend Mentor - [@olisa187](https://www.frontendmentor.io/profile/olisa187)
- Twitter - [@olisa187](https://www.twitter.com/olisa187)


## Acknowledgments

- csstricks.com
- w3schools.com
- developer.mozilla.org