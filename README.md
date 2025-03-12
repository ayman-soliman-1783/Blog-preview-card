# Frontend Mentor - Blog preview card solution

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
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![Design Screenshot](/design/Screenshot_12-3-2025_211451_127.0.0.1.jpeg)

### Links

- Solution URL: [Blog Preview Card Solution](https://www.frontendmentor.io/solutions/blog-preview-card-with-stylish-transitions-and-selection-phVn9qXm8f)
- Live Site URL: [Live Preview](https://ayman-soliman-1783.github.io/Blog-preview-card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Transitions
- Colorful selection pesudo element

### What I learned

Working on the Blog Preview Card project helped me improve my skills in Flexbox, responsive design, and typography. I used CSS custom properties, and subtle hover effects to enhance usability and maintainability. This project reinforced my understanding of layout structuring and interactive design.

```html
<div class="container">
  <img
    src="assets/images/illustration-article.svg"
    alt="article-illustration"
  />
  <span>Learning</span>
  <p>Published 21 Dec 2023</p>

  <h2>HTML & CSS foundations</h2>
  <p>
    These languages are the backbone of every website, defining structure,
    content, and presentation. Greg Hooper
  </p>
  <div class="avatar">
    <img src="assets/images/image-avatar.webp" alt="Greg Hooper" />
    <h5>Greg Hooper</h5>
  </div>
</div>
```

```css
.container:hover {
    transform: translate(-0.5rem, -0.5rem);
    box-shadow: 1.5rem 1.5rem 0 0 black;
}

*::selection {
    background-color: #f5d04e;
    color: white;
}
```

### Continued development

For continued development, I plan to explore CSS animations to add subtle motion effects for a more dynamic user experience. Additionally, I want to refine my approach to accessibility by improving keyboard navigation and contrast ratios. I will also experiment with CSS Grid for more complex layouts and optimize performance by minimizing CSS redundancy.

## Author

- Website - [Ayman Soliman](https://bento.me/ayman-soliman)
- Frontend Mentor - [@ayman-soliman-1783](https://www.frontendmentor.io/profile/ayman-soliman-1783)
- Twitter - [@a_soliman1783](https://x.com/a_soliman1783)