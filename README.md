# Frontend Mentor - Newsletter sign-up form with success message solution

This is a solution to the [Newsletter sign-up form with success message challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/newsletter-signup-form-with-success-message-3FC1AZbNrv). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- Add their email and submit the form
- See a success message with their email after successfully submitting the form
- See form validation messages if:
  - The field is left empty
  - The email address is not formatted correctly
- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Screenshot
![](./design/desktop-preview.jpg)

### Links

- Solution URL: [Invailable](#)
- Live Site URL: [http://newsletter-sign-up-with-success-message.surge.sh](http://newsletter-sign-up-with-success-message.surge.sh)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- Css Animation
- BEM (custom) convention

### What I learned

The event fired when an text input field is being filled is "input" and not "change". 
To learn more
- [Change - Reference API](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwioj5uOoumCAxUVF1kFHUqNCnYQFnoECAsQAQ&url=https%3A%2F%2Fdeveloper.mozilla.org%2Ffr%2Fdocs%2FWeb%2FAPI%2FHTMLElement%2Fchange_event&usg=AOvVaw2jTUSycU0l5WGRi3QeCcQk&opi=89978449)

### Continued development

I add a small slide up animation on page load 
```css
@keyframes slide-up {
  0% {
    transform: translate(0, 4rem);
    opacity: 0;
  }
  
  100% {
    transform: translate(0, 0);
    opacity: 1;
  }
}
```

## Author

- Frontend Mentor - [@patzi275](https://www.frontendmentor.io/profile/patzi275)
- Twitter - [@patzidev](https://www.twitter.com/patzidev)