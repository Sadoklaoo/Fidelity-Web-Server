# ⚙️ Fidelity Full-Stack Core (Server & Web Portal)

[![Node.js](https://img.shields.io/badge/Node.js-18%2B-green.svg?style=for-the-badge&logo=nodedotjs)](https://nodejs.org/)
[![Express.js](https://img.shields.io/badge/Express.js-4.x-000000.svg?style=for-the-badge&logo=express)](https://expressjs.com/)
[![MySQL](https://img.shields.io/badge/MySQL-8.0-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)](https://www.mysql.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

The central core system powering the **Fidelity Ecosystem**—a shared loyalty points network designed for small business networks. This repository operates as a **full-stack solution**, hosting both the core REST API backend and the web portal for overall business management.

---

## 🧩 System Architecture & Ecosystem

The multi-tier system coordinates between business (B2B) and consumer (B2C) applications:

| Component | Repository | Tech Stack | Audience & Function |
| :--- | :--- | :--- | :--- |
| **Full-Stack Core** | **This Repo** | Node.js, Express, Web UI, MySQL | Core REST API server, database management, & administrative web portal |
| **B2C Mobile App** | [Fidelity-App](https://github.com/Sadoklaoo/Fidelity-App) | Flutter, Dart | Consumer mobile app for end-users to earn, track, and redeem points |
| **B2B Merchant App** | [Fidelity-Corp](https://github.com/Sadoklaoo/Fidelity-Corp) | Angular / Android | Merchant app for partner businesses to manage point rules & validate transactions |

---

## 📸 Web Portal Preview & Screenshots

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

* **🌐 Dual Full-Stack Architecture:** Integrated Web UI dashboard combined with RESTful API endpoints.
* **🔐 Multi-Role Authentication:** Dedicated auth pipelines for consumers, merchant managers, and super-admins.
* **💳 Shared Loyalty Rules Engine:** Logic to allocate, validate, and transfer points across participating merchants.
* **📊 Data Import & Push Notifications:** Support for bulk Excel data ingestion and SMS/push event broadcasting.

---

## 🚀 Quick Start

### Prerequisites
* [Node.js](https://nodejs.org/) (`v18+` recommended)
* [MySQL](https://www.mysql.com/) server

### Setup & Run
```bash
# Clone the repository
git clone [https://github.com/Sadoklaoo/Fidelity-Web-Server.git](https://github.com/Sadoklaoo/Fidelity-Web-Server.git)
cd Fidelity-Web-Server

# Install dependencies
npm install

# Start server & web interface
npm start
