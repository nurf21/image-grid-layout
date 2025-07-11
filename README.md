# CSS Grid Photo Gallery

A responsive, modern photo gallery built with **HTML** and **CSS Grid**. This project demonstrates how to create complex, non‑rectangular layouts—complete with hover effects, captions, and responsive breakpoints—using only semantic HTML and CSS.

## 🔗 Project URL

[https://roadmap.sh/projects/image-grid](https://roadmap.sh/projects/image-grid)

## 🔍 Demo

<!-- ![Gallery Preview](./assets/demo-screenshot.png) -->

> **Live Demo:** [nurf21.github.io/image-grid-layout](https://nurf21.github.io/image-grid-layout)

---

## 📚 Table of Contents

- [CSS Grid Photo Gallery](#css-grid-photo-gallery)
  - [🔗 Project URL](#-project-url)
  - [🔍 Demo](#-demo)
  - [📚 Table of Contents](#-table-of-contents)
  - [⭐ Features](#-features)
  - [🚀 Getting Started](#-getting-started)
    - [Prerequisites](#prerequisites)
    - [Installation](#installation)
  - [🛠 Usage](#-usage)
  - [🎨 Customization](#-customization)
  - [👏 Credits \& Assets](#-credits--assets)
  - [⚖️ License](#️-license)

---

## ⭐ Features

* **CSS Grid**: Custom grid‑area definitions for a mosaic‑style layout
* **Hover Effects**: Lift & zoom animations on cards and captions
* **Captions**: Semi‑transparent overlay with blur for readability
* **Responsive**:

  * 3‑column layout on desktop
  * 2‑column on tablets
  * 1‑column on mobile
* **Pure CSS & HTML**: No JavaScript required

## 🚀 Getting Started

### Prerequisites

* A modern browser (Chrome, Firefox, Safari, Edge)
* (Optional) Live server extension or local HTTP server for testing

### Installation

1. **Clone the repo**

   ```bash
   git clone https://github.com/nurf21/image-grid-layout
   cd image-grid-layout
   ```

2. **Open**

   * Open `index.html` directly, **or**
   * Start a live server extension

## 🛠 Usage

1. **Edit images**

   * Replace any `*.png` in `/assets/images` with your own images.
   * Make sure file names match those in `index.html`.

2. **Modify grid layout**

   * Open `style.css`
   * Adjust `grid-template-areas`, `grid-template-rows`, or `gap` to experiment.

3. **Customize captions**

   * Change the `<div class="caption">…</div>` text inside each `.grid-item` in `index.html`.

## 🎨 Customization

* **Colors & Shadows**

  * Tweak CSS variables or replace `box-shadow` values in `style.css`.
* **Breakpoints**

  * Adjust the `@media (max-width: …)` queries to suit your target devices.
* **Animation**

  * Change durations in `transition` or swap `transform: scale(…)` values.

## 👏 Credits & Assets

* Photo assets courtesy of [Unsplash](https://unsplash.com/)

## ⚖️ License

This project is open source and available under the [MIT License](LICENSE).
Feel free to use, modify, and redistribute.

---
