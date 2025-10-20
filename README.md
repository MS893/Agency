# UI Kit for "Agency" Project

This repository contains a simple and clean UI kit designed for "Agency", a fully online school. It provides a foundational set of "atoms" and "molecules" to ensure design consistency and facilitate rapid development.

## How to Use

Simply link the `style.css` file in the `<head>` of your HTML document. The `index.html` file serves as a live catalog of all available components.

```html
<link rel="stylesheet" href="style.css">
```

## Components

The UI kit is structured around the following core components:

### 1. Colors

A well-defined color palette is available through CSS variables.

-   **Primary**: `var(--color-primary)` (Blue)
-   **Secondary**: `var(--color-secondary)` (Orange)
-   **Grays**: `var(--color-dark)`, `var(--color-medium-light)`, `var(--color-light)`
-   **Status Colors**: `var(--color-success)`, `var(--color-danger)`, `var(--color-warning)`, `var(--color-info)`

### 2. Typography

A clear typographic hierarchy is established with two font families: a serif font for headings and a system sans-serif font for body text.

-   **Headings**: `<h1>` to `<h6>`
-   **Paragraphs**: `<p>` and `.lead` for emphasized paragraphs.
-   **Blockquotes**: `<blockquote>` for citations.
-   **Lists**: `<ul>` (unordered) and `<ol>` (ordered).

### 3. Buttons

A versatile set of buttons for various actions.

-   **Types**: `.btn-primary`, `.btn-warning`, `.btn-danger`, `.btn-info`, `.btn-success`
-   **Styles**: Normal (solid) and Outline (e.g., `.btn-outline-primary`)
-   **Sizes**: `.btn-lg` (Large) and `.btn-sm` (Small)

### 4. Iconography

A set of clean, line-art SVG icons is included. Use the `.icon` class on an `<svg>` element.

### 5. Form Inputs

Styled form elements for a consistent user experience, all using the `.form-control` class for text-based inputs, and `.form-check` for radios/checkboxes.

### 6. List Group

A flexible component (`.list-group`) for displaying a series of content or navigation links (`.list-group-item`).

### 7. Cards

A collection of card components (`.card`) for displaying content in a structured way. Variations include cards with images, horizontal cards with avatars, and cards with image overlays.