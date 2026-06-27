# 🛒 Smart Grocery Hub

A modern **Django-based Grocery Store Management System** developed as a Final Year BCA Project.

This project provides a complete online grocery shopping platform where customers can browse products, manage carts, place orders, and administrators can manage products, categories, users, and orders.

---

## 🚀 Features

### 👤 Customer Panel

- User Registration & Login
- Forgot Password
- User Profile Management
- Multiple Address Management
- Wishlist
- Product Search & Filter
- Product Reviews & Ratings
- Shopping Cart
- Coupon Support
- Checkout System
- Order History
- Order Tracking
- Cancel & Reorder Orders

---

### 🛍 Product Management

- Categories
- Brands
- Product Images
- Product Details
- Stock Management
- Related Products
- Product Reviews

---

### 📦 Order Management

- Shopping Cart
- Checkout
- GST Calculation
- Delivery Charges
- Coupon Discount
- Payment Record
- Order Status Tracking

---

### 🔐 Authentication

- Register
- Login
- Logout
- Forgot Password
- Email Verification Ready

---

### ⚙ Admin Panel

- Manage Categories
- Manage Brands
- Manage Products
- Manage Customers
- Manage Orders
- Manage Coupons
- Manage Reviews
- Dashboard using Django Admin

---

## 🛠 Tech Stack

| Technology | Description |
|------------|-------------|
| Python | Programming Language |
| Django 5 | Backend Framework |
| SQLite | Default Database |
| MySQL | Production Database |
| HTML5 | Frontend |
| CSS3 | Styling |
| Bootstrap 5 | Responsive UI |
| JavaScript | Frontend Logic |
| Font Awesome | Icons |
| Pillow | Image Handling |
| django-environ | Environment Variables |

---

# 📂 Project Structure

```
SMART_GROCERY_HUB_PROJECT
│
├── smart_grocery_hub
│   ├── apps
│   │   ├── accounts
│   │   ├── core
│   │   ├── orders
│   │   └── store
│   │
│   ├── config
│   ├── static
│   ├── templates
│   ├── media
│   ├── manage.py
│   ├── requirements.txt
│   └── README.md
│
└── ROADMAP.md
```

---

# ⚙ Installation

## Clone Repository

```bash
git clone https://github.com/HIMADRI1062005/Smart-Grocery-Hub-project-.git

cd Smart-Grocery-Hub-project-
```

---

## Create Virtual Environment

Windows

```bash
python -m venv venv
venv\Scripts\activate
```

Linux / Mac

```bash
python3 -m venv venv
source venv/bin/activate
```

---

## Install Requirements

```bash
pip install -r requirements.txt
```

---

## Create Environment File

Copy

```bash
.env.example
```

to

```bash
.env
```

Update

- SECRET_KEY
- DATABASE
- EMAIL SETTINGS

---

## Database Migration

```bash
python manage.py makemigrations

python manage.py migrate
```

---

## Create Admin

```bash
python manage.py createsuperuser
```

---

## Seed Demo Data

```bash
python manage.py seed_demo_data
```

---

## Run Server

```bash
python manage.py runserver
```

Visit

```
http://127.0.0.1:8000/
```

Admin Panel

```
http://127.0.0.1:8000/admin/
```

---

# 🗄 Database

Default

- SQLite

Supported

- MySQL

Change

```
DB_ENGINE=sqlite
```

to

```
DB_ENGINE=mysql
```

inside

```
.env
```

---

# 📊 Future Roadmap

- Admin Dashboard
- Reports & Analytics
- Inventory Management
- POS Billing
- Online Payments
- Delivery Management
- CRM System
- Loyalty Program
- Multi Store Support
- AI Recommendation System
- AI Chatbot

---

# 📸 Screenshots

Add screenshots here

Example

```
Home Page

Login Page

Cart

Checkout

Admin Dashboard
```

---

# 📚 Academic Deliverables

- Software Requirement Specification (SRS)
- ER Diagram
- System Architecture
- Project Report
- PowerPoint Presentation
- Viva Questions & Answers

---

# 👨‍💻 Developer

**Himadri Bera**

BCA Final Year Student

GitHub

https://github.com/HIMADRI1062005

LinkedIn

https://www.linkedin.com/in/himadri-bera/

---

# ⭐ Support

If you like this project,

⭐ Star the repository.

---

# 📄 License

This project is developed for educational and learning purposes.