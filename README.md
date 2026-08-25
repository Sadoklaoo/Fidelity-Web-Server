# ⚙️ Fidelity Web Server (REST API)

[![Node.js](https://img.shields.io/badge/Node.js-18%2B-green.svg?style=for-the-badge&logo=nodedotjs)](https://nodejs.org/)
[![Express.js](https://img.shields.io/badge/Express.js-4.x-000000.svg?style=for-the-badge&logo=express)](https://expressjs.com/)
[![MySQL](https://img.shields.io/badge/MySQL-8.0-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)](https://www.mysql.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

The central backend REST API powering the **Fidelity Ecosystem**—a multi-vendor loyalty program enabling small businesses to share a unified points network[cite: 1]. This server handles authentication, point calculations, transaction processing, and data persistence for both the client mobile app and corporate web portal[cite: 1].

---

## 🧩 System Ecosystem

This API connects the entire 3-tier architecture:

| Component | Repository | Tech Stack | Role |
| :--- | :--- | :--- | :--- |
| **Backend API** | **This Repo** | Node.js, Express, MySQL | Core business logic, database access, & REST API[cite: 1] |
| **Mobile Client** | [Fidelity-App](https://github.com/Sadoklaoo/Fidelity-App) | Flutter, Dart | Mobile app for end-users to earn & track points[cite: 1] |
| **Admin Web Portal** | [Fidelity-Corp](https://github.com/Sadoklaoo/Fidelity-Corp) | Angular, TypeScript | Dashboard for partner businesses to manage rules & metrics[cite: 1] |

---

## ✨ Key Features

* **🔐 Auth & Security:** Secure user authentication and session management.
* **💳 Point Engine:** Core logic for accumulating, redeeming, and validating shared loyalty points across merchants[cite: 1].
* **📊 Business Metrics:** Endpoints serving analytics and store data to the Angular admin dashboard[cite: 1].
* **🗄️ Relational Persistence:** Structured MySQL relational schema for user balances, store partner profiles, and transaction logs[cite: 1].

---

## 🚀 Quick Start

### Prerequisites
* [Node.js](https://nodejs.org/) (`v18+` recommended)
* [MySQL](https://www.mysql.com/) database server running locally or hosted

### Setup & Run
```bash
# Clone the repository
git clone [https://github.com/Sadoklaoo/Fidelity-Web-Server.git](https://github.com/Sadoklaoo/Fidelity-Web-Server.git)
cd Fidelity-Web-Server

# Install dependencies
npm install

# Configure Environment Variables (.env)
# Create a .env file with your database credentials:
# DB_HOST=localhost
# DB_USER=root
# DB_PASS=yourpassword
# DB_NAME=fidelity_db
# PORT=3000

# Start server
npm start
```


<img src="https://user-images.githubusercontent.com/48072325/100867074-f16c9d80-3499-11eb-8d7e-1029184e4d6d.PNG" >
<img src="https://user-images.githubusercontent.com/48072325/100866802-7c996380-3499-11eb-96eb-e7f522103373.PNG" >
<img src="https://user-images.githubusercontent.com/48072325/100866822-815e1780-3499-11eb-8450-ee0089b2e182.PNG" >
<img src="https://user-images.githubusercontent.com/48072325/100866823-828f4480-3499-11eb-801c-2f46d8ec7600.PNG" >
<img src="https://user-images.githubusercontent.com/48072325/100866809-7e632700-3499-11eb-8131-df85af87547a.PNG" >
<img src="https://user-images.githubusercontent.com/48072325/100866813-7efbbd80-3499-11eb-95e8-dfcbb05627cb.PNG" >
<img src="https://user-images.githubusercontent.com/48072325/100866815-7f945400-3499-11eb-85db-04fb5c06f7a0.PNG" >
<img src="https://user-images.githubusercontent.com/48072325/100866818-80c58100-3499-11eb-93f1-1038c9333803.PNG" >
