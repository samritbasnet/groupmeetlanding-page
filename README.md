# Frontend Mentor - Meet landing page solution

This is a solution to the [Meet landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/meet-landing-page-rbTDS6OUR). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./starter-code/Screenshot%20.png)

### Links

- Solution URL: [Github](https://github.com/samritbasnet/groupmeetlanding-page)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

I learned about use of CSS variables were utilized to create a consistent color scheme throughout the design.
Flexbox and Grid layouts were implemented to create responsive designs that adapt to different screen sizes.
Media queries were used to ensure the layout adjusts appropriately for mobile, tablet, and desktop views.

To see how you can add code snippets, see below:`

```css
.divider {
  display: flex;
  flex-direction: column;
  align-items: center;
  margin-bottom: 64px;
}

.number {
  width: 56px;
  height: 56px;
  border-radius: 50%;
  background-color: white;
  border: 1px solid rgba(135, 135, 157, 0.25);
  display: flex;
  justify-content: center;
  align-items: center;
  font-weight: 900;
}
.feature-images {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 30px;
  margin-bottom: 80px;
}

@media (max-width: 375px) {
  .cta-buttons {
    flex-direction: column;
  }

  .feature-images {
    grid-template-columns: 1fr;
  }
}
```

## Author

- Frontend Mentor - [@Samritbasnet](https://www.frontendmentor.io/profile/samritbasnet)
- Twitter - [@SamritBasnet](https://www.twitter.com/SamritBasnet70)
