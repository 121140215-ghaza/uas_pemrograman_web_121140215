# Struktur Direktori Awal Project RUNLOG

# root-project/
├── backend/                   # folder backend dengan Pyramid
│   ├── runlog/                # main package Pyramid
│   │   ├── __init__.py
│   │   ├── models.py          # definisi schema SQLAlchemy
│   │   ├── views/             # folder views (endpoint CRUD)
│   │   │   ├── users.py
│   │   │   ├── runlog.py
│   │   │   └── goal.py
│   │   └── auth.py            # file login/register
│   ├── development.ini
│   └── setup.py
│
├── frontend/                  # folder frontend React
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   │   ├── RunLogList.jsx
│   │   │   ├── RunLogForm.jsx
│   │   │   └── GoalForm.jsx
│   │   ├── pages/
│   │   │   ├── Dashboard.jsx
│   │   │   └── Login.jsx
│   │   ├── App.jsx
│   │   ├── index.js
│   │   └── services/          # Axios API helper
│   │       └── api.js
│   └── package.json
│
├── README.md
└── .gitignore

# README.md awal

# RUNLOG – Personal Running Tracker

## Deskripsi
RUNLOG adalah aplikasi web yang membantu pelari mencatat dan memantau progres latihan lari harian mereka dengan simpel dan efisien. Website ini memiliki fitur CRUD pada log latihan lari dan target bulanan pengguna.

## Tech Stack

### Backend
- Python Pyramid (RESTful API)
- PostgreSQL

### Frontend
- React JS (UI)
- React Router DOM (Routing)
- Redux Toolkit / Context API (State Management)
- Tailwind CSS / Bootstrap / MUI (UI Framework)
- Axios / Fetch API (API Integration)

## Fitur Aplikasi
- Autentikasi Pengguna (Login/Register)
- CRUD Log Lari
- CRUD Target Bulanan
- Statistik Lari Sederhana
- Filter & Search Log

## Dependensi Paket
### Backend
- pyramid
- sqlalchemy
- psycopg2
- pyramid_jwt / pyramid_basicauth (auth)
- pytest (unit test)

### Frontend
- react
- react-router-dom
- redux-toolkit / react-context
- axios
- tailwindcss / bootstrap / mui

## Referensi
- https://trypyramid.com
- https://reactjs.org
- https://tailwindcss.com
- https://redux-toolkit.js.org
