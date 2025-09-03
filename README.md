# Frontend Mentor -  Testimonials Grid Solution🔗
This is my solution to the [Testimonials Grid challenge](https://testimonial-grid-omega.vercel.app/) on Frontend Mentor.

## Overview ✨

### The Challenge

The challenge was to build a responsive grid of testimonials that closely matches the provided design for both desktop and mobile layouts. Key requirements included:

- Creating a responsive grid layout that adapts to different screen sizes.
- Replicating the unique card styles, including background colors, quote marks, and typography.
- Ensuring the content is semantically structured and accessible.

### Preview

![Screenshot](./images/preview.jpg) 

## 🛠️ Technologies Used
- **HTML5** - For the semantic structure of the testimonial cards and overall page.
- **CSS3** - For styling the layout, typography, and visual effects.
- **CSS Grid** - This was the primary tool used to create the complex two-dimensional layout for the testimonials on desktop.
- **Flexbox** - Used within each card to align the user's profile picture and name.
- **Media Queries** - Essential for creating the responsive layout that shifts from a grid to a single column on smaller screens.

## My Process 🛠️
### 1. HTML Structure 📋
- I created a main `<main>` container to hold all the testimonial cards. 
- A `<div>` for the user's profile information, containing their `<img>` and another `<div>` for their `<h2>` name and `<h3>` verified status.

### 2. Styling 🎨
- **Mobile-first approach** 📱 I started by styling for the mobile layout, which is a simple column. This made it easier to build the more complex desktop grid later with media queries.
- **Layout with CSS Grid**: I used CSS Grid on the `<main>` container to create the desktop layout. grid-template-areas was used to place each testimonial card precisely in the grid, which was key to achieving the staggered design. The first testimonial was designed to span two columns using grid-column: span 2.
- **Card Styling** : A box-shadow was applied to create the lifted effect. The quote marks were added using a background image and background-position on the first testimonial card.
- **Typography** : I imported and applied the correct fonts (Barlow Semi Condensed) and adjusted font-size, line-height, and color to match the design.

## 📚 What I Learned

- **Mastering CSS Grid** : This project was an excellent opportunity to practice and solidify my understanding of grid-template-columns, grid-template-rows, and grid-area. Using named grid areas made the layout structure much more readable and maintainable.
- **Responsive Design** : I gained further experience in how to transition a complex grid layout into a simple, single-column flex or grid layout for mobile devices using media queries.


## 🔗 Links
- **🌐 Live Site URL**:  [Testimonials Grid challenge](https://testimonial-grid-omega.vercel.app/) 

### **👥 Solved by M Olaya** 
<a href="https://www.linkedin.com/in/molaya">LinkedIn</a> 
