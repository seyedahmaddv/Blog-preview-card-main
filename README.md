# Frontend Mentor - Blog Preview Card Solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- View the optimal layout depending on their device's screen size (responsive design)
- See hover state animation for the card component
- Experience a clean and modern blog preview card design

### Screenshot

![](/design/desktop-design.jpg)

### Links

- Solution URL: [https://www.frontendmentor.io/profile/seyedahmaddv/solutions](https://www.frontendmentor.io/profile/seyedahmaddv/solutions)
- Live Site URL: [https://blog-preview-card-main-chi-flame.vercel.app/](https://blog-preview-card-main-chi-flame.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties (variables)
- Flexbox
- Mobile-first workflow
- Responsive design principles
- CSS transitions for hover effects
- Google Fonts (Figtree)

### What I learned

This project helped me strengthen my understanding of building interactive components with CSS. Some key learnings include:

- Using CSS variables for consistent color themes and easy maintenance:
```css
:root {
  --yellow: hsl(47, 88%, 63%);
  --white: hsl(0, 0%, 100%);
  --gray-500: hsl(0, 0%, 42%);
  --gray-950: hsl(0, 0%, 7%);
  --border-radius: 15px;
  --box-shadow: 8px 8px 0px 0px var(--gray-950);
}
```

- Creating engaging hover animations with CSS transitions:
```css
.card {
  transition: transform 0.3s ease;
}

.card:hover {
  transform: translate(-5px, -5px);
  box-shadow: 13px 13px 0px 0px var(--gray-950);
}
```

- Building responsive layouts that work well on different screen sizes:
```css
@media (max-width: 375px) {
  main {
    width: 100%;
  }
  
  .card-content {
    padding: 1.2rem;
  }
}
```

### Continued development

In future projects, I want to focus on:

- Enhancing my CSS animation skills
- Exploring more advanced responsive design techniques
- Implementing accessibility best practices
- Learning more about CSS Grid for complex layouts

### Useful resources

- [MDN Web Docs](https://developer.mozilla.org) - Comprehensive resource for HTML and CSS references
- [CSS-Tricks](https://css-tricks.com) - Great articles about modern CSS techniques
- [Google Fonts](https://fonts.google.com) - Easy access to open-source web fonts

## Author

- Website - [Seyed Ahmad Gholami](https://github.com/seyedahmaddv)
- Frontend Mentor - [@seyedahmaddv](https://www.frontendmentor.io/profile/seyedahmaddv)
- Linkedin - [@seyedahmaddv](https://www.linkedin.com/in/seyedahmaddv)
