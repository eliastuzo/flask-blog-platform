# Flask Blog Site

This Python project was developed as part of the final stages of my Python bootcamp. It showcases an end-to-end blog application built with Flask and several core libraries:

- **Flask** for routing and web handling
- **SQLAlchemy** for ORM and database management
- **WTForms** for secure and validated form handling
- **werkzeug.security** for password hashing
- **os** for environment and path handling

## Overview

The application is a fully functional blog site with user registration, authentication, and CRUD operations on posts.

- The **home page** displays all saved articles in a clean, styled layout using HTML and CSS.
- Visitors can browse posts in **read-only mode** without logging in.
- To create or modify posts, users must **register and log in**.
- User authentication is securely managed, and routes requiring authorization (like creating or editing posts) are protected and cannot be accessed by simply typing the URL.

## Key Features

- **Registration & Login:** Users can create accounts and securely log in.
- **Role-Based Access:** Only authenticated users can create or modify their own posts.
- **Secure Forms:** All data entry is handled via WTForms with validation.
- **Stylized Frontend:** The site renders HTML and CSS templates effectively.
- **Database Management:** All content is stored using SQLAlchemy ORM.

## How It Works

1. Users land on the home page and can view all articles in read-only mode.
2. Registration is required to unlock posting capabilities.
3. After logging in, users can create new entries and edit their own posts.
4. Protected routes (like `/make-post`) require authentication and cannot be accessed directly.

## Installation

Clone the repository and install dependencies:
```bash
pip install -r requirements.txt
```
Run the application:
```bash
python app.py
```

---

Feel free to adapt this to include project screenshots, deployment instructions, or additional credits.
