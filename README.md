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

### 🎛️ Admin Features
- **Admin Dashboard** - Comprehensive business overview
- **Category Management** - Create, edit, delete, and organize product categories
- **Product Management** - Full CRUD operations for product inventory
- **Order Management** - Process and confirm customer orders
- **Sales Analytics** - Beautiful charts and performance metrics
- **Customer Messages** - Handle customer inquiries
- **User Management** - Admin account management system

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
