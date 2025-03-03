# Project Management Tool

📌 **Overview**  
This is a Project Management Tool built using the **MEAN** (MongoDB, Express.js, Angular, Node.js) stack. It helps teams efficiently manage tasks, track project progress, and collaborate effectively.

---

## 🚀 Features
- **User authentication** (login/logout)
- **Create, edit, and delete projects**
- **Task management** with statuses (To-Do, In Progress, Done)
- **Role-based access control** (Admin, Manager, Developer)
- **Interactive dashboard** for project insights
- **Real-time collaboration** (comments, notifications)

---

## 🛠️ Tech Stack

- **Frontend**: Angular
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JWT (JSON Web Tokens)
- **UI Framework**: Bootstrap / Tailwind CSS (if used)

---

## 🎯 Installation & Setup

### Clone the repository
```bash
git clone https://github.com/your-username/project-management-tool.git
cd project-management-tool
```

### Frontend Setup
1. Navigate to the frontend directory:
   ```bash
   cd frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Run the frontend application:
   ```bash
   ng serve
   ```
   This will run the app in development mode. Open your browser and go to `http://localhost:4200/` to view it.

### Backend Setup
1. Navigate to the backend directory:
   ```bash
   cd backend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the backend server:
   ```bash
   node server.js
   ```
   This will run the backend server on `http://localhost:5000/`.

---

🔗 API Endpoints (Sample)

### User Authentication
- **POST** `/api/auth/signup` → Register a new user  
- **POST** `/api/auth/login` → User login

### Project Management
- **GET** `/api/projects` → Fetch all projects
- **POST** `/api/projects` → Create a new project

Task Management
- **GET** `/api/tasks/:projectId` → Get tasks for a project
- **POST** `/api/tasks` → Create a new task

---
 📌 Future Enhancements
- **Kanban board** for task visualization
- **File uploads** for project documentation
- **Integration with third-party tools** like Slack/Trello
- **AI-based task prioritization**

