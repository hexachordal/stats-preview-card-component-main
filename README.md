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


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](images/screenshotOfStatsPreviewCard.png)

### Links

- Solution URL: [https://github.com/hexachordal/stats-preview-card-component-main]
- Live Site URL: [https://hexachordal.github.io/stats-preview-card-component-main/]

## My process

### Built with

- Semantic HTML5 markup
- CSS 
- Flexbox


### What I learned

I learned that I should try a mobile-first approach and build outwards though it feels counter-intuitive to me presently. Using chrome-dev tools was a lifesaver for making changes to the css particularly. I had some issues with getting my left and right components in my card to be equally sized and I learned to apply this code particularly reapplying the box-sizing: border-box for the left and right cards:

```css
#lCard{
        display: flex;
        width: 50%;
        height: auto;
        box-sizing: border-box;
        padding: 0 10% 0 6%;
        color: hsl(0, 0%, 100%);
        flex-direction: column;
        justify-content: center;
        align-items: center;
        border-radius: inherit;
    }
```
I also learned to make sure to add alt text to my images and maybe next time I'll do the image sources in css that way I can change to a smaller image for mobile devices.



### Continued development

In the future, I would like to figure out how to get the color properly overlayed on the image as well as clean up my font sizes as they work responsively.

### Useful resources

- [https://css-tricks.com/css-media-queries/] - This helped with media queries though I have to figure out how to do max and min properly

- [https://quirksmode.org/css/user-interface/boxsizing.html] - This helped me have my "ah ha!" moment with the box sizing on the card elements.

- [https://www.w3schools.com/css/css_background.asp] - w3schools in general helped with everything but particularly when I was trying to figure out how to do the color overlay on the image.



## Author

- Website - [https://github.com/hexachordal]

- Frontend Mentor - [https://www.frontendmentor.io/profile/hexachordal]




