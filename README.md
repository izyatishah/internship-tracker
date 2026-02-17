# Internship Tracker - Full Stack

A premium internship tracking application built with React, Express, and MySQL.

## Features
- **Intern View**: Log tasks, reflections, and upload attachments.
- **Supervisor View**: Review tasks and add guidance/feedback.
- **Dashboard**: Visual statistics and progress tracking.
- **Full Stack**: Real-time data persistence with MySQL.

## Local Setup

### 1. Database
- Create a database named `internship_tracker` in phpMyAdmin.
- Import `database/schema.sql`.

### 2. Environment Variables
- Create a `.env` file in the root:
```env
DB_HOST=localhost
DB_USER=root
DB_PASSWORD=your_password
DB_NAME=internship_tracker
PORT=5000
```

### 3. Installation & Run
```bash
# Install dependencies
npm install

# Start Backend Server
npm run server

# Start Frontend (in another terminal)
npm run dev
```

## Deployment (Pilihan A)
Follow the [Deployment Guide](brain/d289677b-bcc4-413c-95d4-71a0a44bcb99/deployment_guide.md) for instructions on pushing to GitHub and hosting on platforms like Railway, Render, and Vercel.
