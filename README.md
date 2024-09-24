# WEB3BRIDGE Assignment solution

This is a solution to the [ Blackadam host clone site challenge](https://blackadam-host.netlify.app).

## Table of contents

- [WEB3BRIDGE Assignment solution](#web3bridge-assignment-solution)
  - [Table of contents](#table-of-contents)
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

- See hover and focus states for all interactive elements on the page

### Screenshot

![](./screenshot.jpg)


### Links

- Live Site URL: [https://kayode-cloned-site.netlify.app here](https://kayode-cloned-site.netlify.app)
- Solution URL: [https://github.com/Kayodejay/Blackadam-Clone-Site](https://github.com/Kayodejay/Blackadam-Clone-Site)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- desktop-first workflow


### What I learned

CSS grid was a curve-point pf learning for me through this project. i learning the application and interpretation of the grid properties and values

To see how you can add code snippets, see below:

```html
<div class="grid-display">
  <div class="hd1">box1</div>
  <div class="mn2">box2</div> 
  <div class="mn3">box3</div>
  <div class="mn4">box4</div>
  <div class="sb5">box5</div>
  <div class="mn6">box6</div>
  <div class="ft7">box7</div>
</div>
```
```css
.grid-diplay{
  display: grid;
  grid-template-area:
    "one one one"
    "two three three"
    "four four five"
    "six six five"
    "seven seven seven";
}

.hd1{ grid-area: one; }
.mn2{ grid-area: two; }
.mn3{ grid-area: three; }
.mn4{ grid-area: four; }
.sb5{ grid-area: five; }
.ft7{ grid-area: six; }

``` 

### Continued development

This project was a major eye-opener compared to the rest of the projects I have undertaken, I came across alot of challenges along the way and it made me realize I am still at an infant stage of my Web Dev journey. I would still need to do extensive learning on;

- CSS grid
- CSS selector
- CSS properties in general
- media queries (responsiveness)


### Useful resources

- [Writing semantic HTML](https://www.youtube.com/watch?v=HJ0-fUJ-2F0&t=165s&pp=ygUVd3JpdGluZyBzZW1hbnRpYyBodG1s) - This provided me with examples explaining on writing semantic HTML. I'd recommend it to anyone learning the concept
- [Write HTML 10x faster](https://www.youtube.com/watch?v=EhRPdUv1ZrA&list=LL&index=1) - This helped me find a faster way write HTML. I really liked this pattern and will use it going forward.
- [learn grid the easy way](https://www.youtube.com/watch?v=rg7Fvvl3taU) - This is an amazing video which helped me finally understand CSS grid. I'd recommend it to anyone still learning this concept.


## Author

- Frontend Mentor - [@Kayodejay](https://www.frontendmentor.io/profile/Kayodejay)
- Twitter - [@jaykayode529](https://www.twitter.com/jaykayode529)


