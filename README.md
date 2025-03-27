AnuLink – A Next-Gen Social Media Platform

AnuLink is a futuristic social media platform designed to enhance digital interaction. It provides users with a seamless experience to create accounts, share posts, follow other users, engage with content, and receive smart follow suggestions. With a modern design and powerful backend, AnuLink brings a fresh perspective to online social networking.
Key Features:

    ✅ User Authentication – Secure login and signup system.

    ✅ Post Creation & Media Upload – Share thoughts, images, and videos.

    ✅ Follow System – Connect with other users by following them.

    ✅ Interactive Feed – Personalized posts from followed accounts.

    ✅ Like & Comment System – Engage with posts dynamically.

    ✅ Follow Suggestions – Smart recommendations for new connections.

    ✅ Admin Panel – Manage users and content easily.

Technology Stack:

    Backend: Django (Python)

    Frontend: HTML, CSS, JavaScript

    Database: SQLite (can be scaled to PostgreSQL)

    Authentication: Django Auth System

    Media Handling: Django ImageField & Pillow

Installation & Setup

Follow these steps to set up AnuLink on your local system:
1. Create and Activate Virtual Environment

python -m venv venv
venv\Scripts\activate

2. Install Required Dependencies

pip install django-filter
pip install django-ckeditor
pip install Pillow
pip install django-crispy-forms
pip install Django

3. Run Migrations and Setup Database

python manage.py makemigrations
python manage.py migrate

4. Create Superuser for Admin Access

python manage.py createsuperuser

(Enter username, email, and password as prompted)

5. Start the Server

python manage.py runserver

Now, open http://127.0.0.1:8000/ in your browser to access AnuLink.

Conclusion
AnuLink is an interactive and modern social media platform that provides a smooth and engaging experience for users. Whether you're sharing posts, following friends, or exploring new content, AnuLink makes digital networking effortless.
