Full Stack Project – React (Vite) + Django REST
Overview

This project is a full-stack web application with:

Frontend: React (built using Vite)
Backend: Django + Django REST Framework (DRF)
Authentication: JWT (using SimpleJWT)
Database: PostgreSQL (via psycopg2)


Tech Stack

*)Frontend

React
Vite
ESLint
React Compiler (enabled)


*)Backend

Django
Django REST Framework
SimpleJWT (JWT Authentication)
PostgreSQL
django-cors-headers
python-dotenv




📂 Project Structure
project-root/
│
├── frontend/          # React + Vite app
│   ├── src/
│   ├── public/
│   └── package.json
│
├── backend/           # Django project
│   ├── app/
│   ├── project/
│   ├── manage.py
│   └── requirements.txt
│
└── README.md



⚙️ Setup Instructions

1) Clone the Repository
git clone <your-repo-url>
cd project-root

3) Frontend Setup (React + Vite)
cd frontend
npm install
npm run dev
App runs on: http://localhost:5173
Build for Production
npm run build

3) Backend Setup (Django)
Create Virtual Environment
cd backend
python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows

4) Install Dependencies
pip install -r requirements.txt
Environment Variables

📦 Backend Dependencies
asgiref
Django
django-cors-headers
djangorestframework
djangorestframework-simplejwt
PyJWT
pytz
sqlparse
psycopg2-binary
python-dotenv
