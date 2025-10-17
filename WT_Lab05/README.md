# Lab 05 – CSS Layout Techniques & Responsive Design

**Course:** CS 224L – Web Technologies  
**Instructor:** Mr. Mohammad  
**Department of Computer Science, UET Peshawar**

---

## Learning Outcomes

After completing this lab, students should be able to:

- Use different CSS display properties effectively  
- Create web layouts using floats, Flexbox, and CSS Grid  
- Understand and apply different positioning types in CSS  
- Design responsive layouts using media queries  
- Follow a mobile-first approach for modern web design  
- Handle layout challenges and browser compatibility issues  

---

## Background

This lab focuses on practical CSS layout techniques that are used in modern web development.  
You’ll learn how different display and positioning methods affect page structure, and how to build responsive designs that adjust across various screen sizes.

### Key Concepts:
- **Display Property:** Defines how elements appear on a webpage (block, inline, inline-block, etc.)
- **Float Layouts:** Used to align elements horizontally, like columns or images with text.
- **Positioning:** Allows precise control of where elements appear on the screen.
- **Flexbox:** Makes it easier to align and distribute space within a container.
- **CSS Grid:** A two-dimensional layout system for creating more complex and responsive designs.
- **Media Queries:** Used to make websites responsive across different devices.

---

## Pre-Lab Requirements

Before starting this lab, make sure you:
- Have completed **Lab 03 and Lab 04 (CSS Fundamentals)**  
- Understand **CSS selectors**, **properties**, and the **box model**  

---

## Lab Exercises Overview

### Part A – Display Property
Practice the basic display values like block, inline, inline-block, and none.  
Try using them in navigation menus and simple layouts.

### Part B – Float-Based Layouts
Create two- and three-column layouts using floats.  
Learn to fix float collapsing using clearfix and make them responsive.

### Part C – CSS Positioning
Work with static, relative, absolute, fixed, and sticky positioning.  
You’ll also create overlapping elements, modals, and sticky headers.

### Part D – Flexbox Layout
Explore Flexbox properties such as `flex-direction`, `justify-content`, and `align-items`.  
Use them to create navigation bars and responsive card layouts.

### Part E – CSS Grid Layout
Learn grid container and item properties.  
Build responsive galleries and page sections using Grid.

### Part F – Media Queries & Responsive Design
Use media queries to make designs adapt to mobile, tablet, and desktop screens.  
Practice responsive images using the `srcset` and `picture` elements.

### Part G – Combining Layout Techniques
Mix Flexbox, Grid, and float layouts to create advanced responsive designs.

---

## Lab Tasks Summary

| Task | Description |
|------|--------------|
| **Task 1** | Demonstrate different display properties with responsive behavior |
| **Task 2** | Create a float-based magazine-style layout |
| **Task 3** | Build a page using various positioning methods |
| **Task 4** | Develop a responsive navigation bar using Flexbox |
| **Task 5** | Create responsive and equal-height card layouts |
| **Task 6** | Design a responsive photo gallery using CSS Grid |
| **Task 7** | Implement the Holy Grail layout using Float, Flexbox, and Grid |
| **Task 8** | Build an e-commerce product grid with responsive breakpoints |
| **Task 9** | Create an admin dashboard using both Grid and Flexbox |
| **Task 10** | Show media query effects for different screen sizes |

---

## Advanced Tasks

- **Task 11:** Build a complex CSS Grid magazine layout  
- **Task 12:** Create a Flexbox-based form layout that adapts to screen size  
- **Task 13:** Make a portfolio layout combining Grid, Flexbox, and positioning  
- **Task 14:** Design a responsive data table  
- **Task 15:** Create a mobile-first landing page with responsive images and typography  

---

## Media Query Practice

Common responsive breakpoints:

```css
/* Mobile First */
@media (min-width: 768px) { /* Tablet */ }
@media (min-width: 1024px) { /* Small Desktop */ }
@media (min-width: 1200px) { /* Large Desktop */ }
@media (min-width: 1400px) { /* Extra Large */ }
