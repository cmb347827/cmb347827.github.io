# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)


## Overview

### Screenshot

![QR code component project](https://i.postimg.cc/xThwn5nY/qr-code-project.png "QR code component project screenshot")

### Links

- Solution URL: [Add solution URL here](https://github.com/cmb347827/github.io)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow


### What I learned

I focused again firstly on the mobile version as it is best practice to develop using a 'mobile-first' approach. 

I could not find the same background as in the design, so I found one close enough but it was dark pink with colored squiggles.

So I had to use a sheer pink transparant background in the foreground to give the same light-pink background.



### Continued development

I have been using codepen.io too much , and so focused mostly on laptop version development first as it happened naturally.

I remember now that a 'mobile-first' approach is the better way to develop, and by changing my mindset I will develop with it in mind from the start.

### Useful resources

- [CSS tricks full screen background](https://css-tricks.com/perfect-full-page-background-image/) - I have used this code before in applying full coverage background.
- [make-an-empty-div-height-and-width-of-its-container](https://stackoverflow.com/questions/11301151/make-an-empty-div-height-and-width-of-its-container) - This helped me to understand how to cover the foreground container color.
- [How to make only the parent element opaque](https://stackoverflow.com/questions/10879045/how-to-set-opacity-in-parent-div-and-not-affect-in-child-div) - This was new to me. I first tried applying opacity to the parent , but then the child element inherited it. By using hsla() color instead on the parent the child did not inherit the transparancy
- [A more responsive approach to using height in CSS] (https://stackoverflow.com/questions/9537838/div-height-100-and-expands-to-fit-content) - Using 

         `#qr-code-container {display: block ; overflow: auto;} html,body{ height: 100%}`

## Author

- Frontend Mentor - [@cmb347827](https://www.frontendmentor.io/profile/cmb347827)







