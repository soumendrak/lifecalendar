<div align="center">

# Lifecalendar

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-brightgreen?style=flat-square)](https://soumendrak.github.io/lifecalendar/)
[![MIT License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)](LICENSE)
[![HTML5](https://img.shields.io/badge/HTML5-%23E34F26?style=flat-square&logo=html5&logoColor=white)](https://html.spec.whatwg.org/)
[![Zero Dependencies](https://img.shields.io/badge/dependencies-0-success?style=flat-square)](https://www.w3.org/TR/html52/)

<!-- Inline SVG logo -->
<svg width="140" height="140" viewBox="0 0 140 140" xmlns="http://www.w3.org/2000/svg">
<rect width="140" height="140" rx="24" fill="#0a0a14"/>
  <rect x="16" y="30" width="108" height="80" rx="4" fill="#0d0d1a"/>
  <rect x="19" y="33" width="8" height="8" rx="1" fill="#ff6b35"/>
  <rect x="29" y="33" width="8" height="8" rx="1" fill="#ff6b35"/>
  <rect x="39" y="33" width="8" height="8" rx="1" fill="#ff6b35"/>
  <rect x="49" y="33" width="8" height="8" rx="1" fill="#ff6b35"/>
  <rect x="19" y="43" width="8" height="8" rx="1" fill="#ff6b35"/>
  <rect x="29" y="43" width="8" height="8" rx="1" fill="#ff6b35"/>
  <rect x="39" y="43" width="8" height="8" rx="1" fill="#1a1a2e"/>
  <rect x="49" y="43" width="8" height="8" rx="1" fill="#1a1a2e"/>
  <text x="70" y="130" text-anchor="middle" font-family="sans-serif" font-size="9" fill="#8a8a9a">YOUR LIFE IN WEEKS</text>
</svg>

**A 90-year grid where each week of your life is one tiny box — existential but motivating.**

**Live:** [https://soumendrak.github.io/lifecalendar/](https://soumendrak.github.io/lifecalendar/)

</div>

---

## Features

- 90-year × 52-week grid = 4,680 individual boxes
- Age slider (0-100) and number input
- Lived weeks shown in orange, remaining dim
- Hover tooltip: 'Year X, Week Y'
- Stats panel: years/weeks lived, years/weeks left
- 'You have used X% of your life' metric
- Dark theme with orange accent (#ff6b35)

## How It Works

A grid of DIVs is generated via JavaScript: 90 rows (years) × 52 columns (weeks). Each cell is a tiny `<div>` with border-radius. Given an age, cells up to `age × 52` are filled orange, the rest stay dim. Hover events use mouseenter to show a tooltip with the year/week coordinate. Stats update on slider change.

## Usage

1. Open `https://soumendrak.github.io/lifecalendar/` in any browser.
2. No build step, no installation, no server required.
3. Deploy anywhere — GitHub Pages, Netlify, or any static host.

```bash
git clone https://github.com/soumendrak/lifecalendar.git
# Open index.html directly
```

## License

Licensed under the [MIT License](LICENSE).

---

<p align="center"><sub>Built with ❤️ and zero dependencies</sub></p>
