# 🏢 Fidelity Corp (Angular Admin Dashboard)

[![Angular](https://img.shields.io/badge/Angular-10%2B-DD0031.svg?style=for-the-badge&logo=angular&logoColor=white)](https://angular.io/)
[![TypeScript](https://img.shields.io/badge/TypeScript-4.x-3178C6.svg?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

The corporate management web application for the **Fidelity Ecosystem**—a multi-vendor shared loyalty program enabling local businesses to co-manage point rules, user registries, catalog items, and marketing events across partner merchants.

---

## 🧩 System Ecosystem

This management web app interacts with the multi-repo system:

| Component | Repository | Tech Stack | Role |
| :--- | :--- | :--- | :--- |
| **Admin Web Portal** | **This Repo** | Angular, TypeScript | Admin dashboard for business partners & store managers |
| **Backend API** | [Fidelity-Web-Server](https://github.com/Sadoklaoo/Fidelity-Web-Server) | Node.js, Express, MySQL | REST API, database access, & auth logic |
| **Mobile Client** | [Fidelity-App](https://github.com/Sadoklaoo/Fidelity-App) | Flutter, Dart | Mobile client for end-users to collect & track points |

---

## 📸 Interface Preview & Screenshots

### 🔑 Authentication & User Management

| Manager Authentication | User Directory |
| :---: | :---: |
| <img src="https://user-images.githubusercontent.com/48072325/100867074-f16c9d80-3499-11eb-8d7e-1029184e4d6d.PNG" width="450" alt="Fidelity Login Interface"/> | <img src="https://user-images.githubusercontent.com/48072325/100866802-7c996380-3499-11eb-96eb-e7f522103373.PNG" width="450" alt="View Users Table"/> |
| *Manager login screen featuring phone-based authentication.* | *Searchable user management table supporting inline editing & deletion.* |

| User Registration Form | Store & Merchant Directory |
| :---: | :---: |
| <img src="https://user-images.githubusercontent.com/48072325/100866809-7e632700-3499-11eb-8131-df85af87547a.PNG" width="450" alt="User Registration Form"/> | <img src="https://user-images.githubusercontent.com/48072325/100866818-80c58100-3499-11eb-93f1-1038c9333803.PNG" width="450" alt="Store Directory Management"/> |
| *Admin panel to manually register new program members.* | *Partner store directory displaying merchant addresses & types.* |

---

### 📦 Product & Event Management

| Product Catalog | Add New Product |
| :---: | :---: |
| <img src="https://user-images.githubusercontent.com/48072325/100866813-7efbbd80-3499-11eb-95e8-dfcbb05627cb.PNG" width="450" alt="View Products Table"/> | <img src="https://user-images.githubusercontent.com/48072325/100866823-828f4480-3499-11eb-801c-2f46d8ec7600.PNG" width="450" alt="Add Product Screen"/> |
| *Product inventory view linked across participating stores.* | *Product registration form with image upload functionality.* |

| Event & Notification Dispatch | Batch Database Import |
| :---: | :---: |
| <img src="https://user-images.githubusercontent.com/48072325/100866822-815e1780-3499-11eb-8450-ee0089b2e182.PNG" width="450" alt="Create Event Form"/> | <img src="https://user-images.githubusercontent.com/48072325/100866815-7f945400-3499-11eb-85db-04fb5c06f7a0.PNG" width="450" alt="Excel Database Upload Screen"/> |
| *Event scheduling for target client groups via SMS & Push Notifications.* | *Excel database upload tool for bulk user and product migration.* |

---

## ✨ Key Features

* **👥 Role-Based User Management:** Search, edit, and provision user and manager credentials.
* **🏷️ Product & Inventory Control:** Assign products to specific partner stores with images and pricing metrics.
* **📢 Marketing Event Dispatcher:** Create targeted events (e.g., Happy Hours) with options for SMS or push notifications.
* **📊 Batch Data Upload:** Import customer and product lists via bulk Excel sheet parsing.

---

## 🚀 Quick Start

### Prerequisites
* [Node.js](https://nodejs.org/) (`v14+` or `v16+`)
* [Angular CLI](https://angular.io/cli) (`npm install -g @angular/cli`)

### Setup & Run
```bash
# Clone the repository
git clone [https://github.com/Sadoklaoo/Fidelity-Corp.git](https://github.com/Sadoklaoo/Fidelity-Corp.git)
cd Fidelity-Corp

# Install dependencies
npm install

# Start development server
ng serve -o
