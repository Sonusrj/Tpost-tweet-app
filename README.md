# 🐦 Tpost - Twitter-like Web App

**Tpost** is a Django-based web application where users can log in, register, and post text or images. It's similar to Twitter, allowing users to interact with content in a secure and user-friendly environment.

## 🚀 Features

- 🔐 **User Authentication**: Users must sign up or log in to create, edit, or delete posts.
- 📝 **Post Functionality**: Users can post text and images, edit, and delete their own posts. Non-logged-in users can view but not interact.
- 🔒 **Security**: The app utilizes Django's CSRF protection and ORM to ensure a secure environment.
- 💻 **Responsive Design**: Built with HTML, CSS, and Bootstrap for a seamless experience across devices.

---

## ⚙️ Installation and Setup

1. Clone the repository:
    ```bash
    git clone https://github.com/Sonusrj/Tpost-tweet-app.git
    ```

2. Create and activate a virtual environment:
    ```bash
    python -m venv env
    
   # On Windows:
    
    .\env\Scripts\activate
    
   # On Mac/Linux:
   
    source env/bin/activate
    ```
   
2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Navigate to the project folder:
    ```bash
    cd ProjectHQ
    ```

4. Run the development server:
    ```bash
    python manage.py runserver
    ```

5. Access the app at `http://127.0.0.1:8000/`.

---

## 🛠️ Usage

- 🔑 **Login/Register**: Users must create an account or log in to post, edit, or delete.
- 👀 **View Posts**: All users can view existing posts.
- 🛠️ **Admin Panel**: Manage users and posts via Django’s admin panel.

## 🌐 Technologies Used

- 🐍 **Django** (Backend)
- 🌐 **HTML, CSS, Bootstrap** (Frontend)

