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
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page
- View the optimal layout for the interface depending on their device's screen size

### Screenshot

![](./preview.jpg)

### Links

- Solution URL: [Solution](https://github.com/Axmerko/fm-social-links-profile)
- Live Site URL: [Live site](https://fm-social-links-profile-axmerko.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties (colors, typography)
- Flexbox
- Centered desktop/mobile layout

### What I learned

During this project, I focused heavily on CSS Flexbox and understanding how browser defaults affect element spacing and positioning. 

One of my main takeaways was the importance of explicitly declaring `display: flex` before using layout properties like `flex-direction` or `align-items`. I also learned how to vertically stack inline-block elements like `<button>` and stretch them to fill their parent container using `width: 100%`.

Here are a few code snippets highlighting what I worked on:

```css
/* Centering elements inside the card using Flexbox */
.card {
  background-color: #1f1f1f;
  max-width: 384px;
  width: calc(100% - 48px);
  border-radius: 20px;
  padding: 24px;
  
  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: center;
}

/* Stacking buttons and styling them uniformly */
button {
  width: 100%;
  margin-bottom: 16px;
  padding: 14px;
  background-color: #333333;
  color: white;
  border: none;
  border-radius: 8px;
  font-weight: bold;
  font-family: inherit;
  cursor: pointer;
}

/* Resetting default browser margins on typography for precise spacing */
.card h2 {
  color: #ffffff;
  margin: 0;
  margin-bottom: 8px;
}
```

### Continued development

In future projects, I want to continue refining my CSS layout skills, specifically:
- Deepening my understanding of CSS Flexbox and Grid alignment properties.
- Better managing CSS resets (clearing default browser margins and paddings right at the beginning of a project).
- Implementing smooth transition effects for interactive states (hover, focus, and active styles).

### AI Collaboration

I used an AI assistant as an interactive coding mentor throughout the development of this project.

- **Tools used:** AI Assistant (Gemini)
- **How I used it:** Instead of asking for the final code upfront, I shared my HTML/CSS progress and screenshots, asking specific questions about layout problems I encountered (e.g., how to center elements inside the card, how to stack buttons vertically, and why certain spacing issues occurred).
- **What worked well:** This step-by-step guidance helped me identify a missing `display: flex` property and taught me how to effectively reset default margins on text elements. Treating the AI as a mentor rather than a code generator significantly helped reinforce my understanding of CSS fundamentals.

## Author

- GitHub - [@Axmerko](https://github.com/Axmerko)
- Frontend Mentor - [@Axmerko](https://www.frontendmentor.io/profile/Axmerko)