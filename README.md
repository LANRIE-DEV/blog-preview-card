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

![](/assets/blog-preview-card%20screenshot.png)

### Links

- Solution URL: [https://lanrie-dev.github.io/blog-preview-card/]
- Live Site URL: [(https://lanrie-dev.github.io/blog-preview-card/)]

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Flex
- Mobile-first workflow

### What I learned
1. I learnt the use of the "article" tag for the card for the purpose of reusability, self-containment.
2. I learnt the use of "transition" property.

```html
<h1>
  <article>
  </article>
</h1>
```

```css
.info-card {
  background-color: hsl(0, 0%, 100%);
  width: 380px;
  height: 520px;
  padding: 20px;
  border: 1px solid black;
  border-radius: 18px;
  box-shadow: 10px 10px 0px -1px black;
  transition: box-shadow 0.2s ease;
}

.info-card:hover {
  box-shadow: 20px 20px 0px -1px black;
}

```

### Continued development

### Useful resources

- [Example resource 1](https://www.example.com)
- [Example resource 2](https://www.example.com)

## Author

- Website - [LANRIE-DEV](https://lanrie-dev.github.io/blog-preview-card/)
- Frontend Mentor - [@LANRIE-DEV](https://www.frontendmentor.io/profile/LANRIE-DEV)
