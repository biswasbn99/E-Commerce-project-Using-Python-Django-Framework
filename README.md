
# 🛒 E-Commerce Project Using Python Django Framework

1.A comprehensive e-commerce web application built with Django 5.2, featuring a complete online shopping experience with admin panel, user authentication, product management, and order processing.

## 🌟 Features

### 🛍️ Customer Features
- **User Registration & Authentication** - Secure customer account management
- **Product Browsing** - Browse products by categories with search functionality
- **Shopping Cart** - Add/remove products with quantity management
- **Checkout System** - Complete order placement with detailed shipping information
- **Bangladesh Location Integration** - 8 divisions, 64 districts, and thana selection
- **Mobile Payment Integration** - bKash, Rocket, Nagad, Upay payment options
- **Order Tracking** - View order history and status
- **Contact System** - Customer support messaging
- 
### 🛍️ Customer Features(Some Feature ScreenShot):

  <img width="1319" height="663" alt="Home_page-1" src="https://github.com/user-attachments/assets/0e56ea72-3aa2-4e4f-8c6e-167d385bc3b4" />
<img width="1309" height="646" alt="Home_page-2" src="https://github.com/user-attachments/assets/c2ff2d6c-d99c-45b6-9a5e-f975368dacb5" />
<img width="1319" height="695" alt="Add_to_cart-1" src="https://github.com/user-attachments/assets/577f5caa-9c59-4748-b576-092e679099d1" />
<img width="680" height="654" alt="Add_to_cart-2" src="https://github.com/user-attachments/assets/405835b0-c491-4018-946f-7558b48dd1d8" />
<img width="461" height="592" alt="confirm_status" src="https://github.com/user-attachments/assets/02efba2c-8799-4e05-bf26-68fb81c96c67" />
<img width="695" height="641" alt="View_all_order" src="https://github.com/user-attachments/assets/d07b4b70-d9f7-4821-b5b2-6206f558ec00" />

### 🎛️ Admin Features
- **Admin Dashboard** - Comprehensive business overview
- **Category Management** - Create, edit, delete, and organize product categories
- **Product Management** - Full CRUD operations for product inventory
- **Order Management** - Process and confirm customer orders
- **Sales Analytics** - Beautiful charts and performance metrics
- **Customer Messages** - Handle customer inquiries
- **User Management** - Admin account management system
- 
### 🎛️ Admin Features(Some Feature ScreenShot):
  <img width="1245" height="611" alt="admin_dashboard" src="https://github.com/user-attachments/assets/15db0d6d-af49-465f-9547-89d207135080" />
<img width="695" height="638" alt="Manage_Category" src="https://github.com/user-attachments/assets/7c3d1f02-5c12-4a00-8a69-c7d5ed2fcbe8" />
<img width="806" height="629" alt="Product_Category" src="https://github.com/user-attachments/assets/67623d6b-c966-4702-a619-b5cab2d84dbb" />
<img width="723" height="607" alt="Manage_Customer" src="https://github.com/user-attachments/assets/c17c7ce3-2c1d-4ced-a7b1-5a91dd19e7c4" />
<img width="1224" height="602" alt="Manage_order" src="https://github.com/user-attachments/assets/90df4e4b-deb0-44ee-85bb-1205ed7b9eec" />
<img width="1216" height="618" alt="Daily_order_report" src="https://github.com/user-attachments/assets/f7df230d-08e4-4004-98db-cb837f202322" />
<img width="1093" height="639" alt="monthly_order_report" src="https://github.com/user-attachments/assets/363fd912-c753-4b82-b8a7-ffe6e958b879" />
<img width="1137" height="639" alt="sales_Statistics" src="https://github.com/user-attachments/assets/5f244d6a-377e-47b0-bca8-b105afc252a6" />
<img width="1023" height="537" alt="Users_Message" src="https://github.com/user-attachments/assets/23bb071e-6ace-4f57-8eb8-04ccaf84f0e5" />

## 🚀 Technologies Used

- **Backend**: Python 3.13, Django 5.2.5
- **Database**: SQLite3 (Development)
- **Frontend**: HTML5, CSS3, Bootstrap 5, JavaScript
- **Charts**: Chart.js for analytics visualization
- **Authentication**: Django's built-in authentication system
- **Image Handling**: Pillow for image processing
- **Timezone**: Asia/Dhaka timezone support

## 📦 Installation & Setup

### Prerequisites
- Python 3.10 or higher
- pip package manager
- Git

### 1. Clone the Repository
```bash
git clone https://github.com/biswasbn99/E-Commerce-project-Using-Python-Django-Framework.git
cd E-Commerce-project-Using-Python-Django-Framework

2. Create Virtual Environment
# Windows
python -m venv .venv
.venv\Scripts\activate

# Linux/Mac
python -m venv .venv
source .venv/bin/activate

3. Install Dependencies
pip install django==5.2.5
pip install pillow

4. Database Setup
# Run migrations
python manage.py migrate

# Create admin user
python manage.py create_admin_user admin@example.com admin yourpassword123

# Load sample data (optional)
python manage.py create_sample_categories

5. Run the Server
python manage.py runserver

Visit http://127.0.0.1:8000/ to access the application.

🗂️ Project Structure
ECommerce-main/
├── adminpanel/                 # Admin panel Django app
│   ├── management/             # Custom management commands
│   ├── templates/              # Admin templates
│   ├── models.py              # Admin user model
│   ├── views.py               # Admin functionality
│   └── urls.py                # Admin URL patterns
├── homepage/                   # Main website Django app
│   ├── management/             # Management commands
│   ├── templates/              # Website templates
│   ├── models.py              # Product, Order, Category models
│   ├── views.py               # Website functionality
│   └── urls.py                # Website URL patterns
├── myproject1/                 # Django project settings
├── media/                      # User uploaded files
├── static/                     # Static files
├── db.sqlite3                  # Database file
└── manage.py                   # Django management script

🎯 Key Features Explained
🛒 Shopping Cart System
Session-based cart management
Real-time quantity updates
Price calculations with tax

📍 Bangladesh Location System
Complete 8 divisions coverage
64 districts with accurate mapping
Thana/upazila selection
AJAX-powered cascading dropdowns

💳 Payment Integration
Multiple mobile payment options
Visual payment method selection
Secure order processing

📊 Sales Analytics Dashboard
Revenue tracking (daily, weekly, monthly)
Order status distribution
Top-selling products analysis
Interactive charts and graphs
Modern glassmorphism design

🎨 Admin Panel
Clean, modern interface
Comprehensive product management
Order processing workflow
Customer message handling
Category management with bulk operations

🔐 Admin Access
Creating Admin Users

# Method 1: Interactive creation
python manage.py create_admin

# Method 2: Direct creation
python manage.py create_admin_user email@example.com username password123

# Method 3: List existing admins
python manage.py list_admins

Admin Panel URLs
Login: /adminpanel/login/
Dashboard: /adminpanel/dashboard/
Categories: /adminpanel/categories/
Products: /adminpanel/products/
Orders: /adminpanel/orders/
Analytics: /adminpanel/sales-overview/
Messages: /adminpanel/messages/

🌐 Main Application URLs
Homepage: /
Products: /products/
Cart: /cart/
Checkout: /checkout/
About: /about/
Contact: /contact/

📱 Mobile Responsive Design
Fully responsive across all devices
Mobile-first approach
Touch-friendly interface
Optimized for tablets and smartphones

🔧 Custom Management Commands
# Create admin users
python manage.py create_admin_user email username password

# List all admins
python manage.py list_admins

# Create sample categories
python manage.py create_sample_categories

# Create test orders (for development)
python manage.py create_test_orders

🎨 Design Highlights
Modern UI/UX - Clean, professional design
Glassmorphism Effects - Beautiful translucent elements
Smooth Animations - CSS transitions and hover effects
Interactive Charts - Chart.js powered analytics
Responsive Layout - Bootstrap 5 framework
Icon Integration - Font Awesome icons

📈 Performance Features
Optimized Queries - Efficient database operations
Image Optimization - Pillow-based image processing
Session Management - Secure user sessions
Cache Optimization - Minimal redundant operations

🛡️ Security Features
CSRF Protection - Built-in Django security
SQL Injection Prevention - ORM-based queries
Secure Authentication - Password hashing
Admin Access Control - Role-based permissions

🔄 Development Workflow
Local Development - SQLite database
Version Control - Git with GitHub
Clean Code Structure - Modular Django apps
Documentation - Comprehensive README

🚀 Deployment Ready
The project is structured for easy deployment with:

Environment-specific settings
Static files configuration
Media files handling
Database migration support

📞 Contact & Support
For questions, issues, or contributions:

GitHub: biswasbn99
Project Issues: GitHub Issues

📝 License
This project is open source and available under the MIT License.

🙏 Acknowledgments
Django Framework community
Bootstrap team for the CSS framework
Chart.js for beautiful analytics
Font Awesome for icons

⭐ If you find this project helpful, please give it a star on GitHub!

Built with ❤️ using Django


This README.md file provides:

1. **Complete project overview** with features
2. **Step-by-step installation** instructions
3. **Technology stack** details
4. **Project structure** explanation
5. **Admin and user guides**
6. **Custom commands** documentation
7. **Design highlights** and features
8. **Security and performance** notes
9. **Professional formatting** with emojis
10. **Contact information** and links

You can copy this entire content and paste it into your GitHub repository's README.md file!This README.md file provides:

1. **Complete project overview** with features
2. **Step-by-step installation** instructions
3. **Technology stack** details
4. **Project structure** explanation
5. **Admin and user guides**
6. **Custom commands** documentation
7. **Design highlights** and features
8. **Security and performance** notes
9. **Professional formatting** with emojis
10. **Contact information** and links

You can copy this entire content and paste it into your GitHub repository's README.md file!
