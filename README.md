# Edu Learn - Transforming Online Education 🌐📚

Welcome to **Edu Learn**, a modern, responsive multi-page educational website built with HTML5, CSS3, Bootstrap 5, and JavaScript. This project serves as a demo platform for delivering online learning content and services.

## Features

- Hero landing page with animated text and CTA
- Services with interactive pricing calculator
- About Us with company timeline, team, and values
- Portfolio with filterable project gallery and modal preview
- Blog with category filtering and pagination
- Contact form, map, live chat, and FAQ section
- Fully responsive and mobile-friendly
- Modular structure using reusable components like navbar and footer

## Pages

| Page         | Description |
|--------------|-------------|
| `index.html` | Homepage with hero, features, testimonials, and CTA |
| `about.html` | Company story, timeline, team bios, values, stats |
| `services.html` | Overview of services, pricing calculator, and comparison table |
| `portfolio.html` | Showcase of projects with category filters and modal viewer |
| `blog.html`  | Articles listing with search and filter functionality |
| `contact.html` | Contact form, map, live chat, and FAQ section |

## Design Pattern Used

This project follows the **Modular Design Pattern** for frontend structure:

- **Component Reuse**: The navigation bar, footer, and hero sections are consistent and reused across all pages.
- **Separation of Concerns**: Structure (HTML), styling (CSS via Bootstrap and custom styles), and behavior (JavaScript for interactivity like modal, filtering, toggling) are separated for scalability.
- **Behavioral Patterns**:
  - **Strategy Pattern**: The filtering and pricing calculator functions dynamically adjust behavior based on user selections.
  - **Observer Pattern (Lightweight)**: Scroll-based animations and user interactions (e.g., read more toggle, FAQ dropdowns) follow a loosely coupled update mechanism.
