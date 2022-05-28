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

![Screenshot - Frontend Mentor QR Code Component](images/Screenshot%20-%20Frontend%20Mentor%20QR%20code%20component.png)

### Links

- Solution URL: [Add solution URL here](https://github.com/Mixhetl/QR-code-component)
- Live Site URL: [Add live site URL here](https://mixhetl.github.io/QR-code-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Mobile-first workflow

### What I learned

Better for to use semantic tags. And simplify my CSS code.

```html
<section class="card">
  <img class="img" src="images/image-qr-code.png" alt="QR Image.png" />
  <h1 class="title">Improve your front-end skills by building projects</h1>
  <p class="paragraph">
    Scan the QR code to visit Frontend Mentor and take your coding skills to the
    next level
  </p>
</section>

<footer class="attribution">
  Challenge by
  <a href="https://www.frontendmentor.io?ref=challenge" target="_blank"
    >Frontend Mentor</a
  >. Coded by
  <a href="https://www.linkedin.com/in/luis-malquiel-hernandez-avendano/"
    >Luis Malquiel Hernández Avendaño</a
  >.
</footer>
```

```css
:root {
  /**Primary colors**/
  --white: hsl(0, 0%, 100%);
  --light-gray: hsl(212, 45%, 89%);
  --grayish-blue: hsl(220, 15%, 55%);
  --dark-blue: hsl(218, 44%, 22%);

  /** Font Family **/
  --main: "Outfit", sans-serif;
}

* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

body {
  height: 100%;
  background-color: var(--light-gray);
  font-family: var(--main);
}

/**Main Styles**/
.card {
  width: 300px;
  height: 500px;
  padding: 15px;
  background-color: var(--white);
  border-radius: 15px;
  margin: 100px auto 100px;
  text-align: center;
}

.img {
  width: 100%;
  border-radius: 15px;
}

.title {
  color: var(--dark-blue);
  font-size: 1.3rem;
  margin: 20px auto 20px;
}

.paragraph {
  color: var(--grayish-blue);
  font-weight: 400;
}

/**Footer**/
.attribution {
  margin: 0 auto;
  width: 100%;
  text-align: center;
  padding-bottom: 30px;
  color: var(--dark-blue);
}

.attribution > a {
  text-decoration: none;
  color: var(--dark-blue);
}
```

### Continued development

I want to refine my style sheets. Learn to use flexbox in a complex way to make better layouts. I look forward to continuing to practice my templates using flexbox. It's pretty fun.

## Author

- Frontend Mentor - [@Mixhetl](https://www.frontendmentor.io/profile/Mixhetl)
- Twitter - [@XxmalkyelxX](https://twitter.com/XxmalkyelxX)

## Acknowledgments

To make cards it is better to do it with DIV's or with article, however, ARTICLE does not accept a border radius, I recommend using DIV.
