# 🛒 E-Commerce Web Application (Django 5.2)

A **full-featured e-commerce platform** built with **Python Django 5.2**, offering a seamless shopping experience with robust **admin management, product catalog, order processing, mobile payment integration, and sales analytics**.

---

## 🌟 Features

### 👤 Customer Features

* 🔐 **User Registration & Authentication** – Secure customer accounts
* 🛍 **Product Browsing** – Search and filter products by category
* 🛒 **Shopping Cart** – Add, remove, and manage product quantities
* 💳 **Checkout System** – Complete orders with shipping info
* 📍 **Bangladesh Location Integration** – Divisions, districts & thanas
* 📱 **Mobile Payment Support** – bKash, Rocket, Nagad, Upay
* 📦 **Order Tracking** – View order history & statuses
* 📞 **Customer Support Messaging** – Contact the admin directly

📸 **Screenshots** <img width="954" height="394" alt="Screenshot_1" src="https://github.com/user-attachments/assets/3011b0b9-2c8e-4b91-9f8e-14a6f9490df2" />
<img width="1366" height="768" alt="Screenshot_2" src="https://github.com/user-attachments/assets/e39892c7-1c27-4ea6-8f8b-874138ab4725" />
<img width="1319" height="663" alt="Home_page-1" src="https://github.com/user-attachments/assets/0e56ea72-3aa2-4e4f-8c6e-167d385bc3b4" />
<img width="1309" height="646" alt="Home_page-2" src="https://github.com/user-attachments/assets/c2ff2d6c-d99c-45b6-9a5e-f975368dacb5" />
<img width="1319" height="695" alt="Add_to_cart-1" src="https://github.com/user-attachments/assets/577f5caa-9c59-4748-b576-092e679099d1" />
<img width="680" height="654" alt="Add_to_cart-2" src="https://github.com/user-attachments/assets/405835b0-c491-4018-946f-7558b48dd1d8" />
<img width="461" height="592" alt="confirm_status" src="https://github.com/user-attachments/assets/02efba2c-8799-4e05-bf26-68fb81c96c67" />
<img width="695" height="641" alt="View_all_order" src="https://github.com/user-attachments/assets/d07b4b70-d9f7-4821-b5b2-6206f558ec00" />

---

### 🛠️ Admin Features

* 📊 **Admin Dashboard** – Business performance overview
* 🗂️ **Category Management** – Add, edit & delete categories
* 📦 **Product Management** – Full CRUD inventory management
* 📑 **Order Management** – Confirm & process orders
* 📈 **Sales Analytics** – Daily, monthly, yearly insights
* 💬 **Customer Messages** – Handle user inquiries
* 👨‍💼 **User Management** – Manage admin accounts

📸 **Screenshots** <img width="1245" height="611" alt="admin_dashboard" src="https://github.com/user-attachments/assets/15db0d6d-af49-465f-9547-89d207135080" /> <img width="695" height="638" alt="Manage_Category" src="https://github.com/user-attachments/assets/7c3d1f02-5c12-4a00-8a69-c7d5ed2fcbe8" /> <img width="806" height="629" alt="Product_Category" src="https://github.com/user-attachments/assets/67623d6b-c966-4702-a619-b5cab2d84dbb" /> <img width="723" height="607" alt="Manage_Customer" src="https://github.com/user-attachments/assets/c17c7ce3-2c1d-4ced-a7b1-5a91dd19e7c4" /> <img width="1224" height="602" alt="Manage_order" src="https://github.com/user-attachments/assets/90df4e4b-deb0-44ee-85bb-1205ed7b9eec" /> <img width="1216" height="618" alt="Daily_order_report" src="https://github.com/user-attachments/assets/f7df230d-08e4-4004-98db-cb837f202322" /> <img width="1093" height="639" alt="monthly_order_report" src="https://github.com/user-attachments/assets/363fd912-c753-4b82-b8a7-ffe6e958b879" /> <img width="1137" height="639" alt="sales_Statistics" src="https://github.com/user-attachments/assets/5f244d6a-377e-47b0-bca8-b105afc252a6" /> <img width="1023" height="537" alt="Users_Message" src="https://github.com/user-attachments/assets/23bb071e-6ace-4f57-8eb8-04ccaf84f0e5" />

---

## 🚀 Tech Stack

* **Backend**: Python 3.13, Django 5.2.5
* **Database**: SQLite3 (development)
* **Frontend**: HTML5, CSS3, Bootstrap 5, JavaScript
* **Charts & Analytics**: Chart.js
* **Authentication**: Django built-in auth system
* **Image Handling**: Pillow
* **Timezone**: Asia/Dhaka

---

## ⚙️ Installation & Setup

### 📌 Prerequisites

* Python **3.10+**
* pip package manager
* Git

### 🛠 Steps to Run

```bash
# 1. Clone Repository
git clone https://github.com/biswasbn99/E-Commerce-project-Using-Python-Django-Framework.git
cd E-Commerce-project-Using-Python-Django-Framework

# 2. Create Virtual Environment
python -m venv .venv
# Activate
.venv\Scripts\activate  # Windows
source .venv/bin/activate  # Mac/Linux

# 3. Install Dependencies
pip install django==5.2.5 pillow

# 4. Setup Database
python manage.py migrate

# Create Admin User
python manage.py create_admin_user admin@example.com admin yourpassword123

# Load sample data (optional)
python manage.py create_sample_categories

# 5. Run Server
python manage.py runserver
```

📍 Visit **[http://127.0.0.1:8000/](http://127.0.0.1:8000/)** to access the app.

---

## 📂 Project Structure

```
ECommerce-main/
├── adminpanel/       # Admin management system
│   ├── management/   # Custom admin commands
│   ├── templates/    # Admin templates
│   ├── models.py     # Admin models
│   ├── views.py      # Admin views
│   └── urls.py       # Admin URLs
├── homepage/         # Customer-facing app
│   ├── management/   # Commands
│   ├── templates/    # Frontend templates
│   ├── models.py     # Products, Orders, Categories
│   ├── views.py      # Website logic
│   └── urls.py       # Frontend URLs
├── myproject1/       # Django project settings
├── media/            # Uploaded media files
├── static/           # CSS, JS, images
├── db.sqlite3        # Database
└── manage.py         # Django CLI
```

---

## 📊 Key Highlights

### 🛒 Shopping Cart

* Session-based cart management
* Real-time updates & total calculation

### 📍 Bangladesh Location System

* 8 divisions, 64 districts
* Thana/upazila cascading dropdowns (AJAX-powered)

### 💳 Mobile Payments

* bKash, Rocket, Nagad, Upay integration

### 📈 Sales Analytics

* Daily/Monthly/Yearly insights
* Best-selling products tracking
* Interactive Chart.js graphs

### 🎨 UI/UX

* Glassmorphism & modern design
* Bootstrap 5 responsive layout
* Font Awesome icons

---

## 🔐 Admin Access

```bash
# Method 1: Interactive
python manage.py create_admin

# Method 2: Direct
python manage.py create_admin_user email@example.com username password123

# Method 3: List existing admins
python manage.py list_admins
```

### Admin URLs

* 🔑 Login → `/adminpanel/login/`
* 📊 Dashboard → `/adminpanel/dashboard/`
* 📦 Products → `/adminpanel/products/`
* 📑 Orders → `/adminpanel/orders/`
* 📈 Analytics → `/adminpanel/sales-overview/`

### Customer URLs

* 🏠 Homepage → `/`
* 🛍 Products → `/products/`
* 🛒 Cart → `/cart/`
* 💳 Checkout → `/checkout/`
* 📞 Contact → `/contact/`

---

## 🛡️ Security & Performance

* ✅ CSRF protection
* ✅ SQL injection prevention (Django ORM)
* ✅ Secure password hashing
* ✅ Optimized queries & caching
* ✅ Image optimization with Pillow

---

## 📞 Contact & Support

* GitHub: [**biswasbn99**](https://github.com/biswasbn99)
* Issues: [GitHub Issues](https://github.com/biswasbn99/E-Commerce-project-Using-Python-Django-Framework/issues)

---

## 📝 License

This project is **open-source** under the [MIT License](LICENSE).

---

## 🙏 Acknowledgments

* Django Framework Community
* Bootstrap 5
* Chart.js
* Font Awesome

⭐ If you like this project, don’t forget to **star it on GitHub**!

👉 Do you also want me to add a **"Future Improvements / Roadmap"** section (like wishlist features: coupon system, shipping tracking, etc.) to make your README even more professional?
