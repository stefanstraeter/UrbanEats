# URBANEATS – Modern Food Delivery App

A dynamic food ordering app built with Vanilla JavaScript.

Browse menus, manage a real-time shopping cart, and switch between delivery and pickup with instant price updates – all directly in the browser.

🔗 **Live Demo:** https://stefanstraeter.github.io/urban-eats/

---

## Preview

![UrbanEats Preview](assets/img/urbanEats_mockup.jpg)

---

## Features

- Dynamic menu rendering from a central data source
- Real-time shopping cart with live price calculation
- Delivery vs. pickup toggle with dynamic fee updates
- Persistent cart using Local Storage
- Quantity management (+ / -) with validation
- Minimum order logic
- Responsive design with mobile-first approach

---

## Purpose

This project was developed as part of a frontend training program at the Developer Akademie.

It demonstrates how a real-world e-commerce-like application can be built using Vanilla JavaScript without frameworks.

Focus areas include:

- dynamic DOM rendering from structured data
- client-side state management (shopping cart logic)
- persistent data handling using Local Storage
- building interactive UI flows with immediate feedback

---

## Getting Started

Clone the repository:

```id="z7x2qa"
git clone https://github.com/stefanstraeter/urban-eats
cd urban-eats
```

Run the project using a local development server (e.g. VS Code Live Server).

---

## Tech Stack

- HTML5
- CSS3 (Flexbox, Grid, responsive design)
- Vanilla JavaScript
- Local Storage

---

## Project Structure

```id="v1m8ls"
scripts/
  db.js
  template.js
script.js
styles/
```

- **scripts/db.js** – Data layer containing dishes, categories, and pricing
- **scripts/template.js** – UI rendering via template functions
- **script.js** – Main logic (cart, events, state handling)
- **styles/** – Modular CSS (layout, components, responsiveness)

---

## Architecture Highlights

- **Data-Driven UI**
  The entire menu is generated dynamically from a central data structure.

- **Client-Side State Management**
  Cart state is managed in JavaScript and synchronized with Local Storage.

- **Separation of Concerns**
  Clear distinction between data, UI templates, and application logic.

- **Real-Time UI Updates**
  Immediate feedback on user interactions (cart updates, pricing, toggles).

---

## Technical Challenges

### Cart State Management

Keeping cart data consistent across UI, calculations, and Local Storage.

### Dynamic Price Calculation

Handling delivery fees, minimum order values, and live updates without inconsistencies.

### UI Synchronization

Ensuring all components reflect the current state after each interaction.

### Responsive UX Design

Designing a smooth ordering experience across mobile and desktop devices.

---

## Author

**Stefan Straeter**

GitHub: https://github.com/stefanstraeter/
