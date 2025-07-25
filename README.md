# 💰 Fintracker – Smart Personal Finance Tracker

<div align="center">
  <img src="personal finance manager.jpeg" alt="Fintracker Banner" />
  
  <p><strong>Track expenses, set budgets, and visualize your spending – effortlessly.</strong></p>

  <p>
    <a href="LICENSE"><img src="https://img.shields.io/badge/license-MIT-blue.svg" alt="MIT License" /></a>
    <a href="https://react.dev/"><img src="https://img.shields.io/badge/React-18.2.0-%2361DAFB" alt="React" /></a>
    <a href="https://fastapi.tiangolo.com/"><img src="https://img.shields.io/badge/FastAPI-0.95.0-%2300C7B7" alt="FastAPI" /></a>
    <a href="https://www.postgresql.org/"><img src="https://img.shields.io/badge/PostgreSQL-16.0-%23336791" alt="PostgreSQL" /></a>
  </p>
</div>

---

## ✨ Key Features

| Feature               | Description                                                  |
|----------------------|--------------------------------------------------------------|
| 🔐 **JWT Auth**       | Secure registration and login using JWT tokens               |
| 🧾 **Expense Manager**| Add, edit, categorize, and track spending easily             |
| 🎯 **Budget Targets** | Set and manage monthly spending limits by category           |
| 📊 **Data Visualization** | Bar & doughnut charts to analyze and compare expenses   |
| 📱 **Responsive UI**  | Optimized for mobile and desktop screens                     |

---

## 🌐 Overview

Fintracker is a **full-stack personal finance manager** to help individuals organize and track their expenses. Built with a **React frontend** and **FastAPI backend**, the app allows users to set budgets, categorize expenses, and gain insights with visual analytics.

---

## 🧱 Tech Stack

### 🔹 Frontend
- **React**
- **React Bootstrap**
- **Chart.js**
- **Vite** (for fast builds and dev server)

### 🔸 Backend
- **FastAPI**
- **PostgreSQL + SQLAlchemy**
- **Pydantic** (for validation)
- **JWT & OAuth2**
- **Uvicorn** (ASGI server)

### ⚙️ Tools
- **Docker** (for containerization)
- **GitHub Actions** (CI/CD)
- **.env config** (secure secrets handling)

---

## 🚀 Getting Started

### ✅ Prerequisites
- Node.js (v16+)
- Python 3.10+
- PostgreSQL (v16+)
- Docker (optional but recommended)

---

### 📦 Installation Steps

#### 1. Clone the Repository
``bash
git clone https://github.com/Airborne101st/fin-tracker.git
cd fin-tracker



2. Backend Setup
bash
Copy
Edit
cd app
pip install -r requirements.txt
Create a .env file:

env
Copy
Edit
DATABASE_URI=postgresql://postgres:username@localhost:5432/fintracker_db
JWT_SECRET=your_secret_key
Run FastAPI server:

bash
Copy
Edit
uvicorn app.main:app --reload
3. Frontend Setup
bash
Copy
Edit
cd ../frontend
npm install
npm run dev
🔗 Application URL
Visit the frontend at: http://localhost:5173

🧑‍💻 How to Use
✅ Register a new account

🔐 Login using JWT authentication

🧾 Add categories and set monthly budgets

💸 Add expenses and assign them to categories

📊 View bar/doughnut charts with monthly targets

🖼️ Screenshots
<div align="center"> <img src="fintracker_dashboard.png" alt="Dashboard - Bar Chart" width="300" /> <img src="fintracker_category.png" alt="Categories Page" width="300" /> <img src="fintracker_expenses.png" alt="Expenses Page" width="300" /> </div>
🧩 Future Enhancements
🔔 Notification alerts for over-budget categories

📅 Recurring expenses & reminders

📤 Export reports to PDF/CSV

🌐 Multi-user shared accounts (family budgeting)

📱 PWA support for mobile offline use

🤝 Contributing
We welcome contributions!

Fork this repository

Create your feature branch:

bash
Copy
Edit
git checkout -b feature/your-feature
Commit your changes

Push to the branch

Open a Pull Request 🎉

📄 License
This project is licensed under the MIT License – see the LICENSE file for details.

<div align="center"> <b>Fintracker</b> – Your smart partner in managing money 💼 </div> ```
