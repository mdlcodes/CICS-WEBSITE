# UST-CICS Website Redesign

A responsive multi-page web redesign of the University of Santo Tomas – College of Information and Computing Sciences (UST CICS) website, developed as a course project for Application Development.

---

## 📌 Project Overview

This project focuses on redesigning and modernizing the official web interface for the UST College of Information and Computing Sciences (CICS). The primary goal is to apply responsive web design principles, optimize visual hierarchy, and guarantee consistent usability across a spectrum of screen viewports—ranging from mobile devices to desktop monitors.

---

## ✨ Features

- **Adaptive Navigation Header**:
  - Full desktop navbar showcasing brand typography and primary action items.
  - Zero-JavaScript, CSS-only mobile drawer toggle using hidden semantic checkbox logic.
  - Custom SVG-based hamburger and close icons.
  - Custom `1270px` breakpoint preventing text crowding and premature word-wrapping.
- **Unified Multi-Page Architecture**:
  - Shared global stylesheet providing consistent branding, navigation, buttons, and layouts across all 3 pages.
- **Scalable Typography & Sizing**:
  - Root scaling using `html { font-size: 62.5%; }` for intuitive `1rem = 10px` measurements.
  - Fluid typography sizing via CSS `clamp()` to maintain proportional headings across all viewports.
- **Modular Component Architecture**:
  - Centralized design tokens (colors, font weights, transitions) stored in `:root`.
  - Reusable `.btn-primary` utility class supporting size modifiers (`.btn-sm`, `.btn-md`, `.btn-block`).
- **Overflow & Layout Protection**:
  - Defensive viewport scaling preventing horizontal scrollbars and side-gap bleed.
  - Baseline `320px` minimum body width to preserve layout integrity on ultra-narrow viewports.

---

## 🛠️ Tech Stack

- **HTML5**: Semantic layout markup and accessible form control state toggles.
- **CSS3**: Flexbox, CSS Grid, custom properties (variables), fluid units (`clamp()`), and media queries.
- **Figma**: UI/UX design mockups, responsive prototyping, and vector asset generation.

---

## 📁 Repository Structure

```text
├── index.html          # Home page
├── program.html        # Academic programs page
├── community.html      # Community / organization page
├── style.css           # Global unified stylesheet
├── images/             # Vector icons (SVG) and image assets
└── README.md           # Project documentation

```

> *Note: File names for the sub-pages can be adjusted based on the final project routing.*

---

## 🚀 Running the Project Locally

1. **Clone the repository**:
```bash
git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)

```


2. **Navigate to the project folder**:
```bash
cd your-repo-name

```


3. **Open the site**:
* Double-click `index.html` to view it directly in your browser, or
* Launch it using an extension like **Live Server** in Visual Studio Code.



---

## 📱 Breakpoint Logic

| Screen Width | Layout Mode | Navigation Behavior |
| --- | --- | --- |
| **> 1270px** | Desktop | Horizontal inline links with action buttons |
| **≤ 1270px** | Tablet & Mobile | Dropdown card drawer toggled via hamburger icon |
| **320px** | Minimum Mobile Floor | Guaranteed layout floor to prevent flex collapses |

---

## 👥 Authors

Developed for the **Application Development** course at the **University of Santo Tomas** by:

* **Matt**
* **Michelle**

```

```
