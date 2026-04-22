# 🍽️ Restaurant POS System

## 📌 Overview
The Restaurant POS (Point of Sale) System is a web-based application developed using Django to manage restaurant operations efficiently. It helps in handling orders, managing menu items, and generating bills in a fast and organized way.

## 🚀 Features
- 🧾 Fast billing system  
- 🍽️ Menu management (Add, Update, Delete items)  
- 🛒 Order processing with multiple items  
- 💰 Automatic total calculation  
- 🗂️ Store order and transaction records  
- 🖥️ User-friendly interface for daily use  

## 🛠️ Tech Stack
- Backend: Python (Django)  
- Database: MySQL  
- Frontend: HTML, CSS, JavaScript  

## ⚙️ Installation & Setup

### 1. Clone the repository
```bash
git clone <your-repo-url>
cd Restaurant-POS-System
````

### 2. Create virtual environment

```bash id="p9x4ld"
python -m venv venv
venv\Scripts\activate
```

### 3. Install dependencies

```bash id="t6n8fs"
pip install -r requirements.txt
```

### 4. Apply migrations

```bash id="k3w1az"
python manage.py migrate
```

### 5. Run the development server

```bash id="u2m9qy"
python manage.py runserver
```

### 6. Open in browser

```id="j5c8vn"
http://127.0.0.1:8000/
```

## 📊 How It Works

1. Add menu items to the system
2. Select items to create an order
3. System calculates total automatically
4. Generate and display the final bill

## 🎯 Purpose

The goal of this project is to simplify restaurant operations by providing an efficient billing and order management system.

## 📌 Future Improvements

* Add table management system
* Integrate payment gateways
* Add user authentication (admin/staff)
* Generate printable invoices

## 👨‍💻 Author

**Darshan Kaladiya** - www.linkedin.com/in/darshan-kaladiya-968093346
