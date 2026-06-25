# Vehicle Category Cards

A simple frontend component built with HTML and CSS — three cards sitting side by side, each representing a vehicle category: Sedans, SUVs, and Luxury.

---

## What I Built

A fixed 3-column card layout using flexbox. Each card has its own background color, an icon inside a dark circle, a heading, a short description, and a Learn More button. No JavaScript, no frameworks — just HTML and CSS.

---

## Lessons Learnt

**Semantic HTML matters**
I used `<section>`, `<ol>`, `<li>`, and `<article>` instead of just throwing everything into divs. It made the structure cleaner and easier to read.

**Flexbox for layout**
`display: flex` on the parent lined the three cards up side by side. I also used flexbox inside each card with `flex-direction: column` and `justify-content: space-evenly` to space out the content vertically.

**Buttons have default browser styles**
A button stretches full width by default. I had to set `width: fit-content` and `padding: 0 2rem` to get it to wrap tightly around the text.

**CSS filters for icon color**
I used `filter: brightness(0) invert(1)` to turn dark SVG icons white without editing the actual SVG files.

**Positioning is relative to the element itself**
Using `position: relative` with `left` moves the element from where it naturally sits, not from the page. I used this to shift the icon slightly inside the circle.

**Wrapping icons in a div gives you more control**
Instead of styling the image directly, I wrapped it in a `div` and used flexbox to center it. This made it easy to control the circle size and icon size independently.

**`object-fit: contain` keeps images from distorting**
When I gave the image a fixed width and height, it was stretching. `object-fit: contain` kept the aspect ratio intact.

**CSS custom colors with rgba**
Using `rgba(0, 0, 0, 0.4)` instead of a solid color gave the icon background a see-through dark tint that blends nicely with each card color.

---

## Tech Used

- HTML5
- CSS3
- Google Fonts (Big Shoulders, Roboto)

---

