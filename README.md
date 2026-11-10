# 📦 Enterprise PMS & RMS Ecosystem

A lightweight, zero-dependency, and fully responsive client-side web application ecosystem designed to manage inventory, issue official customer receipts, track real-time stock deductions, and analyze business performance through an executive dashboard. 

Built with **HTML5, Native JavaScript, Bootstrap 5, and Chart.js**, this system runs entirely in the browser using `localStorage` for data persistence, making it fast, secure, and easy to deploy.

---

## 🌟 Core Modules

### 1. 📊 Executive Dashboard (`dashboard.html`)
* **Live Business Analytics:** Real-time calculation of total revenue, monthly sales, total inventory valuation, and low-stock items.
* **Interactive Visualizations:** Powered by Chart.js to display revenue trends, category distributions, top-selling products, and stock health.
* **Stock Restock Hub:** Quick-action restock triggers directly from the dashboard view[cite: 3].
* **Express Checkout POS Terminal:** Built-in point-of-sale modal allowing users to instantly select inventory items, adjust quantities, calculate 12% VAT breakdowns, issue receipts, and automatically deduct active stock levels in real-time[cite: 3].

### 2. 📋 Product Management System - PMS (`pms.html`)
* **Inventory Control:** Add, edit, delete, and search products by number, name, description, or category.
* **Stock Monitoring:** Visual low-stock warning badges (< 8 units)[cite: 2].
* **Price Tag Generator:** Generate and print printable thermal price tags for products[cite: 2].
* **Data Portability:** Export inventory or low-stock reports to CSV, and backup/restore the entire database via JSON[cite: 2].

### 3. 🧾 Receipt Management System - RMS (`rms.html`)
* **Transaction Tracking:** Create, edit, view, and delete customer receipts.
* **Barcode & Product Number Integration:** Fast barcode scanning simulation and product lookup that auto-fills prices and descriptions while updating inventory stock instantly[cite: 1].
* **Thermal Receipt Printing:** Formatted receipt preview supporting direct thermal printing with automatic 12% VAT calculations[cite: 1].
* **CSV & JSON Utilities:** Export receipts to CSV or perform full local database backups[cite: 1].

---

## 🔒 Security Feature
* **Inactivity Auto-Lock:** Automatically locks the application after 5 minutes of inactivity (or upon page refresh/reload) with a customizable master password prompt (`Admin@2026`) to secure sensitive business data.

---

## 🚀 Quick Start / Installation

Because this ecosystem relies on static web technologies with browser local storage, no complex backend server setup or node modules installation is required.

Note: On-screen password is "Admin@2026".
