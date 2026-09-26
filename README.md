# Web_Development_2026

A collection of standalone HTML/CSS practice projects built as part of my full-stack development learning journey.

## Overview

This repository represents the frontend stage of a broader full-stack development learning journey and is a personal practice space for core CSS concepts. Each folder is an independent, self-contained HTML file (styles are written inline in a `<style>` tag) rather than a single connected application. The pages cover common UI patterns: a product/cart card, a "coming soon" landing page, a login form, and three different navigation bar styles. There is no shared navigation between pages and no backend — every page is meant to be opened and viewed on its own.

## Features

- **Product / Add-to-Cart card** — a Grand Theft Auto VI–themed product page with a top navbar, product image, discounted price display, and "Add To Cart" / "Buy Now" buttons
- **Coming Soon page** — a centered card with a logo, heading, and an email signup form
- **Login form** — a simple centered card with email and password fields and a login button
- **Three navbar variations**:
  - Horizontal navbar with an animated underline hover effect
  - Vertical sidebar navbar with a background hover effect
  - Horizontal navbar with a dropdown menu on hover
- Responsive layout adjustments (via media queries) on the Add-to-Cart page for tablet and mobile widths
- Hover and transition effects on interactive elements

## Tech Stack

- HTML
- CSS (all styles written inline within each HTML file)
- Google Fonts (`Archivo Black`, `Ramabhadra`, loaded via `@import` on the Add-to-Cart page)

No JavaScript, frameworks, build tools, or backend are used anywhere in this repository.

## Project Structure

```
Web_Development_2026/
└── CSS/
    ├── AddToCart/
    │   ├── index.html      # GTA VI product card with navbar and cart actions
    │   ├── img.jpg          # Product image
    │   └── img2.jpg         # Background image
    ├── ComingSoonPage/
    │   ├── index.html      # Coming soon landing page with email form
    │   └── img.jpg          # Logo image
    ├── Login/
    │   └── index.html      # Login form
    └── NavBar/
        ├── index1.html      # Horizontal navbar, underline hover effect
        ├── index2.html      # Vertical navbar, hover effect
        └── index3.html      # Horizontal navbar with dropdown
```

## Getting Started

These are plain HTML/CSS files with no dependencies or build step. To view a page, just open the corresponding `index.html` file directly in a web browser, for example:

```
CSS/AddToCart/index.html
CSS/ComingSoonPage/index.html
CSS/Login/index.html
CSS/NavBar/index1.html
CSS/NavBar/index2.html
CSS/NavBar/index3.html
```

No installation, server, or package manager is required.

## Usage

Each page is a static UI demo:

- On the **Add-to-Cart** page, the "Add To Cart" and "Buy Now" buttons are styled but not wired to any logic — they don't add items to a cart or trigger a purchase.
- On the **Coming Soon** page, the email form has no submission handler — entering an email and clicking "Notify Me" does not send data anywhere.
- The **Login** form similarly has no authentication logic behind it — it's a UI-only mockup.
- The **NavBar** pages exist purely to demonstrate different navbar styling and hover/dropdown behavior; the links are placeholders (`#`).

## Learning / Concepts Demonstrated

- Flexbox layout (navbars, form and card layouts, the product page's image/text split)
- CSS positioning (`position: absolute`/`relative` for the dropdown menu and image overlay)
- Pseudo-elements (`::before`, `::after`) for background overlays and underline hover effects
- Hover and transition effects on links and buttons
- Linear gradients for backgrounds
- `box-shadow` for card and button depth
- Responsive design via `@media` queries (Add-to-Cart page)
- `object-fit` and `aspect-ratio` for image sizing
- Custom web fonts via `@import` and Google Fonts

## Future Improvements

These are potential next steps and are **not** currently implemented:

- Add JavaScript to make the cart, login, and email signup forms functional
- Extract shared styles into external `.css` files instead of inline `<style>` blocks
- Add a consistent navbar/layout shared across all pages
- Add basic form validation feedback

## Author

**Davik Singh**

GitHub: [github.com/DevSingh-here](https://github.com/DevSingh-here)
