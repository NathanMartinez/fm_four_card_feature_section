# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![](./images/Screen%20Shot%202023-01-21%20at%2011.09.30%20PM.png)
![](./images/Screen%20Shot%202023-01-21%20at%2011.09.44%20PM.png)
![](./images/Screen%20Shot%202023-01-21%20at%2011.09.56%20PM.png)

### Links

- Solution URL: [Github Repo](https://github.com/NathanMartinez/fm_four_card_feature_section)
- Live Site URL: [Github Pages Site](https://nathanmartinez.github.io/fm_four_card_feature_section/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

```css
.card_container {
	grid-template-columns: repeat(3, 1fr);
	grid-template-rows: repeat(4, 115px);
	grid-template-areas:
		'. team-builder .'
		'supervisor team-builder calculator'
		'supervisor karma calculator'
		'. karma .';
	max-width: 70rem;
}

.card.supervisor {
	grid-area: supervisor;
}

.card.team-builder {
	grid-area: team-builder;
}

.card.karma {
	grid-area: karma;
}

.card.calculator {
	grid-area: calculator;
}
```

### Continued development

- React
- Svelte
- Vue
- Nextjs
- CSS Grid
- Semantic HTML

### Useful resources

- [CSS Tricks](https://css-tricks.com/snippets/css/complete-guide-grid/) - This is a great CSS Grid guide.

## Author

- Github - [Github](https://github.com/NathanMartinez)
- Frontend Mentor - [@NathanMartinez](https://www.frontendmentor.io/profile/NathanMartinez)
