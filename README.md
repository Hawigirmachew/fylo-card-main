# Frontend Mentor - Fylo data storage component solution

This is a solution to the [Fylo data storage component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/fylo-data-storage-component-1dZPRbV5n). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
 
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot
MObile view


![mobile-view](https://user-images.githubusercontent.com/88828065/193030735-e9016825-9085-4f6e-beab-fddbce55ad4d.PNG)

Desktop view
![desktop-view](https://user-images.githubusercontent.com/88828065/193030795-be1d9ad1-69a3-4e88-b48e-0eb69700db9b.PNG)


### Links

- Solution URL: [Solution](https://www.frontendmentor.io/challenges/fylo-data-storage-component-1dZPRbV5n/hub/fylo-data-storage-with-grid-and-flex-css-nTZlzk8pMR)
- Live Site URL: [Live site](https://lucky-sunburst-b5a5bc.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow


### What I learned
The use of css aninamtion

.bar {
  height: 10px;
  border-radius: 5px;
  background-image: linear-gradient(hsl(6, 100%, 80%), hsl(335, 100%, 65%));
  animation-name: progress-bar;
  animation-fill-mode: forwards;
  animation-duration: 4s;
}
@keyframes progress-bar {
  from {
    width: 0%;
  }
  to {
    width: 81.5%;
  }
}
.circle {
  height: 10px;
  width: 10px;
  border-radius: 50%;
  background-color: white;
  animation-name: circle1;
  animation-fill-mode: forwards;
  animation-duration: 2s;
}
@keyframes circle1 {
  from {
    margin-left: 0%;
  }
  to {
   margin-left: 96%;
  }
}


## Author

- Website - [Hawi Girmachew](https://lucky-sunburst-b5a5bc.netlify.app/)
- Frontend Mentor - [@Hawigirmahew](https://www.frontendmentor.io/profile/Hawigirmachew)
- Twitter - [@girmachee_h](https://www.twitter.com/girmachee_h)



