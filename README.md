# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Links

- Solution URL: [Github](https://github.com/Specternim/av-product-card-frontend-mentor)
- Live Site URL: [Netlify](https://av-product-card.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I've used data attributes before but never thought they could be implemented in CSS as well. They can be used to switch between multiple SVGs when working on a big project and will save a lot of JavaScript code.

Custom block scoped properties were something new that I came across. It was good to learn about them and how easy they make it to switch between various sizes by just changing their values in media queries.

```html
<h1 data-attributes="#"></h1>
```

```css
.btn[data-icon="shopping-cart"]::before {
  content: "";
  width: 15px;
  height: 16px;
  background-image: url("images/icon-cart.svg");
}

.product {
  --content-padding: 1.5rem;
  --content-spacing: 1rem;
}
```

### Useful resources

- [Josh W Comeau](https://www.joshwcomeau.com/css/custom-css-reset/) - A modern CSS reset.
- [Scott Ohara](https://www.scottohara.me/blog/2017/04/14/inclusively-hidden.html) - This article is for making some content hidden for users but useful for screen readers to help impaired users to know what particular values actually mean.

## Author

- Frontend Mentor - [@Vishal Alkari](https://www.frontendmentor.io/profile/Specternim)

## Acknowledgments

Thanks to Sandy K. for sharing this project with me. It was a really good experience to learn something new along the way and a great shout out to Kevin Powell to make a video on this and making it so simple to follow along!
