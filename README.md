# Frontend Mentor - Meet landing page solution

This is a solution to the [Meet landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/meet-landing-page-rbTDS6OUR). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![Meet Landing Page](meet-landing-page-codebase\assets\screenshot\meet.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

Using the correct semantic tags in **HTML 5** allows for easy lookup of your HTML 5 code, tags like the following are commonly used, for ex:

```html
<main>The Main Content goes here! Occurs once per page.</main>

<section>
  Different Sectional content goes here! Can be used multiple times per page.
</section>

<footer>Occurs once per page.</footer>
```

For layout **CSS Grid** was primarily used; using the following properties:

```css
.someContainer {
  grid-template-columns: repeat(3, minmax(20rem, 1fr))
  grid-template-areas:
    "heading",
    "image",
    "footer";
}
```

Also using the following **CSS** properties to _Display_ a block from **none** to **block** during the _hover_ state. Make sure that the tag being hovered over **precedes** the tag to be _displayed_, as follows:

```html
<button type="button">Download</button>
<p>Some content that will be displayed while the button is hovered over!</p>
```

```css
p {
  display: none;
}

button:hover + p {
  background-color: #fafafa;
  display: block;
}
```

### Continued development

Refactoring **CSS** code, as well as starting to think about writing _re-usuable modular_ code.

### Useful resources

- [LearnWebDev by Brad Schiff](https://youtu.be/pMVO1OPfVJ8) - Provides pratical use cases for **CSS GRID** with examples.

## Author

- GitHub - [Shahin Nosrat Jogan](https://github.com/SJ-Nosrat?tab=repositories)
- Frontend Mentor - [@shahin1987](https://www.frontendmentor.io/profile/shahin1987)

## Acknowledgments

All the YouTubers, FreeCodeCamp and FrontEndMentor.
