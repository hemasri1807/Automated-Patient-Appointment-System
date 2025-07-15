# 🏥 Automated Patient Appointment System

A full-stack web application that allows patients to book appointments with doctors, receive automated reminders, and check real-time doctor availability. Designed to streamline the scheduling process for clinics and healthcare providers.

---

## 🚀 Overview

Manual appointment scheduling is time-consuming, error-prone, and lacks scalability. This project automates the process using modern web technologies, a relational database, and efficient backend logic — improving both patient convenience and clinic efficiency.

---

## 🌟 Features

- 📅 **Online Appointment Booking**: Patients can view available time slots and book instantly.
- ⏰ **Automated Reminders**: Email/SMS alerts before appointment time.
- 🩺 **Doctor Dashboard**: Doctors can view upcoming appointments and availability.
- 🔄 **Real-Time Availability**: Booking system syncs with doctor schedules dynamically.
- 🧠 **Test Data & Trend Analysis**: Integrated with GPT-generated fake patient records and SQL analysis of booking trends.

---

## 🧰 Technologies Used

- **Frontend**: HTML, CSS, JavaScript, Bootstrap
- **Backend**: Flask / Node.js (choose one based on your implementation)
- **Database**: PostgreSQL (normalized to 3NF)
- **Tools**: pgAdmin, ERD tools, Postman
- **Testing**: Manual test cases using GPT-generated data

---

## 🗂️ Project Structure

```bash
appointment-system/
├── backend/
│   ├── app.py or server.js
│   ├── models/
│   └── routes/
├── frontend/
│   ├── index.html
│   └── dashboard.html
├── database/
│   ├── schema.sql
│   └── ERD.png
├── test_data/
│   └── fake_patients.csv
├── requirements.txt or package.json
└── README.md
