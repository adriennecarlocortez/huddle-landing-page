# Frontend Mentor - Huddle landing page with alternating feature blocks solution

This is a solution to the [Huddle landing page with alternating feature blocks challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-alternating-feature-blocks-5ca5f5981e82137ec91a5100). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

### Desktop

![Desktop Screenshot](/public/page/huddle-landing-page-desktop.png)

### Mobile

![Mobile Screenshot](/public/page/huddle-landing-page-mobile.png)

### Links

- Solution URL: [Github](https://github.com/adriennecarlocortez/huddle-landing-page)
- Live Site URL: [Netlify](https://adrienne-huddle-landing-page.netlify.app)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```html
<!-- Editable svg properties -->
<svg class="logo" width="240" height="39">
  <use xlink:href="/images/icon.svg#logo" alt="huddle logo" />
</svg>
```

```css
/* even-columns */
.even-columns {
  display: grid;
  gap: 1rem;
}
@media (min-width: 50em) {
  .even-columns {
    grid-auto-flow: column;
    grid-auto-columns: 1fr;
  }
}
```

### Useful resources

- [Kevin Powell Responsive Website Tutorial](https://www.youtube.com/watch?v=h3bTwCqX4ns&list=PL4-IK0AVhVjNDRHoXGort7sDWcna8cGPA) - This is an amazing video to understand building responsive website with best practices.
- [Any Bell CSS Reset](https://gist.github.com/Asjas/4b0736108d56197fce0ec9068145b421) - This help me have a reset css
- [SVG SPRIT](https://svgsprit.es/) - This help me compile the small svg icons of the website.

## Author

- Website - [Adrienne Carlo Cortez](https://adrienne-portfolio-b.netlify.app/)
- Frontend Mentor - [@adriennecarlocortez](https://www.frontendmentor.io/profile/adriennecarlocortez)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.

**Note: Delete this note and edit this section's content as necessary. If you completed this challenge by yourself, feel free to delete this section entirely.**