# 💸 SpendWise: Expense Tracker
SpendWise is a full-stack Expense Tracker app to manage your income and expenses efficiently. Built with React (Vite) on the frontend, Node.js (Express) on the backend, and MongoDB Atlas for data storage.

Live Demo: https://expense-tracker-finalmern-frontend.onrender.com

---

## 📦 Features

- 🔐 User authentication with JWT
- 💰 Add, update, and delete income/expenses
- 📊 Graphs and charts for insights (Bar/Pie)
- 📆 Filter transactions by date
- 🔎 View recent transactions
- 📁 Download income/expense data in Excel

---

## 🧑‍💻 Tech Stack

### Frontend ⚛️
- React + Vite
- Tailwind CSS
- Recharts
- Axios

### Backend 🛠️
- Node.js + Express
- MongoDB + Mongoose
- JWT (Authentication)
- dotenv

---

## 📁 Folder Structure

Expense-Tracker/
- ├── backend/ → Node.js Express API
- ├── frontend/expense-tracker/ → Vite + React frontend

---

## 🛠️ Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/kireeti01/expense-tracker-finalMERN.git
```

### 2. Backend setup

```bash
cd backend
npm install
```

- Create a .env file inside /backend:

```.env
MONGO_URI=your_mongo_connection_string
JWT_SECRET=your_jwt_secret
PORT=8000
```

- Run the backend server
```bash
npm run dev
```

### 3. Frontend setup

```bash
cd frontend/expense-tracker
npm install
```

- Create a .env file inside /frontend/expense-tracker:

```env
VITE_BASE_URL=http://localhost:8000
```

- Run the frontend
```bash
npm run dev
```

---

## 🙌 Acknowledgements
- Inspired by modern personal finance tools
- Built using best practices in the MERN stack

---

## 🧑‍💼 Author
- Yogendra kireeti
- 📫 [GitHub](https://github.com/kireeti01/my-project)
