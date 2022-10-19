# Frontend Mentor - Product preview card component

![Design preview for the Product preview card component coding challenge](./design/desktop-preview.jpg)

[Frontend Mentor](https://www.frontendmentor.io) challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./images/screenshot.png)

### Links

- [Product preview card](https://product-preview-component-five.vercel.app/)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

In this project I further continued my learnings on implementing box model within css. As well as, styling of typography elements.
I also learned about the picture element in HTML, thus image swapping at different media queries was much easier.

```css
@media (min-width: 640px) {
	.product {
		display: flex;
		max-width: 600px;
		height: 450px;
	}

	.product--details {
		width: 50%;
	}

	.card--img {
		height: 450px;
	}

	.card--img {
		border-top-right-radius: 0;
		border-bottom-left-radius: 10px;
		border-top-left-radius: 10px;
	}

	button {
		margin-bottom: 0;
	}
}
```

### Useful resources

- [Scrimba](https://scrimba.com/learn/learnreact) - This platform provided me with an opportunity to learn react for free

## Author

- Github - [@soji](https://github.com/soji-opa)

## Acknowledgments

I am very grateful to [Smug](https://github.com/theadusamuel) & [Openwell](https://github.com/openwell) for always making time out of their busy schedules to see to my coding challenges and providing me with extra motivation.
