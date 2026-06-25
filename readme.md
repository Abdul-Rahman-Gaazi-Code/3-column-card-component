# 3-column-card-component



A 3-column card component built from scratch using HTML, and CSS. Each card represents a vehicle category — Sedans, SUVs, and Luxury — with icons, descriptions, hover buttons, and a dark mode toggle.

---

## What I Built

Three cards sitting side by side, each with its own background color, an SVG icon positioned relative to a dark circle, a heading, a short description, and a Learn More button.

---

## Lessons Learnt

**Semantic HTML makes your code readable**
Using tags like `<section>`, `<ol>`, `<li>`, and `<article>` instead of divs everywhere gave the markup real meaning and made it easier to navigate.

**Flexbox handles layout in two directions**
I used `display: flex` on the cards to line the cards up horizontally, and `flex-direction: column` inside each card to stack the content vertically with even spacing.

**Buttons have default browser styles that fight you**
A button stretches to fill its container by default. Setting `width: fit-content` and controlling padding manually was the fix.

**CSS filters change SVG colors without touching the file**
`filter: brightness(0) invert(1)` turns any dark icon white instantly. No need to open the SVG and edit the fill.

**Wrapping icons in a div gives you full control**
Putting the image inside a circle div and centering it with flexbox made it easy to control the circle and icon sizes independently, and gave a cleaner result than padding the image directly.

**Hover states make interactions feel alive**
Each button changes to its card's background color on hover with a smooth transition using `transition: background-color 0.3s ease, color 0.3s ease`.

**CSS filters change SVG colors without touching the file**
`filter: brightness(0) invert(1)` turns any dark icon white instantly. No need to open the SVG and edit the fill.

**`rgba` for subtle transparency**
Using `rgba(0, 0, 0, 0.4)` for the icon circle background blends naturally with each card color instead of clashing with a solid color.

## Tech Used

- HTML5
- CSS3
- Google Fonts (Big Shoulders, Roboto)

---
