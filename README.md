# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![](./design/destkop-design.jpg)

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it.

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

### Links

- Solution URL: (https://github.com/rizkibagus/social-links-profile)
- Live Site URL: (https://rizkibagus.github.io/social-links-profile/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```html
<div class="social-media-section">
  <a href="#">GitHub</a>
  <a href="#">Frontend Mentor</a>
  <a href="#">LinkedIn</a>
  <a href="#">Twitter</a>
  <a href="#">Instagram</a>
</div>
```

```css
.social-links-section .social-media-section {
  display: flex;
  flex-direction: column;
  gap: 15px;
  margin-top: 2rem;
}

.social-links-section .social-media-section a {
  font-weight: 600;
  color: var(--white);
  background-color: var(--grey700);
  padding: 12px 24px;
  border-radius: 10px;
  transition: ease 0.5s;
}

.social-links-section .social-media-section a:hover {
  background-color: var(--green);
  color: var(--grey700);
}
```

If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.

## Author

- Frontend Mentor - [@rizkibagus](https://www.frontendmentor.io/profile/rizkibagus)
- Twitter - [@bagusdev\_](https://www.twitter.com/bagusdev_)
