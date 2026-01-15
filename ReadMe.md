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
```

The countdown uses the visitor’s local time zone by default.

## 🔮 Planned Enhancements & Optimizations

The following improvements are planned to expand this project beyond a basic countdown into a polished, reusable, and production-ready static event site.

### 🎨 Visual & Design Enhancements
- [ ] Implement a theme system using CSS variables (e.g., pink/gold, pastel, elegant black)
- [ ] Improve typography with curated font pairings (decorative headers + readable body)
- [ ] Add background image support with gradient overlays
- [ ] Introduce subtle glow and pulse effects for countdown numbers
- [ ] Support seasonal or event-based visual modes (balloons, sparkles, confetti)

### 🎉 Animation & Interaction
- [ ] Add flip-clock or smooth number transition animations
- [ ] Implement microinteractions for hover and focus states
- [ ] Create a celebration sequence when the countdown reaches zero
- [ ] Add optional confetti or fireworks animation at event start
- [ ] Respect user motion preferences (`prefers-reduced-motion`)

### 📱 User Experience & Accessibility
- [ ] Optimize layout for small screens and vertical orientations
- [ ] Add ARIA labels and improve screen reader compatibility
- [ ] Implement high-contrast and reduced-motion modes
- [ ] Improve keyboard navigation and focus states
- [ ] Ensure color contrast meets WCAG guidelines

### 🌍 Localization & Time Handling
- [ ] Add English / Spanish language toggle
- [ ] Localize date and time formatting based on locale
- [ ] Lock countdown to a specific event timezone
- [ ] Display event timezone explicitly for remote guests
- [ ] Handle daylight saving time edge cases

### 🧠 JavaScript Architecture Improvements
- [ ] Centralize event configuration in a single config object
- [ ] Modularize countdown logic, UI updates, and animations
- [ ] Reduce global variables and improve encapsulation
- [ ] Optimize DOM updates for performance
- [ ] Add graceful fallbacks for invalid or missing configuration

### 🎶 Media & Content Features
- [ ] Add optional background music with user-controlled playback
- [ ] Include image or photo slideshow support
- [ ] Support captions or event messaging blocks
- [ ] Add optional video embed for invitations or messages

### 🔗 Sharing & Engagement
- [ ] Add “Add to Calendar” functionality (Google / Apple / Outlook)
- [ ] Generate shareable links or QR codes
- [ ] Add social media preview metadata (Open Graph / Twitter Cards)
- [ ] Create share buttons for messaging platforms

### 🚀 Deployment & Performance
- [ ] Optimize animations and assets for GitHub Pages hosting
- [ ] Add basic service worker for offline support
- [ ] Cache static assets for faster repeat visits
- [ ] Improve load performance on low-power mobile devices

### 📚 Documentation & Portfolio Polish
- [ ] Add screenshots and animated GIFs to README
- [ ] Provide customization examples and templates
- [ ] Document configuration options clearly
- [ ] Add multiple demo themes or example pages
- [ ] Maintain clean, descriptive commit history

### 🧪 Quality & Reliability
- [ ] Add basic error handling and user-friendly messages
- [ ] Validate date/time inputs
- [ ] Handle countdown completion edge cases cleanly
- [ ] Test across major browsers and devices