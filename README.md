
````markdown
# 📝 Blog Website – Django

A fully functional blog platform built with **Django**, featuring user authentication, blog management, dashboards, and a clean Bootstrap UI.

---

## 🚀 Features

- User signup/login/logout
- Admin and user dashboards
- Create/edit/delete blog posts
- Notifications system
- Media/image upload support

---

## ⚙️ Setup Instructions

1. **Clone the repo**
   ```bash
   git clone https://github.com/yajasvikhanna/Blog_website_Django.git
   cd Blog_website_Django
````

2. **Create virtual environment**

   ```bash
   python -m venv venv
   source venv/bin/activate  # or venv\Scripts\activate on Windows
   ```

3. **Install dependencies**

   ```bash
   pip install django
   ```

4. **Run migrations**

   ```bash
   python manage.py migrate
   ```

5. **Create superuser (for admin access)**

   ```bash
   python manage.py createsuperuser
   ```

6. **Start server**

   ```bash
   python manage.py runserver
   ```

Visit: [http://127.0.0.1:8000](http://127.0.0.1:8000)

---

## 📁 Key Folders

* `Blog/`, `dashboard/` – Django apps
* `templates/` – HTML files
* `static/` – CSS/JS assets
* `media/` – Uploaded images

---

## 👤 Author

**Yajasvi Khanna**
[GitHub Profile](https://github.com/yajasvikhanna)

