# Notes App - Vanilla JavaScript

⚠️ **WARNING**: This application contains intentional security vulnerabilities for educational purposes!

## 🚀 Setup

### Backend
```bash
cd backend
npm install
npm start
```

Backend runs on http://localhost:5000

### Frontend
Simply open `frontend/index.html` in your browser.

Or use Live Server in VS Code.

## 🎯 Features

### User Mode
- Create notes
- Edit notes
- Delete notes
- Search notes

### Guest Mode
- View notes only (read-only)
- Search notes

## 🔐 Vulnerabilities Included

1. SQL Injection
2. XSS (Cross-Site Scripting)
3. No input validation
4. IDOR
5. No authorization checks
6. No CSRF protection

## 🧪 Test Vulnerabilities

Try these in search: `' OR 1=1 --`

Try this in note title: `<script>alert('XSS')</script>`

## 📚 Your Task

Fix all security vulnerabilities!