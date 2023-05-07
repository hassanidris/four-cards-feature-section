# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### Screenshot

![Screenshot 2023-05-07 at 12 11 09](https://user-images.githubusercontent.com/69512496/143189939-60d5fb1e-0c94-45bf-afa6-9b1df9c63f50.png)

### Links

- Solution URL: https://github.com/hassanidris/four-cards-feature-section
- Live Site URL: https://hassanidris.github.io/four-cards-feature-section/

## My process

### Built with

- SASS / CSS Variables
- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

To see how you can add code snippets, see below:

- CSS Variables

```scss
--clr-red: 0 78% 62%;
--clr-cyan: 180 62% 55%;
--clr-orange: 34 97% 64%;
--clr-blue: 212 86% 64%;
```

- Nesting media queries inside the classes

```scss
@media (max-width: 610px) {
  .statement {
    font-size: var(--fs-400);
    text-align: center;
    margin: 0 0.1em;
  }

  .header_title {
    font-size: var(--fs-400);
    text-align: center;
    margin: 0 0.4em;
  }

  .header_text {
    width: 100%;
    text-align: center;
    margin: 0 6em;
  }

  .cards {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    margin: 1em;
  }
}
```

## Author

- Github - [hassanidris](https://github.com/hassanidris)
- Frontend Mentor - [@hassanidris](https://www.frontendmentor.io/profile/hassanidris)
