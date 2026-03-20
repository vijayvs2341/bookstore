📚 Online Bookstore (Django Project)

## 🚀 Download Project

👉 [Click here to download ZIP](https://github.com/vijayvs2341/bookstore/archive/refs/tags/v1.0.zip)

---

## 📊 Changelog

👉 https://github.com/vijayvs2341/bookstore/commits/v1.0

A fully functional E-Commerce Web Application built using Django, HTML, CSS, JavaScript.

🚀 Features

🛒 Add to Cart (AJAX-based)

📦 Checkout System

📧 Email Invoice with Product Images

⭐ Product Reviews & Ratings

🔄 Cart Update (Increase / Decrease Quantity)

🧾 Order Tracking System

📊 Dynamic Product Listing

🎨 Modern UI with Background Effects

🛠️ Tech Stack

Backend: Django (Python)

Frontend: HTML, CSS, JavaScript, Bootstrap

Database: SQLite

Email Service: Gmail SMTP

Media Handling: Django Media Files

📂 Project Structure
bookstore/
│
├── store/                 # Main App
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│
├── templates/            # HTML Templates
├── static/               # CSS, JS
├── frontend/media/       # Uploaded Images
├── db.sqlite3
├── manage.py
⚙️ Installation & Setup
1️⃣ Clone Repository
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
2️⃣ Create Virtual Environment
python -m venv venv
venv\Scripts\activate   # Windows
3️⃣ Install Dependencies
pip install -r requirements.txt
4️⃣ Apply Migrations
python manage.py makemigrations
python manage.py migrate
5️⃣ Run Server
python manage.py runserver
📧 Email Configuration

Update in settings.py:

EMAIL_HOST = 'smtp.gmail.com'
EMAIL_PORT = 587
EMAIL_HOST_USER = 'your_email@gmail.com'
EMAIL_HOST_PASSWORD = 'your_app_password'
EMAIL_USE_TLS = True
📸 Screenshots

Home Page

Product Detail Page

Cart Page

Order Success Page

Email Invoice

🎯 Future Improvements

💳 Payment Gateway (Razorpay / Stripe)

📱 Responsive Mobile UI

🧑‍💼 Admin Dashboard Enhancements

📄 PDF Invoice Download

👨‍💻 Author

Vijay VS
Frontend Developer | Django Developer
