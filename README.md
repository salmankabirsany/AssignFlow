# AssignFlow

AssignFlow is a full-stack academic assignment and task management platform designed to help students and teachers efficiently manage coursework, deadlines, priorities, and progress tracking.

The project is built using Django REST Framework for the backend and Vue.js with TypeScript for the frontend.

---

# Features

## Authentication & Authorization
- User registration and login
- JWT-based authentication
- Role-based access control (Student & Teacher)

## Assignment Management
- Create assignments
- Update assignments
- Delete assignments
- Track assignment progress
- Mark assignments as completed

## Academic Organization
- Subject/course management
- Assignment categorization
- Priority-based workflow
- Deadline management

## Dashboard & Analytics
- Total assignments overview
- Completed tasks tracking
- Overdue assignment monitoring
- Upcoming deadlines summary

## Search & Filtering
- Filter by subject
- Filter by priority
- Filter by status
- Search assignments by title

---

# Tech Stack

## Backend
- Django
- Django REST Framework
- PostgreSQL
- JWT Authentication

## Frontend
- Vue.js
- TypeScript
- Axios
- Vue Router

## Tools
- Git
- GitHub
- Postman

---

# Project Structure

```bash
AssignFlow/
│
├── backend/
│   ├── apps/
│   ├── config/
│   └── requirements.txt
│
├── frontend/
│   ├── src/
│   ├── components/
│   ├── services/
│   └── pages/
│
├── docs/
└── README.md
```

---

# Goals of the Project

This project was developed to practice and demonstrate:
- REST API development
- Full-stack application architecture
- Database relationship handling
- Authentication systems
- Frontend-backend integration
- Clean code organization
- Real-world problem solving

---

# Planned Features

- Email notifications
- Assignment reminder system
- File upload support
- Team assignment collaboration
- Performance analytics dashboard

---

# Installation

## Backend Setup

```bash
cd backend
pip install -r requirements.txt
python manage.py runserver
```

## Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

---

# API Endpoints (Planned)

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | /api/auth/register | Register user |
| POST | /api/auth/login | Login user |
| GET | /api/assignments | Get assignments |
| POST | /api/assignments | Create assignment |
| PUT | /api/assignments/:id | Update assignment |
| DELETE | /api/assignments/:id | Delete assignment |

---

# Development Status

Currently under active development.

---

# Author

Developed by Salman Kabir Sany
