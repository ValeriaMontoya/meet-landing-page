# Frontend Mentor - Meet landing page solution

This is a solution to the [Meet landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/meet-landing-page-rbTDS6OUR). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Links

- Solution URL: [Frontend Mentor](https://www.frontendmentor.io/solutions/responsive-meet-landing-page-dzGmgjw00I)
- Live Site URL: [GitHub Pages](https://valeriamontoya.github.io/meet-landing-page/)

## My process

### Built with

- Semantic HTML5 markup
- Flexbox
- CSS Grid
- [Syntactically Awesome Style Sheets](https://sass-lang.com/)
- Mobile-first workflow

### What I learned

I used the hover media query for the first time, and I think it's a better approach than applying hover states solely in the desktop layout.

Here's how I implemented it:

```scss
@media (hover: hover) {
  .button {
    &--blue:hover {
      background-color: #71c0d4;
    }
    &--purple:hover {
      background-color: #b18bdd;
    }
  }
  .main {
    &__image:hover {
      transform: translateY(10px);
    }
  }
}
```

### Useful resources

- [1-Line Layouts](https://1linelayouts.glitch.me/) - 10 single-line CSS layouts by [@una](https://github.com/una). The seventh layout helped me achieve responsiveness for the images.

## Author

- Frontend Mentor - [@ValeriaMontoya](https://www.frontendmentor.io/profile/ValeriaMontoya)
- Twitter - [@val_smf](https://twitter.com/val_smf)
