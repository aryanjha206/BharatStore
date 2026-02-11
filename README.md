# BharatStore 🇮🇳

BharatStore is a localized, full-stack app marketplace for India, built with Flask and MongoDB. It allows developers to publish apps and users to discover them, featuring an admin moderation workflow.

## Features
- **User & Developer Accounts**: Role-based access (User, Developer, Admin).
- **App Management**: Developers can submit apps with metadata, icons, and screenshots.
- **Moderation System**: Admins approve or reject app submissions.
- **Search & Filter**: Browse apps by category or search by name.
- **Indian Aesthetics**: UI designed with Saffron, White, and Green accents using Glassmorphism.
- **Security**: Password hashing with Bcrypt and secure session management.

## Setup Instructions

1. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

2. **Run the Application**:
   ```bash
   python app.py
   ```

3. **Access the App**:
   Open your browser and go to `http://127.0.0.1:5000`.

## Default Admin Account
An admin account is automatically created on the first run if it doesn't exist:
- **Email**: admin@bharatstore.in
- **Password**: admin123

## Technology Stack
- **Backend**: Python (Flask)
- **Database**: MongoDB Atlas
- **Frontend**: HTML5, CSS3 (Custom Glassmorphism), Vanilla JS
- **Auth**: Flask-Login, Flask-Bcrypt

## Project Structure
- `app.py`: Main application logic.
- `templates/`: HTML templates.
- `static/`: CSS and assets.
- `requirements.txt`: Python dependencies.
