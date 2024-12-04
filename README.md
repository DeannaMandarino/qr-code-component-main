# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### Screenshot

![QR Code Component Screenshot](/screenshot/qr-code-component-screenshot.png)

### Links

- Solution URL: [Solution](https://github.com/DeannaMandarino/qr-code-component-main)
- Live Site URL: [Live Site](https://deannamandarino.github.io/qr-code-component-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties (CSS Variables) for color management
- Flexbox for centering and responsive layout
- Mobile-first design approach
- Responsive media queries for small screen adjustments

### What I learned

During this project, I learned how to implement a clean, responsive design that works across different screen sizes. By using Flexbox, I was able to center the content both horizontally and vertically. The challenge also provided an opportunity to practice working with media queries for responsive adjustments.

Here's some of the code I’m particularly proud of:

```html
<main class="container">
  <img class="qr-code" src="images/image-qr-code.png" alt="QR code that links to Frontend Mentor">
  <h1 class="title">Improve your front-end skills by building projects</h1>
  <p class="instructions">Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p>
</main>
```
```css
body {
  background-color: var(--background-color);
  font-size: 1.5rem;
  font-family: Outfit, sans-serif;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  margin: 6rem 0;
}

.container {
  background-color: var(--container-color);
  text-align: center;
  padding: 1.5rem;
  width: 29rem;
  border-radius: 1.5rem;
  box-shadow: 0.5rem 0.5rem 1.2rem var(--box-shadow-color);
}
```

### Continued development

Moving forward, I would like to refine my understanding and application of Flexbox, especially in more complex layouts. I also aim to focus on improving my CSS skills, particularly in optimizing for responsiveness across various devices and screen sizes.

## Author

- GitHub - [Deanna Mandarino](https://github.com/DeannaMandarino)
- Frontend Mentor - [@DeannaMandarino](https://www.frontendmentor.io/profile/DeannaMandarino)

## Acknowledgments

Thanks to Frontend Mentor for providing this challenge to enhance my HTML and CSS skills.