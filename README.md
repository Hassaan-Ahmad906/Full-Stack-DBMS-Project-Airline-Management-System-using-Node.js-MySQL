# ✈️ SkyWings Airlines – Flight Booking System

A **full-stack airline reservation system** built with **Node.js**, **Express**, and **MySQL**. This project simulates real-world airline operations including flight search, booking, seat management, and online check-in, with separate roles for **Users** and **Admins**.

---

## 📖 About the Project

**SkyWings Airlines** is a web-based flight booking application designed to demonstrate practical backend development, relational database design, and secure authentication flows. The system covers the complete lifecycle of an airline reservation process — from flight scheduling to booking management.

This project was built as a learning-focused, real-world simulation to strengthen backend, database, and API development skills.

---

## ✨ Features

### 👤 User Features

* Secure user registration and login using **JWT authentication**
* Search flights by origin, destination, date, and passenger count
* Book flights with passenger details and seat selection
* View booking history and cancel bookings
* Download tickets
* Online check-in simulation
* Personalized user dashboard

### 🛡️ Admin Features

* Admin dashboard with booking and revenue statistics
* Create, update, schedule, and cancel flights
* Manage aircraft fleet (e.g., Boeing, Airbus)
* View and manage users and bookings

---

## 🛠️ Technology Stack

### Frontend

* HTML5
* CSS3 (Vanilla)
* JavaScript (ES6+)
* Responsive, mobile-first design

### Backend

* **Node.js** – Runtime environment
* **Express.js** – REST API framework
* **MySQL** – Relational database
* **JWT** – Stateless authentication
* **Bcrypt** – Password hashing

---

## 🚀 Getting Started

Follow the instructions below to run the project locally.

### Prerequisites

* Node.js (v14 or higher)
* MySQL Server (v8.0 or higher)
* npm

---

## 📦 Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/skywings-airlines.git
cd skywings-airlines
```

### 2️⃣ Install Dependencies

```bash
npm install
```

### 3️⃣ Environment Configuration

Create a `.env` file in the root directory:

```env
DB_HOST=localhost
DB_PORT=3306
DB_USER=root
DB_PASSWORD=your_mysql_password
DB_NAME=skywings_airlines
PORT=3000
JWT_SECRET=your_jwt_secret_key
```

### 4️⃣ Database Setup

Import the database schema:

```bash
mysql -u root -p < sql/schema.sql
```

Initialize sample data:

```bash
node scripts/initialize_database.js
node scripts/insert_comprehensive_data.js
```

### 5️⃣ Run the Server

```bash
npm start
```

### 6️⃣ Open in Browser

Visit:

```
http://localhost:3000
```

---

## 🔐 Test Credentials

### Admin Account

* **Email:** [admin@skywings.com](mailto:admin@skywings.com)
* **Password:** admin123

### User Account

* **Email:** [user1@skywings.com](mailto:user1@skywings.com)
* **Password:** user1123

---

## 📚 What I Learned

* Designing **normalized relational database schemas**
* Implementing **role-based access control (RBAC)**
* Handling **ACID-compliant transactions** in MySQL
* Writing complex **SQL joins and subqueries**
* Building secure and scalable **RESTful APIs**
* Managing real-world booking logic and edge cases

---

## 📌 Future Improvements

* Payment gateway integration
* Email notifications for bookings and check-ins
* Advanced seat map visualization
* Deployment using Docker and cloud services

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome.
Feel free to fork the repository and submit a pull request.


---

## 👤 Author

"Hassaan Ahmad"

---

⭐ If you like this project, please give it a star!

