# 🎬 Movie Magic - Smart Movie Ticket Booking System

This is a Flask-based web application for booking movie tickets online. It supports user registration, login, movie search, booking system, admin panel, and password recovery with AWS integration.

## 🚀 Features

- User Authentication (Register/Login/Logout)
- Movie Listing and Search
- Movie Ticket Booking
- Admin Booking Dashboard
- Forgot Password via Email Verification
- AWS Integration:
  - **DynamoDB** for storing users and bookings
  - **SNS** for sending password recovery verification code

## 🛠 Technologies Used

- Python 3.9
- Flask
- HTML, CSS, Bootstrap
- AWS EC2, DynamoDB, SNS
- GitHub for version control

## 📁 Project Structure

MovieMagic/
│
├── app.py # Main Flask application
├── templates/ # HTML pages (login, register, movies, book, etc.)
├── static/ # CSS, JS, Images
├── requirements.txt # Python dependencies
└── README.md # Project documentation



## 💡 Setup Instructions (Local)

1. Clone the repository:
   ```bash
   git clone https://github.com/deepthi-kurimeti743725/awsproject.git
   cd awsproject
Install dependencies:


pip install -r requirements.txt
Run the Flask app:


python app.py
Open your browser and go to:

cpp
http://3.92.65.120:5000
☁️ Cloud Deployment (AWS)
EC2 Instance: Amazon Linux 2, t2.micro

IAM Role: MovieMagic_role with AmazonDynamoDBFullAccess and AmazonSNSFullAccess

DynamoDB Tables:

MovieMagic_Users (Partition key: Email)

MovieMagic_Bookings (Partition key: Bookingid)

SNS Topic: MovieTicketNotifications with confirmed email subscriber

✅ Status
🎉 Successfully deployed both locally and on AWS EC2 with full functionality.

📬 Contact
Developer: Deepthi Kurimeti
📧 Email: deepthikurimeti37@gmail.com
🔗 GitHub: @deepthi-kurimeti743725

Made with 💖 for learning & deployment on AWS

yaml

