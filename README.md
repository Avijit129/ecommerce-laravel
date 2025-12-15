# Full-Stack E-Commerce Application

A modern full-stack e-commerce web application built with **Laravel** for the backend and **React** for the frontend. The project follows industry-standard architecture and best practices, including token-based authentication, clean API separation, and a scalable frontend structure.

This repository contains both the **admin panel** and **public storefront**, designed to closely mirror real-world production systems.

---

## Tech Stack

### Backend

* **Laravel** – RESTful API development
* **Laravel Sanctum** – Token-based authentication
* **MySQL** – Relational database
* **Axios-friendly API design**

### Frontend

* **React** – Component-based UI
* **Axios** – API communication
* **Modern CSS / UI utilities**

---

## Core Features

### Authentication & Security

* User **registration (sign up)**
* User **login & logout**
* Token-based authentication using **Laravel Sanctum**
* Protected API routes for authenticated users
* Secure session handling between frontend and backend

---

### Product Management

* Product listing with optimized API responses
* Advanced **product filtering** (category-based and attribute-based)
* Smooth **lazy loading** for improved performance
* Clean separation between admin-controlled data and public views

---

### Product Zoom (Amazon-Style)

* Interactive **image zoom** similar to Amazon product pages
* High-resolution magnification on hover
* Optimized for performance and user experience

---

### Loading & UX Enhancements

* Global and component-level **loading indicators**
* Smooth state transitions for API calls
* Clear visual feedback during data fetching

---

### Admin Panel

* Secure admin authentication
* Product management via API
* Scalable structure for future extensions (orders, users, analytics)

---

## Architecture Overview

```
Frontend (React)
   │
   │ Axios (API Requests)
   ▼
Backend (Laravel API)
   │
   │ Sanctum Tokens
   ▼
Database (MySQL)
```

* Frontend and backend are **fully decoupled**
* Communication handled exclusively via REST APIs
* Authentication managed using **HTTP-only tokens**

---

## API Communication

* Axios is used for all HTTP requests
* Centralized API configuration for scalability
* Automatic token handling for authenticated requests
* Error handling designed for real-world production use

---

## Installation & Setup

### Backend (Laravel)

```bash
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate
php artisan serve
```

### Frontend (React)

```bash
npm install
npm run dev
```

Make sure the frontend API base URL points to the Laravel backend.

---

## Project Goals

* Demonstrate **real-world full-stack development**
* Apply clean coding standards and separation of concerns
* Build a scalable foundation for future features such as:

  * Orders & payments
  * Reviews & ratings
  * Role-based access control

---

## Status

The project is actively developed and structured to support long-term scalability and maintainability.

---

## Author

**Avijit Biswas**
Full-Stack Web Developer

---

## License

This project is open for learning and demonstration purposes.
