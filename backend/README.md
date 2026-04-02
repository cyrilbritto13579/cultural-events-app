# Cultural Events Booking - Backend ⚙️

The Node.js and Express backend for the Cultural Events Booking System.

## ✨ Features

-   **RESTful API**: Standard HTTP methods for managing events, users, and bookings.
-   **JWT Authentication**: Secure stateless authentication for users and admins.
-   **Sequelize ORM**: Powerful database management with MySQL.
-   **Role-Based Access**: Middleware to protect sensitive administrative routes.
-   **Automatic Synchronization**: Synchronizes database models with MySQL tables on startup.

## 🛠️ Tech Stack

-   **Node.js**: Asynchronous JavaScript runtime.
-   **Express.js**: Minimalist web framework.
-   **Sequelize**: Modern TypeScript and Node.js ORM for SQL.
-   **MySQL**: Relational database storage.
-   **JWT**: Token-based security and authorization.
-   **Bcrypt.js**: Secure password hashing.

## 🏁 Getting Started

### Prerequisites

-   MySQL Server.
-   Root project dependencies installed (`npm run install:all`).

### Configuration

Ensure the `.env` file exists in the `backend` directory.

### Running the Backend

From the root directory:
```bash
npm run dev --prefix backend
```
Or from the `backend` folder:
```bash
npm run dev
```

The server will run at [http://localhost:5000](http://localhost:5000).

## 📂 Structure

-   `config/`: Database connection and Sequelize instance.
-   `controllers/`: API route handlers.
-   `models/`: Sequelize data models (User, Event, Booking).
-   `routes/`: API endpoint definitions.
-   `middleware/`: Auth and RBAC logic.

---
*For full project setup including the frontend and database, see the [Root README](../README.md).*
