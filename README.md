# 🏥 Clinic Management System

![Dashboard](dashboard.png)

A web-based **Clinic Management System** built using **Flask** and **SQLAlchemy** to streamline the management of patients, doctors, appointments, and visits with a clean, responsive dashboard.

---

## ✨ Features

- 👥 **Patient Management** – Add, view, and update patient records.
- 🩺 **Doctor Management** – Track doctor details and highlight top performers.
- 📅 **Appointment Scheduling** – Create, modify, and delete appointments.
- 📋 **Visit Records** – Maintain patient visit history with appointment linkage.
- 📊 **Admin Dashboard** – Overview of key statistics: patients, doctors, visits.
- 🔔 **User Notifications** – Real-time feedback with success/error messages.
- 🔒 **Secure Routes** – Only authorized users can perform CRUD operations.
- 🗃️ **Database Integration** – SQLAlchemy ORM with SQLite/MySQL support.

---

## 🛠️ Tech Stack

| Tech              | Description                        |
|-------------------|------------------------------------|
| `Python 3.x`      | Programming Language                |
| `Flask`           | Lightweight Web Framework          |
| `SQLAlchemy`      | ORM for Database Interaction       |
| `Flask-Migrate`   | Database Migrations                |
| `Jinja2`          | Templating Engine                  |
| `HTML5/CSS3`      | Markup & Styling                   |
| `Bootstrap`       | Responsive Design                  |
| `Git & GitHub`    | Version Control & Collaboration    |

---

## 🚀 Installation & Setup

Follow these steps to run the project locally:

```bash
# 1. Clone the repository
git clone https://github.com/Roymahi/ClinicManagementSystem.git
cd ClinicManagementSystem

# 2. (Optional) Create and activate a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run the application
python app.py
