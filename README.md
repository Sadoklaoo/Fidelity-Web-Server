# ⚙️ Fidelity Full-Stack Core (Server & Web Portal)

[![Node.js](https://img.shields.io/badge/Node.js-18%2B-green.svg?style=for-the-badge&logo=nodedotjs)](https://nodejs.org/)
[![Express.js](https://img.shields.io/badge/Express.js-4.x-000000.svg?style=for-the-badge&logo=express)](https://expressjs.com/)
[![MySQL](https://img.shields.io/badge/MySQL-8.0-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)](https://www.mysql.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

The core central system powering the **Fidelity Ecosystem**—a shared loyalty points network designed for small businesses. This repository serves as a **full-stack solution**, hosting both the core REST API backend and the central Web Dashboard for management and operational control.

---

## 🧩 System Architecture & Ecosystem

The multi-tier system coordinates between business (B2B) and consumer (B2C) clients:

| Component | Repository | Tech Stack | Audience & Function |
| :--- | :--- | :--- | :--- |
| **Full-Stack Core** | **This Repo** | Node.js, Express, Web UI, MySQL | REST API server, database management, & administrative web dashboard |
| **B2C Mobile Client** | [Fidelity-App](https://github.com/Sadoklaoo/Fidelity-App) | Flutter, Dart | Consumer app for end-users to earn, track, and redeem points |
| **B2B Merchant App** | [Fidelity-Corp](https://github.com/Sadoklaoo/Fidelity-Corp) | Angular / Android | Merchant app for partner businesses to validate transactions & manage point rules |

---

## ✨ Key Features

* **🌐 Dual Full-Stack Architecture:** Combines an administrative web frontend interface with a REST API engine.
* **🔐 Unified Authentication:** Central authentication and authorization for end-consumers, business partners, and system admins.
* **💳 Point Rules Engine:** Calculates, validates, and transfers loyalty balances across partner merchants.
* **📊 Business Intelligence:** Serves transaction metrics, user profiles, and operational data to both B2B apps and internal dashboards.

---

## 🚀 Quick Start

### Prerequisites
* [Node.js](https://nodejs.org/) (`v18+` recommended)
* [MySQL](https://www.mysql.com/) database server

### Setup & Run
```bash
# Clone the repository
git clone [https://github.com/Sadoklaoo/Fidelity-Web-Server.git](https://github.com/Sadoklaoo/Fidelity-Web-Server.git)
cd Fidelity-Web-Server

# Install dependencies
npm install

# Environment setup (.env)
# DB_HOST=localhost
# DB_USER=root
# DB_PASS=yourpassword
# DB_NAME=fidelity_db
# PORT=3000

# Start server & web interface
npm start
