# Flask Blog Project

A fully functional blog platform built with Python and Flask. This project features user authentication, a commenting system, and an administrative interface for managing blog content.

## 🚀 Features

* **User Authentication**: Secure registration and login system using `Flask-Login` and password hashing with `Werkzeug`.
* **Administrative Controls**: An `admin_only` decorator ensures that only the authorized administrator (User ID: 1) can create, edit, or delete blog posts.
* **Interactive Commenting**: Registered users can comment on blog posts. A custom `only_commenter` decorator allows users to manage and delete their own comments.
* **Dynamic UI**: Integrated with `Flask-Bootstrap` for responsive design and `CKEditor` for a rich-text editing experience when creating posts.
* **Profile Avatars**: Uses `Flask-Gravatar` to automatically generate profile images for users based on their email addresses.
* **Database Management**: Utilizes `Flask-SQLAlchemy` with a SQLite database to store users, blog posts, and comments with relational mapping.

## 🛠️ Technologies Used

* **Backend**: Python, Flask
* **Database**: SQLAlchemy (SQLite)
* **Frontend**: HTML5, CSS3, JavaScript, Bootstrap 5
* **Forms**: Flask-WTF
* **Security**: Werkzeug (Password Hashing)

## 📁 Project Structure

* `main.py`: The core Flask application containing routes, models, and logic.
* `forms.py`: Defines the WTForms for registration, login, and posting.
* `templates/`: HTML templates for the blog's frontend.
* `static/`: Contains CSS, JavaScript, and image assets.
* `requirements.txt`: List of all Python packages required to run the project.

## 🙏 Acknowledgments

This project was developed as part of a side learning initiative. While I handled the backend logic and database architecture, I received external assistance in crafting the CSS, JavaScript, and certain HTML components to ensure a polished user interface.
