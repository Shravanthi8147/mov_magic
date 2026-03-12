# 🎬 Movie Magic - Online Movie Ticket Booking System

## 📌 Project Overview

Movie Magic is a web-based movie ticket booking system developed using **Python Flask** and deployed on **AWS EC2**.
The application allows users to browse movies, book tickets, make payments, and receive booking confirmations.

The system uses **AWS DynamoDB** as the database and **AWS SNS** for sending email notifications.

---

## 🏗️ Architecture

User Browser
↓
Flask Web Application (AWS EC2)
↓
AWS DynamoDB (Database)
↓
AWS SNS (Email Notifications)

---

## ⚙️ Technologies Used

* Python
* Flask
* HTML / CSS
* AWS EC2
* AWS DynamoDB
* AWS SNS
* GitHub

---

## 📂 Project Structure

```
mov_magic
│
├── app.py
├── templates
│   ├── index.html
│   ├── login.html
│   ├── signup.html
│   ├── dashboard.html
│   ├── booking.html
│   ├── payment.html
│   ├── confirmation.html
│   ├── profile.html
│   └── admin.html
│
└── static
    ├── css
    ├── js
    └── images
```

---

## 🚀 Features

* User Registration & Login
* Movie Listings
* Ticket Booking
* Payment Simulation
* Booking Confirmation
* Email Notification using AWS SNS
* Admin Dashboard to Manage Movies
* User Profile and Booking History

---

## 🛠️ Setup Instructions

### 1️⃣ Clone the Repository

```
git clone https://github.com/yourusername/mov_magic.git
cd mov_magic
```

### 2️⃣ Install Dependencies

```
pip install flask boto3 werkzeug
```

### 3️⃣ Configure AWS Services

Create the following AWS resources:

* DynamoDB Tables:

  * MovieMagic_Users
  * MovieMagic_Bookings
  * MovieMagic_Movies

* SNS Topic:

  * MovieTicketNotifications

* IAM Role:

  * Attach permissions for DynamoDB and SNS

---

### 4️⃣ Run the Application

```
python3 app.py
```

---

### 5️⃣ Open the Website

```
http://EC2-PUBLIC-IP:5000
```

Example:

```
http://54.163.xxx.xxx:5000
```

---

## 🔑 Default Admin Login

Email:

```
admin@moviemagic.com
```

Password:

```
admin123
```

---

## 📧 AWS Services Used

* Amazon EC2 – Application Hosting
* Amazon DynamoDB – Database
* Amazon SNS – Email Notifications
* IAM – Access Control

---

## 📊 Future Enhancements

* Online payment gateway integration
* Movie recommendation system
* Mobile responsive UI
* Seat selection interface

---

## 👩‍💻 Author

Team lead:  Shravanthi J

Team members names:
Nithya Shree S
G Nandini
Vennela kp
B Shravani

Project title:
Movie Magic: Smart Movie Ticket Booking System Using AWS

---

## 📜 License

This project is for educational and learning purposes.
