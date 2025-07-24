# 💰 Fintracker - Personal Finance Tracker  

![Fintracker Banner](https://via.placeholder.com/1200x400/4f46e5/ffffff?text=Fintracker+-+Smart+Expense+Management)  
[![GitHub License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![React](https://img.shields.io/badge/React-18.2.0-%2361DAFB)](https://react.dev/)
[![FastAPI](https://img.shields.io/badge/FastAPI-0.95.0-%2300C7B7)](https://fastapi.tiangolo.com/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-16.0-%23336791)](https://www.postgresql.org/)

> **Track expenses, set budgets, and visualize spending effortlessly**  

---

## ✨ Features  

✅ **User Authentication** – Secure signup/login with JWT  
✅ **Expense Management** – Add, edit, and categorize transactions  
✅ **Budget Targets** – Set monthly spending limits per category  
✅ **Data Visualization** – Interactive charts (Bar & Doughnut)  
✅ **Responsive UI** – Works on mobile & desktop  

---

# Fintracker
Personal Finance Tracking Application


## 🌟 Overview

This is a **Full Stack Expense Tracker Application** that helps users manage their expenses by creating categories, setting monthly targets, and visualizing spending trends through bar and charts and doughnut charts. Built using **React** for the frontend and **FastAPI** for the backend, it provides an intuitive interface and efficient performance.

---

## 🛠️ **Features**

- **User Authentication**: Register and login securely.
- **Category Management**: Add, edit, and delete expense categories.
- **Expense Tracking**: Keep a record of expenses and their details.
- **Bar Charts**: Visualize spending trends with targets highlighted on the chart.
- **Responsive UI**: Designed to work seamlessly on both desktop and mobile devices.

---

## 🛠️ **Tech Stack**

### **Frontend**:
- **React**: JavaScript library for building user interfaces.
- **React Bootstrap**: For responsive and stylish components.
- **Chart.js**: To create bar charts for visualizing data.

### **Backend**:
- **FastAPI**: High-performance Python backend framework.
- **PostgresDB**: SQL database for storing users, categories, and expenses.

### **Tools**:
- **Docker**: Containerization for seamless deployment.
- **GitHub Actions**: CI/CD for automated deployments.

---

## 🔧 **Installation**

### Prerequisites:
- Node.js (v16 or later)
- Python 3.10 or later
- Postgres server (Version 17 or later)
- Docker (optional but recommended for deployment)

### Steps:

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/Airborne101st/fin-tracker.git
    cd fin-tracker
    ```

2. **Set Up the Backend**:
    - Navigate to the `backend` folder:
      ```bash
      cd app
      ```
    - Install dependencies:
      ```bash
      pip install -r requirements.txt
      ```
    - Create a `.env` file and configure environment variables:
      ```env
      DATABASE_URI=postgresql://postgres:username@localhost:5432/fintracker_db
      JWT_SECRET=your_secret_key
      ```
    - Run the FastAPI server:
      ```bash
      uvicorn app.main:app
      ```

3. **Set Up the Frontend**:
    - Navigate to the `frontend` folder:
      ```bash
      cd frontend
      ```
    - Install dependencies:
      ```bash
      npm install
      ```
    - Start the React development server:
      ```bash
      npm run dev
      ```

4. **Access the Application**:
    - Open [http://localhost:5173](http://localhost:5173) to view the application.

---

## 🧑‍💻 **Usage**

1. Register your user.
2. Login to your account
3. Create categories and set monthly targets.
4. Add expenses under specific categories.
5. Visualize your spending with bar and doughnut charts, including target indicators.

---

## 🖼️ **Screenshots**

### Bar Chart with Targets:
![Bar Chart](fintracker_dashboard.png)

### Category Page:
![Bar Chart](fintracker_category.png)

### Expenses Page:
![Bar Chart](fintracker_expenses.png)

---


## 🤝 **Contributing**

We welcome contributions! To get started:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/your-feature

