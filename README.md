# Dev Meki – Professional Software Developer Portfolio

A high-performance, visually stunning, single-page portfolio designed for modern software developers. Built with **HTML5**, **Vanilla JavaScript**, and **Tailwind CSS**.

## Key Features

- **Dynamic Hero Section**: featuring a sleek **Typewriter Effect** and interactive social links.
- **Infinite Tech Marquee**: A seamless, high-speed scrolling track showcasing a wide array of technical skills.
- **Micro-Animations**: Custom **Per-letter Wave Animations** on headers for a playful, liquid-like feel.
- **Responsive Off-canvas Navigation**: A polished mobile sidebar with glassmorphism and smooth transition effects.
- **Interactive Project Showcase**: Stylish project cards with glassmorphism, hover-zoom effects, and tech tag badges.
- **Dark Mode Contact Section**: A premium, high-contrast footer/contact section with subtle radial glow backgrounds.
- **Optimized Performance**: Zero build step required—leveraging Tailwind CSS Play CDN and optimized assets.

## Tech Stack

- **Frontend**: HTML5, Tailwind CSS, Vanilla JavaScript
- **Backend (Compatible)**: PHP, MySQL
- **Design Patterns**: Mobile-First, Responsive Design, Glassmorphism
- **Iconography**: DevIcon (SVG-based)

## Getting Started

### Prerequisites

A modern web browser (Edge, Chrome, Firefox, Safari).

### Usage

1. Clone the repository.
2. Open `index.html` directly in your browser.
3. For local development with live updates, use an extension like **Live Server** in VS Code.

## Customization

### 1. Branding & Name

Search for `Dev Meki` in `index.html` to update the site title, navbar logo, and hero section.

### 2. Tailwind Configuration

The site's visual theme and custom animations are controlled via the `tailwind.config` script at the top of the file:

```javascript
tailwind.config = {
  theme: {
    extend: {
      colors: {
        primary: "#1e3a8a", // Brand Blue
        accent: "#f59e0b", // Brand Amber
        dark: "#0f172a", // Background Dark
      },
      animation: {
        marquee: "marquee 15s linear infinite", // Adjust speed here
        "wave-bounce": "wave-bounce 4s ease-in-out infinite",
      },
    },
  },
};
```

### 3. Adding Projects

Navigate to the `<section id="projects">` and duplicate the `<article>` blocks. Replace the images, titles, and descriptions as needed.

---

_Hand-crafted by Dev Meki_
