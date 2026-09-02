# Frontend Mentor - Blog Preview Card Solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckveHhDpS).

## Table of Contents

- [Overview](#overview)
  - [The Challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My Process](#my-process)
  - [Built With](#built-with)
  - [What I Learned](#what-i-learned)
- [Author](#author)

## Overview

### The Challenge

Users should be able to:

- View the optimal layout for the card depending on their device's screen size
- See hover states for interactive elements

### Screenshot

<img width="1911" height="908" alt="blog preview" src="https://github.com/user-attachments/assets/f525f286-a08a-44f5-a989-3db5f386b7dc" />


### Links

- Live Site URL: ([Click](https://khaalidd.github.io/blog-preview-card/))

## My Process

### Built With

- Semantic HTML5 markup
- CSS custom properties (variables)
- Flexbox
- Mobile-first workflow
- [Figtree](https://fonts.google.com/specimen/Figtree) Google Font

### What I Learned

Working on this card helped me practice building a small, self-contained component with a card-based layout. A few things I paid attention to:

```css
.container {
    max-width: 384px;
    box-shadow: 10px 10px 0px 0px black;
}
```

I also worked on keeping typography and spacing consistent using `rem` units and CSS variables for color, which makes the design easier to adjust later:

```css
:root {
    --bg-color: #F4D04E;
    --primary-text: #111111;
    --secondary-text: #6B6B6B;
}
```


## Author

- Frontend Mentor - [@Khaalidd](https://www.frontendmentor.io/profile/Khaalidd)
