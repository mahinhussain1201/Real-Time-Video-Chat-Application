# Django Chat Application 🚀

Welcome to our real-time chat application! This project demonstrates a modern approach to building real-time communication systems using Django.

## 🌟 Features

- **Real-time Video Calling**: Instant Video Calling
- **User Authentication**: Secure lobby name
- **Chat Rooms**: Create and join multiple chat rooms
- **Responsive Design**: Works seamlessly on desktop and mobile

## 🛠️ Tech Stack

- **Backend**: Django 
- **Frontend**: HTML5, CSS3, JavaScript
- **Database**: SQLite (default) / PostgreSQL
- **UI Framework**: Bootstrap 5

## 📋 Prerequisites

- Python 3.8+
- Git
- pip (Python package manager)
- Virtual environment

## 🚀 Quick Start

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/chat-app.git
   cd chat-app
   ```

2. **Set Up Virtual Environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Environment Setup**
   Create `.env` file in root directory:
   ```env
   DEBUG=True
   SECRET_KEY=your-secret-key
   ALLOWED_HOSTS=localhost,127.0.0.1
   ```

5. **Database Setup**
   ```bash
   python manage.py migrate
   ```

6. **Create Admin User**
   ```bash
   python manage.py createsuperuser
   ```

7. **Run Development Server**
   ```bash
   python manage.py runserver
   ```

Visit `http://localhost:8000` to see the application in action!

## 💻 Development

### Project Structure
```
mychat/
├── base/               # Main application directory
├── static/            # Static files (CSS, JS, Images)
├── templates/         # HTML templates
├── manage.py          # Django management script
├── requirements.txt   # Project dependencies
└── README.md         # This file
```

### Running Tests
```bash
python manage.py runserver
```

## 🔧 Configuration

### Environment Variables
- `DEBUG`: Set to False in production
- `SECRET_KEY`: Django secret key
- `ALLOWED_HOSTS`: Comma-separated list of allowed hosts

### Database Configuration
Default SQLite configuration:
```python
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.sqlite3',
        'NAME': BASE_DIR / 'db.sqlite3',
    }
}
```
---
Made with ❤️ by Mahin