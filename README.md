# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Acknowledgments](#acknowledgments)



## Overview

### The challenge

Users should be able to:

- See hover states for interactive elements

### Screenshot

![before hover](./images/Screenshot%202022-10-24%20at%2020-26-36%20Frontend%20Mentor%20NFT%20preview%20card%20component.png)

![after hover](./images/Frontend%20Mentor%20_%20NFT%20preview%20card%20component.png)


### Links

[Solution  URL:](https://github.com/Wahomethegeek/nft-preview-card-component-main.git)
![Live Site URL:](https://nft-preview-card-component-eight-eta.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox


### What I learned

at first I had a problem styling up the hover effect on the image but at long last i was able to succeed it by knowing positioning and opacity

```html
        <div class="image">
            <div class="overlay">
              <svg width="48" height="48" xmlns="http://www.w3.org/2000/svg"><g fill="none" fill-rule="evenodd"><path d="M0 0h48v48H0z"/><path d="M24 9C14 9 5.46 15.22 2 24c3.46 8.78 12 15 22 15 10.01 0 18.54-6.22 22-15-3.46-8.78-11.99-15-22-15Zm0 25c-5.52 0-10-4.48-10-10s4.48-10 10-10 10 4.48 10 10-4.48 10-10 10Zm0-16c-3.31 0-6 2.69-6 6s2.69 6 6 6 6-2.69 6-6-2.69-6-6-6Z" fill="#FFF" fill-rule="nonzero"/></g></svg>
            </div>
            <img  class="equil" src="./images/image-equilibrium.jpg" alt="Equilibrium">
        </div>
```
```css
.overlay{
    position: absolute;
     width: 320px;
    height: 315px; 
    top: 49%;
    left: 50%;
    padding-left: 20px;
    transform: translate(-50%, -50%);
    background-color: hsl(178, 100%, 50%);
    display: flex;
    justify-content: center;
    align-items: center;
     opacity: 0;
    border-radius: 10px;

}
```

## Acknowledgments
Thanks to slack community for frontend mentor I was able to understand the hover effect.

