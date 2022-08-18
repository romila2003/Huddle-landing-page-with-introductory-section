# Frontend Mentor - Huddle landing page with single introductory section

This is a solution to the [Huddle landing page with single introductory section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-a-single-introductory-section-B_2Wvxgi0). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- Build out the project to the designs provided.

### Screenshot

# Mobile Preview 

![screenshot]()

# Tablet Preview

![screenshot]()

# Desktop Preview 

![screenshot]()


### Links

 - Source code: []()
 - Live website: []()

## My process

### Built with

- Semantic HTML5 markup
- Plain CSS
- Flexbox
- Mobile-first workflow

### What I learned

This challenge was not too difficult regarding the content within the lading page however the background property was difficult to adjust to look like the design therefore I tried but couldn't imitate it. The mobile version looks similar to the design provided, where I also included the `hover` effect for the button and the social media icons. Overall, it was a great challenge and helped me to test out my layout skills for a web page rather than a small component.


CSS - Background: 

```css

body {
    background-color: var(--violet);
    height: 100vh;
    background-image: url(/images/bg-mobile.svg);
    background-repeat: no-repeat;
    background-size: contain;
    overflow-x: hidden;
    display: flex;
    justify-content: center;
    align-items: center;
    position: relative;
}

&&

@media screen and (min-width: 800px) {
    body {
        background-image: url('/images/bg-desktop.svg');
        background-size: cover;
        background-attachment: fixed;
    }
}

```

### Continued development

For future developments, I need to work on more complex HTML and CSS challenges and try challenges that involve web pages since that would test my layout skills more than the smaller components. I should also incorporate Javascript into future projects.


## Author

- Frontend Mentor - [@romila2003](https://www.frontendmentor.io/profile/romila2003)
- Twitter - [@romila003](https://www.twitter.com/romila003)
