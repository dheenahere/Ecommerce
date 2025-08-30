

# 🛒 SwiftCart

**Full-stack E-commerce App** built with **React**, **Node.js**, **Express**, **MongoDB**, **JWT**, **Stripe Payments**, and **Tailwind CSS**.
Forked & enhanced from Murali’s original project—with ❤️ by **Author: Thinakaran Manokaran** ([@thinakaran.dev](https://thinakaran.dev))

---

## 📑 Table of Contents

* [✨ Features](#-features)
* [🛠 Tech Stack](#-tech-stack)
* [🎥 Demo](#-demo)
* [⚡ Getting Started](#-getting-started)

  * [📦 Prerequisites](#-prerequisites)
  * [⚙️ Installation](#️-installation)
  * [▶️ Running the App](#️-running-the-app)
* [📂 Folder Structure](#-folder-structure)
* [🔐 Configuration](#-configuration)
* [🖥 Usage](#-usage)
* [🚀 Future Improvements](#-future-improvements)
* [👨‍💻 Author](#-author)
* [📜 License](#-license)

---

## ✨ Features

* 🔐 User authentication with **JWT**
* 🛍 Product & category management (add, edit, delete)
* 🖼 File uploads for **product/category images**
* 📱 Fully responsive UI with **Tailwind CSS**
* 💳 Integrated payments (Stripe)
* 📊 Real-time CRUD notifications
* ⚡ Modern **React + Express + MongoDB** stack

---

## 🛠 Tech Stack

| Layer       | Technologies                            |
| ----------- | --------------------------------------- |
| 🎨 Frontend | React, Tailwind CSS, Context API        |
| 🖥 Backend  | Node.js, Express.js, Mongoose (MongoDB) |
| 🔐 Auth     | JSON Web Tokens (JWT)                   |
| 📦 Storage  | MongoDB + Server file system (uploads)  |
| 💳 Payments | Stripe API                              |

---

## 🎥 Demo

*(Optional: Add GIFs or video link)*
👉 Example: [YouTube Walkthrough](https://www.youtube.com/watch?v=lXk14qt2D28)

---

## ⚡ Getting Started

### 📦 Prerequisites

* 📌 Node.js (v16+) & npm / Yarn
* 🗄 MongoDB (local or Atlas cluster)
* 💳 Stripe account & API keys (optional for payments)

---

### ⚙️ Installation

1️⃣ Clone the repo

```bash
git clone https://github.com/thinakaranmanokaran/SwiftCart.git
cd SwiftCart
```

2️⃣ Install dependencies

```bash
cd client && npm install
cd ../server && npm install
```

---

### ▶️ Running the App

1. Start MongoDB (local/Atlas)
2. Add environment variables (see [Configuration](#-configuration))
3. Run backend:

   ```bash
   cd server
   npm run dev
   ```
4. Run frontend:

   ```bash
   cd ../client
   npm start
   ```

👉 Frontend: `http://localhost:3000`
👉 Backend: `http://localhost:5000`

---

## 📂 Folder Structure

```
SwiftCart/
├── client/             # 🎨 React frontend
│   ├── src/
│   └── public/
├── server/             # 🖥 Node.js + Express backend
│   ├── controller/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   ├── public/uploads/
└── README.md
```

---

## 🔐 Configuration

Create `.env` inside `server/`

```env
PORT=5000
MONGODB_URI=your_mongo_connection_string
JWT_SECRET=your_jwt_secret
STRIPE_SECRET_KEY=your_stripe_secret_key
```

---

## 🖥 Usage

* 👤 Sign up / Login as **Admin**
* 🛒 Add / Edit / Delete **Products & Categories**
* 🖼 Upload product/category images
* 💳 Checkout with Stripe integration
* 📦 Manage stock, prices, and offers

---

## 🚀 Future Improvements

* 📱 Add **mobile app (React Native / Flutter)**
* 🌍 Multi-language & multi-currency support
* 📊 Analytics dashboard for admin
* 🔔 Push/email notifications for orders

---

## 👨‍💻 Author

**Thinakaran Manokaran**
🌐 [thinakaran.dev](https://thinakaran.dev)
💼 [LinkedIn](https://linkedin.com/in/thinakaran-manohar)
📧 [thinakaran.manohar@gmail.com](mailto:thinakaran.manohar@gmail.com)

---

## 📜 License

This project is licensed under the **MIT License**.

