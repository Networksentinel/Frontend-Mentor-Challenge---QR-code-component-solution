# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H).

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)

## Overview

### Screenshot

![](./images/QR%20components%20screenshot.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

Although I thought I had a good grasp of HTML semantics and basic CSS, I was surprised by a few challenges. Choosing the right tag for the QR component and centering it vertically with the footer next to it was tricky. However, this challenge helped me reinforce some key concepts:

- `<section>` is super useful for grouping related content! 😄
- min-height is much better than height for making sure the content adapts when the screen is too narrow.
- to center one flex item vertically and keep the other at the bottom of the page, I used this CSS:

```css
body {
  min-height: 100%;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
}

main {
  flex: 1;
  display: flex;
  justify-content: center;
  align-items: center;
}
```

### Continued development

In future projects, I want to focus on:

- Not forgetting the basics — they’re always useful and form the foundation of solid work.
- Using Git commits more frequently and structuring my commit messages better.


### Useful resources I use all the time, but helped me in this challenge

- [https://compressor.io/](https://compressor.io/) - For quick image compression.
- [https://squoosh.app/](https://squoosh.app/) - For image optimization, especially the ability to convert images to WebP files.
- [https://responsively.app/](https://responsively.app/) - A great app to view the project on many different devices at the same time.
