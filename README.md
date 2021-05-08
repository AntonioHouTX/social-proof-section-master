# Frontend Mentor - Social proof section solution

This is a solution to the [Social proof section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-proof-section-6e0qTv_bA). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshots](#screenshot)
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

- View the optimal layout for the section depending on their device's screen size

### Screenshots
#### Desktop

![](images/desktop_screenshot.jpg)

#### Mobile (Top, Middle, & Bottom)
![](images/mobile_screenshot_top.jpg)
![](images/mobile_screenshot_middle.jpg)
![](images/mobile_screenshot_bottom.jpg)



### Links

- Solution URL: [HTML/CSS Site Using CSS Grid and Flexbox](https://www.frontendmentor.io/solutions/htmlcss-site-using-css-grid-and-flexbox-JQmiWnUPN)
- Live Site URL: [Social Proof Section Project](https://antoniohoutx.github.io/social-proof-section-master/index.html)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

Probably the biggest challenge in working on this project was the addition of the stars in the ratings section of the website.  Since we were provided only one image of a star, I had duplicated it 5 times in the HTML, and manipulated the margins of its parent container to render it properly (on both the desktop and mobile versions.  The code snippets created to demonstrate this are:


```html
<div class="reviews">
  <div class="stars">
    <span class="star"><img src="images/icon-star.svg"></span>
    <span class="star"><img src="images/icon-star.svg"></span>
    <span class="star"><img src="images/icon-star.svg"></span>
    <span class="star"><img src="images/icon-star.svg"></span>
    <span class="star"><img src="images/icon-star.svg"></span>
  </div>
  <p class="rating">Rated 5 Stars in Reviews</p>
</div>
```
```css
.proud-of-this-css {
  .reviews,
  .report_guru,
  .besttech {
    background-color: hsl(300, 24%, 96%); /* Light Grayish Magenta */
    display: flex;
    margin: 0.8125rem 0rem;
    padding-left: 1.25rem;
    border-radius: 10px;
    align-items: center;
  }

  .star {
    margin: 0.25rem;
  }

  .rating {
    margin-left: 1.5rem;
  }
}
```
### Continued development

Areas that I would like to continue to focus on in the future include unit measurements (fr vs rem, etc.) and striking a balance in creating responsive websites between the way it is rendered on a desktop vs. mobile.

### Useful resources

- [Stack Overflow](https://stackoverflow.com/questions/2949606/repeat-css-background-image-a-set-number-of-times) - The aforementioned subject of repeating background stars was addressed by this question and answer in Stack Overflow.  It was incredibly useful in designing this project.

## Author

- Frontend Mentor - [@AntonioHouTX](https://www.frontendmentor.io/profile/AntonioHouTX)
- Twitter - [@clintmaxwell](https://www.twitter.com/clintmaxwell)
- LinkedIn - [Clint Maxwell](https://www.linkedin.com/in/maxwellclint/)

## Acknowledgments

Once again, special thanks goes out to [Drull](https://github.com/drull1000) for his patience and guidance on this project.  His tips were invaluable.
