# COLLEGE-ERP-MANAGER

🎓 College ERP Manager

A College ERP (Enterprise Resource Planning) System built with Django, designed to streamline academic and administrative workflows such as student management, faculty management, course enrollment, attendance, exams, and more.

🚀 Features

👩‍🎓 Student Management – registration, profiles, and academic records

👨‍🏫 Faculty Management – faculty profiles, subject allocation

📚 Course & Subject Management – create, update, and assign courses

📝 Attendance Tracking – daily attendance for students

🧾 Examination Module – marks entry, grade generation, report cards

💬 Notice Board & Announcements

🔐 Role-Based Access Control – admin, faculty, student dashboards

🛠️ Tech Stack

Backend: Django, Django REST Framework

Frontend: HTML, CSS, Bootstrap / Tailwind (customizable)

Database: PostgreSQL / MySQL / SQLite (dev)

Authentication: Django Auth (with roles)

Deployment: Gunicorn, Nginx, Docker (optional)

1. Clone the Repository
git clone https://github.com/harshu-cyber/college-erp.git
cd college-erp

2. Create Virtual Environment
python -m venv venv
source venv/bin/activate  # On Linux/Mac
venv\Scripts\activate     # On Windows

3. Install Dependencies
pip install -r requirements.txt

4. Setup Environment Variables

Copy .env.example to .env and update values:

DEBUG=True
SECRET_KEY=your_secret_key
DATABASE_URL=sqlite:///db.sqlite3

5. Run Migrations
python manage.py migrate

6. Create Superuser
python manage.py createsuperuser

7. Run Development Server
python manage.py runserver


App will be available at: http://127.0.0.1:8000/

🧪 Running Tests
python manage.py test

📦 Deployment

Use Gunicorn + Nginx for production

Or run with Docker:

docker build -t college-erp .
docker run -p 8000:8000 college-erp

🤝 Contributing

Fork the repo

Create a new branch (feature/new-feature)

Commit changes

Push and open a Pull Request

📜 License

This project is licensed under the MIT License.


