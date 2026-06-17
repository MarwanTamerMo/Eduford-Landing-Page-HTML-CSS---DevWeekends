<div align="center">

# 🎓 Eduford University

### *World's Biggest University — Landing Page*

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Font Awesome](https://img.shields.io/badge/Font_Awesome_6-528DD7?style=for-the-badge&logo=fontawesome&logoColor=white)](https://fontawesome.com/)
[![Google Fonts](https://img.shields.io/badge/Google_Fonts-4285F4?style=for-the-badge&logo=google&logoColor=white)](https://fonts.google.com/)

> A clean, responsive university landing page built with pure HTML, CSS & JavaScript — crafted during **DevWeekends**.

---

</div>

## ✨ Features

- 🏠 **Hero Section** — Fullscreen banner with overlay and a clear call-to-action
- 📚 **Courses Section** — Cards for Computer Science, Engineering, and Business
- 🌍 **Global Campus** — Interactive hover-reveal campus images (London, New York, Washington)
- 🏛️ **Facilities** — Library, Playground, and Cafeteria highlights
- 💬 **Student Testimonials** — Real student reviews with star ratings (full, half & empty stars)
- 📣 **Call to Action** — Full-width banner encouraging enrollment
- 🔗 **Footer** — Social media links + credits
- 📱 **Responsive Design** — Mobile-friendly with a smooth sliding hamburger menu

---

## 🖼️ Sections Overview

| Section | Description |
|---|---|
| **Navigation** | Logo + links + animated hamburger menu for mobile |
| **Hero** | Full-page background with headline & CTA button |
| **Courses** | 3-column card layout with hover shadow effect |
| **Campus** | Image gallery with red overlay + city name reveal on hover |
| **Facilities** | Icon-rich content blocks for library, sports & dining |
| **Testimonials** | Student cards with avatar, review text & star ratings |
| **CTA Banner** | Dark overlay banner with enrollment prompt |
| **Footer** | Social icons (Facebook, Twitter, Instagram, LinkedIn) |

---

## 🗂️ Project Structure

```
Eduford-Landing-Page/
│
├── index.html          # Main HTML file with all page sections
├── style.css           # All styles — layout, components, responsive
│
└── eduford_img/        # All image assets
    ├── logo.png
    ├── banner.png
    ├── banner2.jpg
    ├── london.png
    ├── newyork.png
    ├── washington.png
    ├── library.png
    ├── basketball.png
    ├── cafeteria.png
    └── ...
```

---

## 🚀 Getting Started

No build tools, no dependencies — just open and run!

```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/Eduford-Landing-Page-HTML-CSS---DevWeekends.git

# Navigate into the project
cd Eduford-Landing-Page-HTML-CSS---DevWeekends

# Open in browser
open index.html
# or just double-click index.html in your file explorer
```

---

## 📱 Responsive Behaviour

| Viewport | Layout |
|---|---|
| **Desktop (> 700px)** | Full nav links visible, 3-column grid layouts |
| **Mobile (≤ 700px)** | Hamburger menu with sliding drawer, single-column stacked layout |

The mobile menu slides in smoothly from the right side and is dismissed with the ✕ close button.

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| **HTML5** | Page structure and semantic markup |
| **CSS3** | Flexbox layouts, transitions, hover effects, media queries |
| **Vanilla JavaScript** | Mobile menu toggle (show/hide) |
| **Font Awesome 6** | Icons — menu, close, stars, social media, heart |
| **Google Fonts (Roboto)** | Typography |

---

## 🎨 Design Highlights

- **Color Palette:** Deep Red `#f44336` accent on a clean white base
- **Hover Effects:** Underline animation on nav links, shadow lift on course cards, red overlay reveal on campus images
- **Smooth Transitions:** 0.5s CSS transitions on menu, overlay, and card interactions
- **Typography:** Roboto font with varied weights for hierarchy

---

## 🐛 Bugs Fixed During Development

- ✅ Mobile hamburger icon was hidden (was nested inside the off-screen nav drawer)
- ✅ FontAwesome icon classes updated from deprecated v4/v5 (`fa-star-o`, `fa-star-half-o`) to v6 (`fa-regular fa-star`, `fa-star-half-stroke`)
- ✅ Footer social icons color not applying (fixed from `.fa` to `.fa-brands` selector)
- ✅ Background image paths changed from absolute to relative for cross-environment compatibility
- ✅ Testimonial boxes spacing fixed with `box-sizing: border-box`

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

<div align="center">

Made with ❤️ during **DevWeekends**

*Built by the Eduford Team*

</div>