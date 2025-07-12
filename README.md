# 🏫 Hostel Leave Management System

A web-based Django application that allows hostel students to apply for leave and wardens/admins to manage leave requests efficiently. Built using Django, this system streamlines leave approvals, enhances communication between students and wardens, and maintains a clear record of leave history.

---

## 🚀 Features

- ✅ Student Registration & Secure Login
- 📝 Leave Application Form
- 🔐 Admin/Warden Login & Dashboard
- 📋 Leave Approval/Rejection Panel
- 🏢 Department Management
- 🧑‍🏫 Role-based Access (Student/Admin)
- 🕒 Timestamps for Leave Applications
- 📦 Modular App Structure

---

## 🛠️ Tech Stack

| Layer      | Technology            |
|------------|------------------------|
| Backend    | Python, Django         |
| Database   | SQLite (default)       |
| Frontend   | HTML, CSS (Django Templating) |
| Other Tools| Django Admin, Model Managers, Virtualenv |

---

## ⚙️ Setup Instructions

Follow these steps to run the project on your local machine:

### 🔁 1. Clone the Repository

```bash
git clone https://github.com/your-username/hostel-leave-management.git
cd hostel-leave-management

🐍 2. Create & Activate Virtual Environment

python -m venv env
env\Scripts\activate         # For Windows
# source env/bin/activate   # For macOS/Linux



📦 3. Install Required Packages

pip install -r requirements.txt

🗃️ 4. Apply Migrations

python manage.py makemigrations
python manage.py migrate

👤 5. Create Superuser (Admin Login)
python manage.py createsuperuser
Enter username, email, and password when prompted.

▶️ 6. Run the Development Server
python manage.py runserver
Then open your browser and visit:
http://127.0.0.1:8000/

👤 Admin Panel
To manage students, leave requests, and departments, login at:

http://127.0.0.1:8000/admin/
Use your superuser credentials to access the admin dashboard.

📁 Project Structure

Hostel-Leave-Portal/
├── student/              # Student app
├── leave/                # Leave request handling
├── templates/            # HTML templates
├── static/               # CSS, JS, images
├── db.sqlite3            # Local database (optional to track in Git)
├── manage.py
├── requirements.txt
├── README.md
└── .gitignore


🙋‍♀️ Maintainer
Kavya Gouravam
📧 kavyagouravam@gmail.com
🌐 GitHub: https://github.com/GouravamKavya