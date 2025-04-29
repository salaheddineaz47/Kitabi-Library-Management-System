# Kitabi Library Management System

[![Kitabi Demo Video](https://img.youtube.com/vi/lZVzDYnsSMo/0.jpg)](https://youtu.be/lZVzDYnsSMo)

> **Watch the Kitabi Demo:** [YouTube Video](https://youtu.be/lZVzDYnsSMo)
>
> Click the image above or the link to watch a full walkthrough and demonstration of Kitabi Library Management System.

> **Showcase Project — Not for Public Use or Contributions**
>
> This repository is for portfolio and demonstration purposes only. It is intended to showcase my Laravel, MVC, and frontend skills, and to explain how the Kitabi project works. Not intended for production or collaborative development.

---

## Project Overview

Kitabi is a modern library management system built with Laravel. It features a clean UI, strict MVC architecture, and advanced frontend techniques. This project demonstrates my ability to design, implement, and document a full-featured web application from scratch.

---

## Why Kitabi? (Skills Demonstrated)

- **MVC Architecture:** All business logic is in controllers/models, never in views.
- **Blade Components:** Extensive use of reusable Blade components for UI consistency.
- **Theming:** Fully supports dark and light modes with TailwindCSS.
- **Localization:** Uses Laravel's translation system; easily extendable to new languages.
- **Custom Features:**
  - FAQ with JS toggle (no Alpine.js)
  - Best Sellers slider/grid with dynamic data
  - Admin dashboard with analytics
- **Clean Code:** Readable, maintainable, and well-documented throughout.

---

## Key Features

- User authentication (admin/user)
- Browse, search, and filter books
- Detailed book pages with related books
- Category management (admin)
- Book checkout/return system
- Admin dashboard with statistics and quick actions
- Reports and analytics for admins
- Dark/light theme toggle
- Language switcher (EN/FR)

---

## Technical Highlights

- **Backend:** Laravel (PHP), MySQL
- **Frontend:** Blade, TailwindCSS, custom JS
- **Auth:** Laravel Breeze
- **Components:** Located in `resources/views/components/`
- **Translations:** In `resources/lang/en/general.php`
- **Best Sellers:** Book model uses `scopeBestsellers()` for ranking
- **FAQ:** Uses Blade + JS for toggle, translations for questions/answers

---

## How the Project Works

- All user/admin pages are Blade views, using data passed from controllers
- No direct DB/model queries in views
- Sidebar, navbar, FAQ, and other UI elements are Blade components
- Theming and localization are available on every page
- Book and category management are admin-only features
- The welcome page features a Best Sellers slider and dynamic statistics

---

## Screenshots & Demo

> **Tip:** Add your own screenshots or GIFs here to show off the UI and features!
>
> - Home page (light/dark)
> - Admin dashboard
> - Book details
> - FAQ section
> - Best Sellers slider

---

---

## Contact

For questions or to discuss my work, reach me via [GitHub](https://github.com/salaheddineaz47) or email (see profile).

---

© 2025 Kitabi. All rights reserved.
