# Blogr Landing Page Website

This is a fully responsive **Blogr landing page website** built with HTML and CSS.  
It features a modern layout, smooth animations, and adapts seamlessly to different screen sizes — from mobile to desktop.  
The design includes interactive hover states, unique section shapes, and clean typography for a polished, professional look.


## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size.
- See hover states for all interactive elements on the page.
- Experience smooth animations and responsive design adjustments.

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic **HTML5** markup
- **CSS custom properties**
- **Flexbox**
- **CSS Grid**
- **Responsive design** with media queries
- **Google Fonts** - Overpass and Ubuntu
- **Mobile-first workflow**
- Basic **CSS animations and keyframes**

### What I learned

While building this project, I gained a deeper understanding of:

- Structuring a responsive landing page using **flexbox** and **grid** together.
- Creating smooth animations using `@keyframes` for fade and scale effects.
- Using **multiple background images** and gradients in the same element.
- Applying **border-radius** creatively to achieve unique shapes in the header and footer.
- Writing media queries to progressively adapt layouts for different screen widths.

Example of combining a gradient and a background image:

```css
header {
  background-image: url('./images/bg-pattern-intro-desktop.svg'),
    linear-gradient(to right, hsl(13, 100%, 72%), hsl(353, 100%, 62%));
  background-position: center;
  border-bottom-left-radius: 110px;
}
````

Example of smooth scale animation:

```css
@keyframes first-img-animation {
  to {
    scale: 1;
    opacity: 1;
  }
}
```

### Continued development

In the future, I plan to:

- Add JavaScript functionality for the mobile menu toggle.
- Implement smooth dropdown animations for navigation menus.
