# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./images/Screenshot.jpg)

### Links

- Solution URL: [https://github.com/DamonTham/3-column-preview-card-component](https://github.com/DamonTham/3-column-preview-card-component)
- Live Site URL: [https://damontham.github.io/3-column-preview-card-component/](https://damontham.github.io/3-column-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```html
<div class="sedans">
  <img src="images/icon-sedans.svg" alt="" />
  <div class="heading">Sedans</div>
  <div class="text">
    Choose a sedan for its affordability and excellent fuel economy. Ideal for
    cruising in the city or on your next road trip.
  </div>
  <input type="button" value="Learn More" class="learnmore" />
</div>
```

```css
@media screen and (max-width: 375px) {
  .container {
    max-width: 345px;
  }

  .card {
    display: flex;
    flex-direction: column;
  }

  .learnmore {
    margin-top: 10px;
  }

  .luxury .learnmore:focus-visible {
    background-color: hsl(179, 100%, 13%);
    color: hsla(0, 0%, 100%, 0.75);
    transition: 0.2s ease-in-out;
  }
}
```

<!-- ```js
const proudOfThisFunc = () => {
  console.log("🎉");
};
``` -->

## Author

- Frontend Mentor - [@DamonTham](https://www.frontendmentor.io/profile/DamonTham)
