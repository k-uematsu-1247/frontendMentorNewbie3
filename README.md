# frontendMentorNewbie3
# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)


## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Links

- Solution URL: https://github.com/k-uematsu-1247/frontendMentorNewbie3
- Live Site URL: https://frontendmentornewbie3.onrender.com/

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

During this project, I focused on implementing precise visual properties and ensuring strong digital accessibility. I am proud of these specific elements:

- **`box-shadow` configurations:** I learned how to style non-blurry, hard-edged offset shadows to accurately recreate the bold Neo-brutalism layout theme.
- **`focus-visible` integration:** I mastered using the custom focus ring to separate keyboard navigation styles from general mouse clicks, providing a visible layout without disrupting natural mouse interactions.

Here is the structured card layout and CSS logic I used:

```html
<div id="card">
  <div id="card-header"><img src="./assets/images/illustration-article.svg" alt="illustration-article"></div>
  <div id="card-center">
    <!-- Component content goes here -->
  </div>
</div>
```

```css
#card {
    background: var(--White);
    width: 100%;
    max-width: 384px;
    border: var(--Gray-950) solid 1px;
    border-radius: 20px;
    padding: 1.5em;
    display: grid;
    gap: 1.5em;
    box-shadow: 8px 8px 0 0 var(--Gray-950);
}

#card-center h1 a:focus-visible {
    outline: 2px dashed var(--Gray-950);
    outline-offset: 4px;
}
```

### Continued development

In future projects, I want to keep building upon these core frontend mechanics to create even more interactive components:

- **`box-shadow` dynamic styling:** I want to practice animating hard shadows to create micro-interactions like responsive click behaviors without causing layout shifting.
- **`focus-visible` styling patterns:** I plan to build highly customized visual indicator rings that perfectly fit dark/light layout variations while fully maintaining proper web accessibility contrasts.

### AI Collaboration

I collaborated with an AI assistant to streamline my development workflow and improve my component architecture.
- **Tools used:** Gemini (AI Assistant)
- **How I used it:** I used the AI to review my custom stylesheet structure, brainstorm best-practice methods for embedding local font configurations, and optimize my grid spacing strategy.
- **What worked well:** The AI was highly effective in verifying my style guide compliance and providing immediate feedback on semantic element selectors, allowing me to complete the card with highly polished CSS.

## Author

- Frontend Mentor - [@k-uematsu-1247](https://www.frontendmentor.io/profile/k-uematsu-1247)
