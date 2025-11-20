# 🛒 E-Com Web Application

A full-stack e-commerce web application built using **React (Vite)** for the frontend and **Spring Boot** for the backend.

The project uses an **H2 In-Memory Database**, making development simple, fast, and lightweight.

---

## 🚀 Tech Stack

### **Frontend**
- **Framework:** React JS (Vite)
- **HTTP Client:** Axios
- **State Management:** Context API
- **Styling:** CSS, HTML, JavaScript

### **Backend**
- **Framework:** Spring Boot (Java 17+)
- **Web:** Spring Web
- **Database:** H2 Database (In-Memory)
- **ORM:** Spring Data JPA & Hibernate
- **Architecture:** REST API

---

## 📁 Project Structure

```text
E-Com/
│
├── Client/
│   └── ecom-frontend-2/
│       ├── src/
│       │   ├── components/
│       │   │   ├── Home.jsx
│       │   │   ├── Navbar.jsx
│       │   │   ├── Product.jsx
│       │   │   ├── Cart.jsx
│       │   │   ├── CheckoutPopup.jsx
│       │   │   └── AddProduct.jsx
│       │   ├── Context/
│       │   ├── App.jsx
│       │   ├── main.jsx
│       │   └── index.css
│       ├── package.json
│       └── vite.config.js
│
└── Java_Backend/
    └── ecom-proj/
        ├── src/
        │   └── main/
        │       ├── java/com/example/ecom_proj/
        │       │   ├── controller/
        │       │   ├── model/
        │       │   ├── repository/
        │       │   ├── service/
        │       │   └── EcomProjApplication.java
        │       └── resources/
        │           ├── application.properties
        │           └── data.sql (optional)
```

---

## ⚙️ Setup & Installation

Follow these steps to get the project running locally.

### 1. Backend Setup (Spring Boot)

The backend should be started first so the API is available for the frontend.

**Navigate to the backend directory:**
```bash
cd Java_Backend/ecom-proj
```

**Run the application:**
You can run this using your IDE (IntelliJ/VS Code) or via the terminal:

```bash
mvn spring-boot:run
```

- **Server Port:** `http://localhost:8080`
- **H2 Database Console:** `http://localhost:8080/h2-console` (Check `application.properties` for credentials).

<br>

### 2. Frontend Setup (React + Vite)

**Navigate to the frontend directory:**
```bash
cd Client/ecom-frontend-2
```

**Install dependencies:**
```bash
npm install
```

**Start the development server:**
```bash
npm run dev
```

- **Frontend URL:** `http://localhost:5173`

---

## 📝 Key Features
Based on the project structure, the application includes:
- **Home Page:** Product listing.
- **Product Management:** Add new products (`AddProduct.jsx`).
- **Shopping Cart:** Manage selected items (`Cart.jsx`).
- **Checkout:** Simple checkout popup (`CheckoutPopup.jsx`).

---

## ⚠️ Current Status: Work in Progress
**Note:** This is a live project currently under active development.
- The **User Interface (UI)** is functional but not yet fully polished or attractive.
- Some **Backend APIs** are still in progress and not yet fully completed.