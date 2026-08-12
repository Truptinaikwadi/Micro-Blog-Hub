# 📝 MicroBlogHub

A **Weibo-inspired microblogging web application** built using **Django and MySQL**. MicroBlogHub allows users to create accounts, share short posts, view posts from other users, and manage their profiles.

## 📌 Project Overview

**MicroBlogHub** is a collaborative web application developed using Django. It provides a simple social-media-style platform where users can:

* 👤 Register and log in
* 📝 Create and publish short posts
* 👀 View posts shared by other users
* 👤 Manage their profiles
* 🗄️ Store application data using MySQL

The project uses a **shared MySQL database** for collaborative development among team members.

## 🛠️ Tech Stack

| Technology                     | Purpose               |
| ------------------------------ | --------------------- |
| 🐍 Python                      | Backend programming   |
| 🌐 Django                      | Web framework         |
| 🗄️ MySQL                      | Database              |
| 🎨 HTML & CSS                  | Frontend              |
| 📄 Django Templates            | Dynamic web pages     |
| 🔧 Git & GitHub                | Version control       |
| 🛡️ Virtual Environment (venv) | Dependency management |

## ✨ Features

### 🔐 User Authentication

* User registration
* Login and logout functionality
* Secure authentication using Django's built-in authentication system

### 📝 Microblogging

* Create short text posts
* View posts from other users
* Display posts dynamically

### 👤 User Profiles

* Manage user profile information
* View user-related content

### 🗄️ Database

* MySQL database integration
* Centralized database for storing users and posts

## 📂 Project Structure

```text
MicroBlogHub/
│
├── microblog_project/
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
│
├── app/
│   ├── models.py
│   ├── views.py
│   └── urls.py
│
├── templates/
│
├── static/
│
├── manage.py
├── requirements.txt
└── README.md
```

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone <repository-url>
cd MicroBlogHub
```

### 2. Create a Virtual Environment

```bash
python -m venv venv
```

Activate the virtual environment:

**Windows:**

```bash
venv\Scripts\activate
```

**macOS/Linux:**

```bash
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure MySQL

Create a MySQL database and update the database configuration in:

```text
microblog_project/settings.py
```

Example:

```python
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.mysql',
        'NAME': 'your_database_name',
        'USER': 'your_username',
        'PASSWORD': 'your_password',
        'HOST': 'localhost',
        'PORT': '3306',
    }
}
```

### 5. Run Migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

### 6. Start the Development Server

```bash
python manage.py runserver
```

Open the application in your browser at:

```text
http://127.0.0.1:8000/
```

## 👥 Team Members

* **Hitanshi Mopari**
* **Ritika Mohite**
* **Trupti Naikwadi**

## 🎯 Learning Outcomes

Through this project, we gained practical experience in:

* Django web application development
* Python backend development
* MySQL database integration
* Django Models, Views, and Templates
* User authentication
* Git and GitHub collaboration
* Virtual environment management
* Basic frontend development using HTML and CSS

## 🚀 Future Enhancements

Possible improvements include:

* ❤️ Like and unlike posts
* 💬 Comment functionality
* 👥 Follow/unfollow users
* 🔍 Search users and posts
* 📷 Image uploads
* 🔔 Notifications
* 📱 Responsive UI
* 🌐 REST API integration

## 📄 License

This project is developed for **educational purposes only**.
