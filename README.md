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

(./screenshot_1.png)
(./screenshot_2.png)

### Links

- Solution URL: [https://github.com/evenrise01/frontend-mentor-social-links-profile]
- Live Site URL: [https://evenrise01.github.io/frontend-mentor-social-links-profile/]

## My process
1. Analyze the Design:
Goal: Recreate a clean, mobile-friendly profile card design that adheres to modern UX principles.
Breakdown:
A circular image placed at the top center, slightly overlapping the card.
Clean hierarchy: Name, location, description, and action buttons.
Proper spacing, padding, and alignment to maintain a visually appealing layout.
Consistent font styles, button sizes, and color scheme to ensure harmony.

2Responsive Design: Ensured that the layout is responsive and adaptive to different screen sizes.
Reusable Code:
Created consistent styles using variables (--color-variable-*).
Simplified button styling under a unified class.
Semantic Accuracy:
Replaced <div> buttons with <a> tags, making them more meaningful for navigation links.

3.  Test and Iterate:
After making changes, I mentally walked through the design again to ensure:
Spacing and proportions looked balanced.
The design aligned with the original goal.
Code was clean, modular, and easy to maintain.


Here's my thought process in tackling the challenge of improving your design implementation:

1. Analyze the Design:

Goal: Recreate a clean, mobile-friendly profile card design that adheres to modern UX principles.
Breakdown:
A circular image placed at the top center, slightly overlapping the card.
Clean hierarchy: Name, location, description, and action buttons.
Proper spacing, padding, and alignment to maintain a visually appealing layout.
Consistent font styles, button sizes, and color scheme to ensure harmony.


2. Implement Incremental Changes:
Image (Avatar):

Made the image circular with border-radius: 50% and ensured responsiveness with object-fit: cover.
Positioned the image to overlap the top of the card (margin-top: -48px) for a polished look.
Added a subtle shadow and border for contrast.
Card Layout:

Increased the card width and added a box-shadow for depth.
Adjusted padding to ensure proper spacing around content, including more bottom padding for buttons.
Typography:

Adjusted font sizes to better match the hierarchy (e.g., larger name, smaller location).
Styled the description text with an italic and lighter color for contrast.
Buttons:

Reorganized buttons under a common .button class for reusability.
Ensured proper alignment and spacing (display: block) for vertical stacking.
Added hover effects for interactivity.

3. Prioritize Usability and Reusability:
Responsive Design: Ensured that the layout is responsive and adaptive to different screen sizes.
Reusable Code:
Created consistent styles using variables (--color-variable-*).
Simplified button styling under a unified class.
Semantic Accuracy:
Replaced <div> buttons with <a> tags, making them more meaningful for navigation links.

4. Test and Iterate:
After making changes, I mentally walked through the design again to ensure:
Spacing and proportions looked balanced.
The design aligned with the original goal.
Code was clean, modular, and easy to maintain.

### Key Design Principles Followed:
Hierarchy: Organized the layout to make the name, location, and buttons stand out visually.
Consistency: Used uniform font sizes, button padding, and color schemes.
Responsiveness: Ensured the card looks good across varying screen sizes.
Simplicity: Avoided unnecessary complexity for clean and efficient code.
### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox


### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

I learned the following from this project: 

1. CSS variables: Using the colors in custom variables helped to reduce the typing redundancy and less errors in the code overall
2. Responsiveness: Using the CSS properties to correctly scale the image and the buttons to make sure the design doesn't break when viewing on a phone.
3. Flexbox: Using the flexbox to correctly align items in the center.
4. Adding interactivity to the buttons using the hover state


The below code snippet helped me place the image correctly-
```css
 .avatar {
    border-radius: 50%; /* Ensures the image is perfectly circular */
    width: 96px;
    height: 96px; /* Ensures consistent circular dimensions */
    object-fit: cover; /* Ensures the image scales properly */
    margin-top: 4px; 
    border: 4px solid var(--color-variable-mediumgrey); /* Added border to blend with card */
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1); 
  }
```

## Author

- Website - [Daksh Singh](https://www.your-site.com)
- Frontend Mentor - [evenrise01](https://www.frontendmentor.io/profile/evenrise01)

