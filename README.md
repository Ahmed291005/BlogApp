# ✍️ Blog App - Django REST API

![Django](https://img.shields.io/badge/Django-092E20?logo=django\&logoColor=white)
![Django REST](https://img.shields.io/badge/Django%20REST-ff1709?logo=django\&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-07405E?logo=sqlite\&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?logo=redis\&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?logo=celery\&logoColor=white)
![Gunicorn](https://img.shields.io/badge/Gunicorn-499848?logo=gunicorn\&logoColor=white)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

---

A **scalable blogging app** built with **Django + Django REST Framework**.
Handles authentication, blog management, media uploads, and background tasks with **Celery + Redis**.

---

## ✨ Features

✅ **User Authentication** – Secure signup/login with JWT
✅ **Blog Management** – Create, read, update, delete posts
✅ **Rich Text Support** – Integrated with TinyMCE editor
✅ **Image Uploads** – Managed with Pillow & Django Storages
✅ **Background Tasks** – Powered by Celery + Redis
✅ **Testing Suite** – Pytest with coverage & playwright integration

---

## 🚀 Live Demo

> 🌍 Coming soon — Deployment link will be added here.

---

## ⚙️ Tech Stack

* **Backend:** Django 3.1, Django REST Framework, Celery
* **Database:** SQLite (default) → Easily switchable to PostgreSQL
* **Task Queue:** Celery + Redis
* **Storage:** Django Storages (S3, local, etc.)
* **Deployment:** Gunicorn, Docker-ready

---

## 📊 API Highlights

* `POST /api/token/` → Obtain JWT token
* `POST /api/token/refresh/` → Refresh JWT token
* `GET /api/posts/` → Fetch all blog posts
* `POST /api/posts/` → Create new blog post
* `GET /api/posts/<id>/` → Retrieve single blog post
* `PUT /api/posts/<id>/` → Update blog post
* `DELETE /api/posts/<id>/` → Delete blog post

---

## 🛠️ Local Setup

1️⃣ Clone the repo

```bash
git clone https://github.com/Ahmed291005/BlogApp.git
cd BlogApp
```

2️⃣ Create & activate virtual environment

```bash
python -m venv env
.\env\Scripts\activate   # Windows  
source env/bin/activate  # Mac/Linux  
```

3️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

4️⃣ Run migrations

```bash
python manage.py migrate
```

5️⃣ Start dev server

```bash
python manage.py runserver
```

Visit 👉 `http://127.0.0.1:8000/`

---

## 📌 Future Improvements

* 🔹 API rate limiting & throttling
* 🔹 Blog categories & tags
* 🔹 User profiles with avatars
* 🔹 Real-time notifications (WebSockets + Django Channels)
* 🔹 Docker Compose for prod-ready setup

---

## 🔒 Security

* JWT authentication with refresh tokens
* Encrypted passwords via Django’s auth system
* CSRF protection for web sessions
* Secure file storage options (AWS S3, GCS, etc.)

---

## 📝 License

Licensed under the **MIT License**.
See [LICENSE](./LICENSE) for details.

---

## 🤝 Connect with Me

Made with ❤️ by **Muhammad Ahmed**

* 🔗 [LinkedIn](https://www.linkedin.com/in/muhammad-ahmed-5b7850340/)
* 💻 [GitHub](https://github.com/Ahmed291005)

---
