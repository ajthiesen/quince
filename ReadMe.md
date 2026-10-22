# Quinceañera Countdown Website

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub Pages](https://img.shields.io/badge/Hosted%20With-GitHub%20Pages-blue.svg)](https://pages.github.com/)

**Quinceañera Countdown** is a fully client-side, lightweight, and animated static web application engineered to celebrate and count down the days, hours, minutes, and seconds leading up to a Quinceañera. Designed with a festive aesthetic, smooth CSS/JS animations, and a mobile-first responsive layout, it requires zero server-side dependencies and deploys instantly via GitHub Pages.

---

## Table of Contents

* [Key Features](#key-features)
* [Architecture & Single-File Design](#architecture--single-file-design)
* [Technologies Used](#technologies-used)
* [Configuration](#configuration)
* [Deployment](#deployment)
* [Planned Roadmap & Enhancements](#planned-roadmap--enhancements)
* [Contributing](#contributing)
* [License](#license)

---

## Key Features

* **Real-Time Precision Timer**: Calculates days, hours, minutes, and seconds remaining using client-side JavaScript updated on a strict 1-second interval.
* **Automated Date Formatting**: Renders a human-readable event date automatically derived from the target JavaScript configuration.
* **Pure CSS & Vanilla JS Animations**: Dynamic floating pastel balloons and responsive UI microinteractions built without heavy external animation libraries.
* **Zero-Dependency Single-File Architecture**: Built completely with vanilla HTML5, CSS3, and JavaScript—no frameworks, build steps, or npm packages required.
* **Fully Responsive**: Mobile-first design tailored for optimal display across smartphones, tablets, and desktop displays.
* **GitHub Pages Native**: Designed specifically for zero-cost static hosting and instantaneous deployment.

---

## Architecture & Single-File Design

The repository intentionally enforces a minimal **Single-File Architecture** (`index.html`) containing the semantic HTML layout, CSS stylesheet rules, and vanilla JavaScript engine. This keeps maintenance lightweight, prevents dependency bloat, and makes static site hosting effortless.

```
quince/
├── index.html        # Unified application (HTML layout, CSS styling, JS engine)
├── LICENSE           # Open-source license terms
└── README.md         # Technical documentation
```

### Application Flow

```
+-------------------------------------------------------+
|                    index.html                         |
+-------------------------------------------------------+
                           |
            +--------------+--------------+
            |                             |
            v                             v
+-----------------------+     +-----------------------+
|  CSS Engine           |     |  JavaScript Core      |
|  - Keyframe Floating  |     |  - Date Calculation   |
|  - Responsive Layout  |     |  - Interval Updates   |
|  - Hover States       |     |  - DOM Manipulation   |
+-----------------------+     +-----------------------+
                                          |
                                          v
                              +-----------------------+
                              | Render Live Countdown |
                              +-----------------------+
```

---

## Technologies Used

* **HTML5**: Semantic web markup for accessibility and efficient DOM parsing.
* **CSS3**: Flexbox layout modeling, gradient overlays, box shadows, and native `@keyframes` keyframe animations.
* **Vanilla JavaScript (ES6+)**: Local timezone handling, DOM selection, and interval-driven date arithmetic.
* **GitHub Pages**: Free static site hosting and continuous deployment directly from the repository main branch.

---

## Configuration

To customize the website for a specific event, modify the single target date string in **`index.html`**:

```javascript
// Set the target Quinceañera event date and time (ISO format)
const quinceDate = new Date("2026-06-15T18:00:00");
```

> **Note**: The countdown automatically interprets the target string and evaluates the remaining time against the visitor's local system timezone.

---

## Deployment

### Deploying to GitHub Pages

1. Fork or clone this repository:
   ```bash
   git clone https://github.com/ajthiesen/quince.git
   cd quince
   ```
2. Push your changes to your GitHub repository.
3. In your GitHub repository, navigate to **Settings** > **Pages**.
4. Under **Build and deployment** > **Source**, select `Deploy from a branch`.
5. Select the `main` branch and `/ (root)` folder, then click **Save**.
6. Your website will be live at `https://<your-username>.github.io/quince/`.

---

## Planned Roadmap & Enhancements

Below is the structured technical roadmap for expanding the project into a multi-theme, fully customizable event platform.

### 🎨 Visual & Design Enhancements
- [ ] **CSS Variable Theme System**: Support interchangeable color palettes (e.g., Pink/Gold, Royal Blue, Pastel Lavender, Elegant Black).
- [ ] **Curated Typography**: Introduce Google Fonts integrations (decorative headers paired with high-readability body fonts).
- [ ] **Dynamic Visual Modes**: Add toggleable seasonal visual overlay effects (sparkles, confetti, or balloons).

### 🎉 Animation & Interaction
- [ ] **Flip-Clock Animations**: Smooth numerical transitions on second/minute updates.
- [ ] **Event Start Celebration**: Trigger a high-impact celebration sequence (confetti/fireworks canvas explosion) when the timer reaches zero.
- [ ] **Accessibility Motion Limits**: Respect `prefers-reduced-motion` CSS media queries.

### 🌐 Accessibility & Localization
- [ ] **Bilingual Support**: Instant toggle between English and Spanish language localization.
- [ ] **Timezone Pinning**: Option to lock the target timezone explicitly rather than defaulting to client local time.
- [ ] **WCAG Compliance**: High-contrast modes and screen reader ARIA live region updates.

### 🔗 Engagement & Integrations
- [ ] **Calendar Export**: "Add to Calendar" action buttons for Google, Apple, and Outlook calendars.
- [ ] **Social Sharing**: Pre-configured Open Graph metadata tags for rich link previews across messaging apps and social platforms.

---

## Contributing

Contributions, bug reports, and design suggestions are welcome!

1. Fork the Repository.
2. Create your Feature Branch (`git checkout -b feature/NewFeature`).
3. Commit your Changes (`git commit -m 'Add NewFeature'`).
4. Push to the Branch (`git push origin feature/NewFeature`).
5. Open a Pull Request.

---

## License

This project is open-source and licensed under the [MIT License](LICENSE).
