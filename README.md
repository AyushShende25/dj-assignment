# djChat - A Django-Based Chat Application

djChat is a robust and scalable chat application built using Django. The project is divided into three modules:

- **djChat**: The core project configuration and settings.  
- **chat**: Manages real-time messaging and chat functionality.  
- **users**: Handles user authentication, profiles, and management.

---

## Features

- User authentication and profile management.  
- Real-time chat between users.  
- Modular structure for easy scalability.  
- PostgreSQL integration for reliable data storage.  

---

## Requirements

- Python 3.13.1
- Django 5.x
- PostgreSQL

---

## Local Setup

1. **Clone the repository**
   ```bash
   git clone <https://github.com/AyushShende25/dj-assignment>
   cd djChat
2. **Create and activate virtual env**
   ```bash
   python -m venv venv
   # on windows
   venv\Scripts\activate
   # on mac/linux
   source venv/bin/activate
3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
4. **Configure environment variables**
   Create a `.env` file in the root directory of your project with reference to the example env.


5. **Apply database migrations**
   ```bash
   python manage.py migrate
6. **Create superuser (admin)**
   ```bash
   python manage.py createsuperuser
6. **Run development server**
   ```bash
   python manage.py runserver