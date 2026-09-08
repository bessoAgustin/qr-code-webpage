# QR code component solution

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)


## Overview

This is the first of many projects in my front-end developer portfolio to get me a job in the field and eventually be able to work on projects for clients of my own autonomously.

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: [Repository URL](https://github.com/bessoAgustin/qr-code-challenge.git)
- Live Site URL: [Live site URL (GitHub Pages)](https://bessoagustin.github.io/qr-code-challenge/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I learned the basics of how to make the webpage responsive to make it look visually appealing independently of the device.
I also made good use of the 'class' attribute inside `<div>` components for future styling using CSS:

```html
  <div class="container">
    <img src="./images/image-qr-code.png" alt="QR code" class="qrCode">
    <div class="content">
      <h1>Improve your front-end skills by building projects</h1>
      <p>Scan the QR code and take your coding skills to the next level</p>
    </div>
  </div>
```
It was also my first time using external fonts in development:

```html
<link href="https://fonts.googleapis.com/css2?family=Outfit:wght@100..900&display=swap" rel="stylesheet">
```
I consider the most valuable block of code in my CSS file to be this next one, since it represented the real challenge of positioning the container div in the middle of the page to imitate as close as possible the given image. I learned for the first time how to use the Flexbox features for this action.

```css
.container {
      background-color: hsl(0, 0%, 100%);
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      padding: 1rem;
      font-family: 'Outfit', sans-serif;
      text-align: center;
      margin: 1rem auto;
      max-width: 250px;
      border-radius: 1rem;
    }
```

### Continued development

In future projects I plan to continue my path to learning how responsiveness works, and add accessibility features to strengthen my foundations in front-end development. Also, I plan to acquire more knowledge in the fields of UX/UI and be able to build websites not only functional but user-friendly and accessible. 

### Useful resources

- [W3Schools](https://www.w3schools.com/) - Always the most reliable source for troubleshooting when I get stuck with some concept.
- [Coder Coder's "Git, GitHub, & GitHub Desktop for beginners"](https://youtu.be/8Dd7KRpKeaE?si=ByinKElc8Pdtn6OA) - Great resource to learn how Git and GitHub work on real production environments.
- [The Common Coder's "How to Use GitHub Pages in 2026! (Beginner's Guide)"](https://youtu.be/5XhxR9Vs6zc?si=dzor6DHAP7dLhYso) - Clear and concise step-by-step of how to create a GitHub Page as my site hosting.

### AI Collaboration

Given the low complexity of the present project, the use of AI agents was truly limited. In this case, I used Claude when I felt I had already tried everything and wasn't getting to the desired solution, particularly on the Flexbox features and importing the 'Outfit' font from Google Fonts, which are tools I never used before. 

## Author

- Portfolio - [Agustín Besso](https://agustinbessoportfolio.vercel.app/)