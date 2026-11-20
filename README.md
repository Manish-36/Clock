# Analog Clock

A clean, real-time analog clock web application built with vanilla HTML, CSS, and JavaScript that displays the current time using rotating hour, minute, and second hands.

## Preview

<img width="1917" height="846" alt="Screenshot 2026-11-20 194229" src="https://github.com/user-attachments/assets/c672e3e2-db9b-40a0-8df3-0986050219a7" />

## Features

* **Real-Time Hand Rotation:** Dynamically calculates rotation angles (`deg`) for the hour, minute, and second hands using JavaScript `Date` values and updates every second via `setTimeout`.
* **Classic Clock Face Layout:** Features a circular `350px x 350px` light grey dial with a dark grey border, cardinal markers (`12`, `3`, `6`, `9`), a dark green center pivot (`::before`), and a logo image near the top.
* **Distinct Hands Styling:** Includes a shorter hour hand, a standard minute hand, and a goldenrod second hand anchored from the bottom center (`transform-origin: bottom center`)[cite: 10].
* **Centered Full-Viewport UI:** Styled with Flexbox over a `salmon` background using monospaced typography[cite: 10].

---

## Project Structure

```text
├── index.html      # Clock dial markup, hour markers, hands, and logo image
├── style.css       # Circular clock styling, hand rotations, and Flexbox centering
├── index.js        # Time calculation, angle conversion, and recursive timer loop
└── preview.png     # Application screenshot for the README
