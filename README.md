# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### Links

- Solution URL: [Github Repo](https://github.com/mtrivera/qr-code-component/)
- Live Site URL: [Github Pages Demo](https://mtrivera.github.io/qr-code-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I learned to use the `calc` command with CSS:


```css
: root {
  font-size: calc((var(--base) / 16) * 100%);
  --r15: calc((15 / var(--base) * 1rem));
  --r20: calc((20 / var(--base) * 1rem));
  --base: 16;
}
```

Also, I created a responsive layout:

```css
.container {
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  min-height: 100vh;
}
```

### Continued development

- Responsive layout
- Flexbox
- CSS custom properties
- CSS Grid

### Useful resources

- [Converting pixels to rems](https://coryrylan.com/blog/converting-css-pixels-to-rems) - This helped me with font sizes for the project. I really liked this pattern and will use it going forward.
- [Kevin Powell-CSS Responsive Layout Course (FREE)](https://courses.kevinpowell.co/conquering-responsive-layouts) - This is a great course that helped me understand layout. It focuses on Flexbox and media queries. I'd recommend it to anyone still learning this concept.

## Author

- Website - [Miguel T Rivera](https://www.your-site.com)
- Frontend Mentor - [@mtrivera](https://www.frontendmentor.io/profile/mtrivera)
