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
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![](./assets/images/Screenshot%20Frontend%20Mentor%20Social%20links%20profile.png)

### Links

- Solution URL: [Solution URL here](https://github.com/stephany247/social-links-profile)
- Live Site URL: [Live site URL here](https://stephany247.github.io/social-links-profile/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow\*

### What I learned

- CSS Custom Properties (Variables): I learned to use CSS custom properties to manage colors efficiently, which made it easier to maintain consistency across the project.

css

```css
:root {
  --Green: hsl(75, 94%, 57%);
  --White: hsl(0, 0%, 100%);
  --Grey-700: hsl(0, 0%, 20%);
  --Grey-800: hsl(0, 0%, 12%);
  --Grey-900: hsl(0, 0%, 8%);
}
```

- Hover Effects: I learned how to create hover states to enhance the user experience by changing the card’s box-shadow and title color.
  css

```css
.link:hover,
.link:focus {
  background-color: var(--Green);
  color: var(--Grey-900);
}
```

### Continued development

- Responsive Design Techniques: While I used a mobile-first workflow, I want to continue refining my skills in making layouts more responsive across a wider range of screen sizes and devices, ensuring perfect fluidity.

- Advanced Hover and Transition Effects: I experimented with hover effects and transitions in this project, but I’d like to explore more complex animations and interactions in future projects to make the UI more engaging.

- Accessibility Enhancements: Accessibility is crucial, and I plan to continue focusing on improving accessibility features, like better screen reader support and keyboard navigation, to ensure that my projects are usable by all users.

- CSS Grid: I primarily used Flexbox for this project, but I aim to explore CSS Grid further in future projects for more complex layouts and better control over two-dimensional designs.

### Useful resources

- [Google Fonts](https://fonts.google.com/) - This helped me understand how to embed custom fonts into my project and manage different font weights and styles.
- [Stack Overflow](https://stackoverflow.com/) - I found helpful solutions for CSS issues, like handling hover effects and box shadows, which were crucial for implementing the card design in this project.

## Author

- Website - [Onyinye Stephanie Oguocha](https://www.your-site.com)
- Frontend Mentor - [stephany247](https://www.frontendmentor.io/profile/stephany247)
- Twitter - [@stephanyoguocha](https://x.com/stephanyoguocha)

## Acknowledgments

I would like to give a big thanks to the Frontend Mentor community and the resources on Stack Overflow for helping me troubleshoot and improve my project.
