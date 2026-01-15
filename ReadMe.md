# 🎉 Quinceañera Countdown Website

A fully client-side, animated countdown website built to celebrate a Quinceañera by counting down the days, hours, minutes, and seconds until the event. Designed to be visually festive, mobile-friendly, and easy to deploy using GitHub Pages.

This project demonstrates clean HTML/CSS structure, real-time JavaScript date calculations, lightweight animations, and static-site hosting best practices.

---

## ✨ Features

- ⏳ **Live countdown timer**
  - Displays days, hours, minutes, and seconds remaining
  - Updates every second using JavaScript
- 📅 **Human-readable event date**
  - Automatically formatted from a single date configuration
- 🎈 **Festive animated UI**
  - Floating pastel balloons using pure CSS + JS
  - Hover animations for countdown elements
- 📱 **Responsive design**
  - Looks great on mobile, tablet, and desktop
- 🌐 **Static & fast**
  - No backend, no frameworks, no dependencies
- 🚀 **Free hosting via GitHub Pages**

---

## 🛠️ Technologies Used

- **HTML5**
  - Semantic structure
  - Single-file deployment
- **CSS3**
  - Flexbox layout
  - Gradients, shadows, hover effects
  - Keyframe animations
- **Vanilla JavaScript**
  - Date/time calculations
  - DOM manipulation
  - Interval-based updates
- **GitHub Pages**
  - Static site hosting

---

## 📂 Project Structure
quince/
├── index.html # Entire website (HTML, CSS, JS)
└── README.md # Project documentation


This project intentionally uses a **single-file architecture** to keep deployment and maintenance simple.

---

## ⚙️ Configuration

To customize the countdown for a specific event, update **one line** in `index.html`:

```js
const quinceDate = new Date("2026-06-15T18:00:00");

The countdown uses the visitor’s local time zone by default.