FreshKart is a web-based marketplace platform that connects farmers directly with customers. The main goal of this project is to eliminate intermediaries in the agricultural supply chain so that farmers can sell their products directly and customers can purchase fresh farm products at fair prices.

This platform allows farmers to manage their products, customers to browse and order products, and administrators to monitor and control the system.

The project is developed using Flask for backend development and SQLite for database management.
Purpose of the Project

The main objective of this project is to create a digital platform that supports farmers by providing direct market access and helps customers easily purchase fresh agricultural products online.
🚀 Features
👤 User Authentication

Farmer and Customer registration

Secure login system

Role-based access (Farmer / Customer / Admin)

👨‍🌾 Farmer Dashboard

Farmers can:

Add products

Upload product images

Set price and quantity

Edit or delete products

View customer orders

Mark orders as delivered

🛒 Customer Marketplace

Customers can:

Browse all available farm products

View product details and images

Select product quantity

Add products to cart

Place orders

🛍 Cart System

Customers can save items in cart

Order products anytime from cart

📦 Order Management

Farmers receive order notifications

Farmers can update delivery status

Customers can track ordered items

🛠 Admin Dashboard

Admin can:

Approve or reject farmer registrations

View total farmers and customers

Monitor total products sold

Track platform activity

🛠 Technologies Used

Python

Flask

SQLite

HTML

CSS

JavaScript

📂 Project Structure
FreshKart
│
├── app.py
├── database.db
├── requirements.txt
├── .env
│
├── templates
│   ├── index.html
│   ├── auth.html
│   ├── products.html
│   ├── cart.html
│   ├── farmer_dashboard.html
│   ├── add_product.html
│   └── admin_dashboard.html
│
├── static
│   └── style.css
│
└── uploads
    └── product_images
⚙️ Installation and Setup
1️⃣ Clone the Repository
git clone https://github.com/yourusername/freshkart.git
2️⃣ Navigate to the Project Folder
cd freshkart
3️⃣ Create Virtual Environment
python -m venv env
4️⃣ Activate Virtual Environment

Windows

env\Scripts\activate

Mac/Linux

source env/bin/activate
5️⃣ Install Required Packages
pip install -r requirements.txt
6️⃣ Run the Application
python app.py
7️⃣ Open in Browser
http://127.0.0.1:5000
🎯 Objectives of the Project

Provide a direct marketplace for farmers

Reduce dependency on middlemen

Ensure fair pricing for farmers

Provide fresh products to customers

Create a simple digital agriculture platform

🔮 Future Improvements

Online payment integration

Order tracking system

Mobile responsive design

Farmer analytics dashboard

Notifications for orders

👩‍💻 Author

Anvitha Piriya
