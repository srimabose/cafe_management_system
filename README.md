# ☕ Cafe Management System

This is a complete **Cafe Management System** built using **C# (.NET Framework)** and **SQL Server**. The application is designed to handle cafe operations like order processing, user and item management, and generating printable order summaries. It supports both **admin** and **guest** logins.

---

## 📌 Features

### 🔐 Login System
- Login with username and password for registered users
- Guest login available for placing orders without user management rights
- Role-based access: `Admin`, `Guest`

### 🛒 Order Management
- Browse and filter items by category: **Food** or **Beverage**
- Add items to cart and calculate total
- Checkout and place orders
- View and print order summary (includes seller name, order ID, date, total amount)

### 📦 Item Management
- Add, edit, update, and delete items
- View all available items
- Filter items by category

### 👥 User Management (Admin only)
- Add new users
- Edit and delete existing users
- View all users in the system

### 🧾 Order Summary
- View history of all placed orders
- Filter by date or user
- Print summary with full details:
  - Order Number
  - Seller/User
  - Date of Order
  - Total Bill

---

## 🧱 Database Schema

- **Users** (`id`, `username`, `password`, `role`)
- **Items** (`id`, `name`, `category`, `price`)
- **Orders** (`id`, `user_id`, `order_date`, `total_amount`)
- **OrderDetails** (`id`, `order_id`, `item_id`, `quantity`, `price`)

---

## 💻 Technologies Used

- **C# (.NET Framework)**
- **Windows Forms**
- **SQL Server**
- **ADO.NET** for database connectivity
- **PrintDocument & PrintPreviewDialog** for order summary printing

---

## 🚀 Getting Started

### 🛠 Prerequisites
- Visual Studio (with Windows Forms support)
- SQL Server or SQL Server Express

### ⚙️ Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/cafe-management-system.git
