## Overview
This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid

### What I learned

I learnt how to use the grid layout, it was difficult to figure out how to center the first and fourth card. 

.grid-container{
  display: grid;
  gap: 10px;
  grid-template-columns: 1fr 1fr 1fr;
  justify-content: center;
  align-content: center;
  margin: 0 auto;
  width: 940px;
  margin-top: 30px;
  padding: 10px;

  .supervisor,.calculator{
  width: 300px;
  align-self: center;
}