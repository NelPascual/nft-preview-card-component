# Frontend Mentor - NFT Preview Card Component Solution

This is a solution to the [NFT Preview Card Component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Links

- Solution URL: [Add solution URL here](https://github.com/NelPascual/nft-preview-card-component)
- Live Site URL: [Add live site URL here](https://nft-preview-card-nelpascual.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

Among the things I was able to learn and practice in this project are:
1. The use of :hover to animate changing or overlaying content over another element;
2. The use of position: relative and position:absolute.

Here are some examples:

```html
<div class="img-component">
  <a href="/"><img src="img/image-equilibrium.jpg" alt="Image Equilibrium"></a>
  <div class="img-component-hover">
      <img src="img/icon-view.svg" alt="Icon View">
  </div>
</div>
```
```css
.img-component {
    border-radius: 1rem;
    position: relative;
}

.img-component-hover {
    display: flex;
    align-items: center;
    justify-content: center;
    background-color: #00fff755;
    border-radius: 1rem;
    cursor: pointer;
    position: absolute;
    top: 0%;
    left: 0%;
    right: 0;
    bottom: 0;
    opacity: 0;
    transition: opacity .2s ease-in-out;
}

.img-component:hover > .img-component-hover {
    opacity: 1;
}
```

### Continued development

This is my third project done on this platform, I will continue to apply what I have learned in the following projects, taking advantage of each of the challenges, as each of them always challenges us to learn something new and correct mistakes made in previous projects.

## Acknowledgments

I thank Frontend Mentor for providing free resources to put into practice what I have learned, and above all a place to show them.
