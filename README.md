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

### User Interface Pages

#### Home Page

##### Home Page Light Mode

![Home Page Light Mode](./screenshots/HomePage1.png)

##### Home Page French lang Dark Mode

![Home Page French Dark Mode](./screenshots/HomePageFrDark.png)

### Books Page

##### Books Page Light Mode

![Books Page](./screenshots/BooksPage.png)

##### Books Page Dark Mode

![Books Page Dark Mode](./screenshots/BooksPagedark.png)

### Book Details Page

![Book Details Page](./screenshots/BookPage.png)

### Best Sellers Page

##### Best Sellers Dark Mode

![Best Sellers Page Dark Mode](./screenshots/bestsellersPageDarkFr.png)

##### Best Sellers Light Mode

![Best Sellers Page](./screenshots/bestsellersPage.png)

### Categories Page

##### Categories Light Mode

![Categories Page](./screenshots/categoriesPage.png)

##### Categories Dark Mode

![Categories Page Dark Mode](./screenshots/categoriesPagedark.png)

### Checkouts Page

##### Checkouts Light Mode

![Checkouts Page](./screenshots/checkoutsPage.png)

##### Checkouts Dark Mode

![Checkouts Page Dark Mode](./screenshots/checkoutsPageDark.png)

### Authentication Pages

##### User Login Page

![Login Page](./screenshots/loginPage.png)

##### Admin Login Page

![Admin Login Page](./screenshots/admin/adminLoginPage.PNG)

### Admin Dashboard Pages

#### Main Dashboard

##### Dashboard Light Mode

![Admin Dashboard Light Mode](./screenshots/admin/dashboard.png)

##### Dashboard Dark Mode

![Admin Dashboard Dark Mode](./screenshots/admin/dashboarddark.png)

#### Book Management

##### Books List View Light Mode

![Books List View](./screenshots/admin/dashboardBooksIndex.PNG)

##### Books List View Dark Mode

![Books List View Dark Mode](./screenshots/admin/dashboardBooksIndexdarkfr.PNG)

##### Book Details View Light Mode

![Book Details View](./screenshots/admin/dashboardBooksView.PNG)

##### Book Details View Dark Mode

![Book Details View Dark Mode](./screenshots/admin/dashboardBooksViewDark.PNG)

##### Book Edit Page Light Mode

![Book Edit Page](./screenshots/admin/dashboardBooksEdit.PNG)

##### Book Edit Page Dark Mode

![Book Edit Page Dark Mode](./screenshots/admin/dashboardBooksEditDark.PNG)

#### Category Management

##### Categories List View Light Mode

![Categories List View](./screenshots/admin/dashboardcategoriesIndex.PNG)

##### Categories List View Dark Mode

![Categories List View Dark Mode](./screenshots/admin/dashboardcategoriesIndexDark.PNG)

##### Category Details

![Category Details View](./screenshots/admin/dashboardCtegoriesView.PNG)

##### Add Book to a Category

![Add Category View](./screenshots/admin/dashboardCtegoriesViewAdd.PNG)

##### Add Category

![Add Category Form](./screenshots/admin/dashboardCtegoriesAdd.PNG)

##### Edit Category

![Edit Category Form](./screenshots/admin/dashboardCtegoriesEdit.PNG)

#### Checkout Management

##### Checkouts

![Checkouts List View](./screenshots/admin/dashboardcheckoutsIndex.PNG)

##### Overdue Checkouts

![Overdue Checkouts View](./screenshots/admin/dashboardcheOverdueckoutsIndex.PNG)

#### User Management

![Users List View](./screenshots/admin/dashboardusersIndex.PNG)

#### Statistics and Reports

##### Dashboard Statistics

![Dashboard Statistics](./screenshots/admin/dashboardStatistics%20and%20Reports.PNG)

---

## Contact

For questions or to discuss my work, reach me via [GitHub](https://github.com/salaheddineaz47) or email : salaheddine.aitzenni@gmail.com .

---

© 2025 Kitabi. All rights reserved.
