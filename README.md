# 🧑‍💻 Fully Functional Social Media Web App

This is a Django-based social media web application created by **Anurag Kumar Jha**.  
It supports user registration, posting, liking, commenting, following, and more.

---

## 🚀 Features

- User Authentication (Login/Register/Logout)
- Post Creation & Feed
- Like, Comment, and Follow/Unfollow system
- Profile management
- Responsive UI

---

## 🛠️ Tech Stack

- Backend: Django (Python)
- Frontend: HTML, CSS, JavaScript
- Database: SQLite (default)
- Auth: Django's built-in User system

---

## ⚙️ Setup Instructions

### 🔽 Step 1: Clone the Repo

```bash
git clone https://github.com/Anuragzha/Fully_Functional_Social_Media.git
cd Fully_Functional_Social_Media

# Create virtual environment
python -m venv venv

# Activate it
# On Windows:
venv\Scripts\activate

# On Mac/Linux:
source venv/bin/activate


pip install -r requirements.txt

#do after installing reqts.
cd socials



#migration for databases
python manage.py makemigrations
python manage.py migrate

#Create Admin User (Optional)
python manage.py createsuperuser

#Start the Server
python manage.py runserver


Visit http://127.0.0.1:8000 in your browser!
