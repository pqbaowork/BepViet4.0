# 🍲 BepViet 4.0 (Vietnamese Kitchen 4.0)

[![Build Status](https://img.shields.io/badge/build-passing-brightgreen.svg)](#)
[![Backend](https://img.shields.io/badge/Backend-Laravel-FF2D20.svg?logo=laravel)](#)
[![Frontend](https://img.shields.io/badge/Frontend-JavaScript-F7DF1E.svg?logo=javascript)](#)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

## 📖 About The Project

**BepViet 4.0** is a comprehensive, modern web application designed to digitize and manage operations for Vietnamese restaurants and food delivery services. Built with scalability and performance in mind, it operates on a fully decoupled architecture, separating the client-side interface from the robust backend API.

### 🚀 Key Features
* **Modern Interface**: A seamless and responsive user experience for customers browsing menus, placing orders, and tracking deliveries.
* **Admin Dashboard**: Comprehensive management of inventory, categories, orders, and user roles.
* **RESTful API**: Secure, scalable, and optimized endpoints servicing the frontend clients.
* **Authentication & Authorization**: Secure JWT/Sanctum-based authentication.

---

## 🛠 Tech Stack

### Backend (`/bepviet-backend`)
* **Framework:** [Laravel](https://laravel.com/) (PHP)
* **Template Engine:** Blade (for emails and specific admin views)
* **Database:** MySQL / PostgreSQL
* **Authentication:** Laravel Sanctum / JWT

### Frontend (`/bepviet-frontend`)
* **Language:** JavaScript (ES6+), HTML5, CSS3
* **Framework:** React / Vue.js (or equivalent modern JS framework)
* **State Management:** Redux / Pinia / Context API
* **Styling:** TailwindCSS / SCSS / Bootstrap

---

## 📂 Project Structure

This repository is built as a monorepo containing both the frontend and backend applications.

```text
BepViet4.0/
├── bepviet-backend/        # Laravel application (REST API)
│   ├── app/                # Core backend logic (Controllers, Models)
│   ├── routes/             # API routes
│   └── ...                 
├── bepviet-frontend/       # Client-side web application
│   ├── src/                # UI components, pages, state management
│   ├── public/             # Static assets
│   └── ...                 
└── README.md               # Project documentation (You are here)
