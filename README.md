# 📑 Bookmark Manager

A modern full-stack Bookmark Manager that allows users to securely save, organize, search, and manage their favorite links. The application uses Supabase Authentication for secure email-based login and Supabase Database for storing bookmark data.

## 🚀 Features

* 🔐 Email Authentication with Supabase
* 👤 User Registration & Login
* ✉️ Email Verification
* ➕ Create Bookmarks
* 📖 View Saved Bookmarks
* ✏️ Edit Bookmarks
* 🗑️ Delete Bookmarks
* 🔍 Search Bookmarks
* 🔒 Protected User Data
* 📱 Responsive Design

## 🛠️ Tech Stack

### Frontend

* HTML
* CSS
* JavaScript

### Backend

* Node.js
* Express.js

### Database & Authentication

* Supabase
* Supabase Auth
* PostgreSQL

## 📂 Project Structure

```bash
Bookmark/
│
├── .env
├── package.json
├── package-lock.json
├── vercel.json
│
├── public/
│   ├── css/
│   │   └── style.css
│   │
│   └── pages/
│       ├── dashboard.html
│       ├── login.html
│       ├── register.html
│       └── profile.html
│
└── src/
    │
    ├── index.js
    │
    ├── controller/
    │   ├── auth.controller.js
    │   ├── bookmarkcontroller.js
    │   └── profilecontroller.js
    │
    ├── routes/
    │   ├── auth.routes.js
    │   ├── bookmark.routes.js
    │   └── profile.routes.js
    │
    ├── middleware/
    │   └── auth.middleware.js
    │
    └── lib/
        ├── db.js
        └── email.js


## 📌 Core Functionality

### Authentication

* Sign Up with Email
* Login with Email
* Email Verification
* Session Management
* Protected Routes

### Bookmark Management

* Add Bookmark
* Update Bookmark
* Delete Bookmark
* Search Bookmark
* User-specific Bookmark Storage

## 🎯 Future Enhancements

* Bookmark Categories
* Tags
* Favorites
* Import/Export Bookmarks
* Share Bookmarks
* Pagination

## 👨‍💻 Author

Parishkrat Mishra

GitHub: https://github.com/Parishkrat

## ⭐ Support

If you found this project useful, please consider giving it a star.
