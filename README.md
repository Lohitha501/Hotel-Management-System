# 🏨 StayFlow - Hotel Management System

StayFlow is a web-based Hotel Management System developed using Python and Flask. It helps manage hotel bookings, guests, rooms, hotels, authentication, and cancellations through a simple web interface.

## 📌 Features

- 🏠 Hotel and room browsing
- 🔐 User registration and login
- 👤 Guest dashboard
- 🧑‍💼 Manager dashboard
- 🛠️ Admin dashboard
- 🛏️ Room and hotel management
- 📅 Hotel room booking
- ❌ Booking cancellation
- 📧 Email-related services
- 🗄️ Supabase PostgreSQL database
- 📊 Demo data seeding
- 🖼️ Hotel and room images
- 📱 Simple and user-friendly web interface

## 🛠️ Technologies Used

- **Python**
- **Flask**
- **HTML**
- **CSS**
- **PostgreSQL**
- **Supabase**
- **Psycopg**
- **Jinja2**
- **Git & GitHub**

## 📂 Project Structure

```text
Hotel-Management-System/
│
├── app.py
├── auth_tools.py
├── common.py
├── database.py
├── email_service.py
├── mail_test.py
├── seed_demo_data.py
├── stayflow_auth.py
├── requirements.txt
├── .gitignore
│
├── static/
│   └── app.css
│
├── templates/
│   ├── admin_dashboard.html
│   ├── guest_dashboard.html
│   ├── home.html
│   ├── hotel_detail.html
│   ├── login.html
│   ├── manager_dashboard.html
│   └── register.html
│
├── supabase/
│   └── schema.sql
│
└── uploads/
    └── Hotel and room images
