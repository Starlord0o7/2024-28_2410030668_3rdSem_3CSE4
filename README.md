[README.md](https://github.com/user-attachments/files/32065803/README.md)
# 2024-28_2410030668_3rdSem_3CSE4# Full-Stack Development Internship — TaskFlow

**Internship Report Repository | B.Tech CSE | Batch 2024–2028**

---

## 👤 Student Details

| Field | Details |
|---|---|
| **Name** | Akshat Maurya |
| **Roll Number** | 2410030668 |
| **Batch** | 2024–2028 |
| **Section** | 3CSE4 |
| **Semester** | 3rd Semester |
| **Program** | B.Tech, Computer Science & Engineering |
| **University** | School of Computer Science and Engineering, IILM University, Greater Noida, U.P. |

---

## 📌 About This Repository

This repository contains my **Full-Stack Development Internship** submission, completed as part of the requirement for the degree of B.Tech in Computer Science and Engineering. It includes the internship report, completion certificate, and the presentation documenting the project undertaken during the internship.

As the practical project for the internship, I designed and built **TaskFlow** — a full-stack task and project management web application — covering the complete development stack from UI to database.

---

## 🎓 Internship Details

| Field | Details |
|---|---|
| **Domain** | Full-Stack Development |
| **Internship Period** | 02-08-2026 to 30-08-2026 |
| **Conducted By** | UniConverge Technologies & upSkillCampus |
| **In Collaboration With** | All India Council for Technical Education (AICTE), The IoT Academy |
| **Certificate ID** | USC704188TIA |

---

## 🚀 Project: TaskFlow — Full-Stack Task & Project Management Web App

TaskFlow allows users to create, view, update and delete tasks, assign priorities and status values, and track progress through a dashboard. It follows a three-layer architecture — a React presentation layer, an Express/Node.js application layer, and a MongoDB data layer — keeping responsibilities cleanly separated.

### Core Modules
- Dashboard with task statistics
- Task CRUD (Create, Read, Update, Delete)
- Task status workflow: `Todo → In Progress → Done`
- Priority levels: `Low`, `Medium`, `High`
- REST API layer
- Persistent database storage

### 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Frontend | HTML5, CSS3, JavaScript, React.js |
| Backend | Node.js, Express.js |
| Database | MongoDB, Mongoose |
| Tools | Git, GitHub, VS Code, Postman |

### 🔗 Major API Endpoints

| Method | Endpoint | Purpose |
|---|---|---|
| GET | `/api/tasks` | Fetch all tasks |
| POST | `/api/tasks` | Create a task |
| PUT | `/api/tasks/:id` | Update a task |
| DELETE | `/api/tasks/:id` | Delete a task |
| GET | `/api/health` | Check server status |

### 🏗️ System Architecture

```
┌───────────────────────────┐
│      React Frontend       │
│ Dashboard • Task Forms    │
│ Filters • Task List       │
└─────────────┬─────────────┘
              │ HTTP / JSON
              ▼
┌───────────────────────────┐
│  Node.js + Express API    │
│ Routes • Validation       │
│ Business Logic • Errors   │
└─────────────┬─────────────┘
              │ Mongoose
              ▼
┌───────────────────────────┐
│         MongoDB           │
│     Tasks Collection      │
└───────────────────────────┘
```

---

## 📂 Repository Structure

```
2024-28_2410030668_3rdSem_3CSE4/
│
├── Report/            # Internship Report (PDF)
├── Certificate/        # Internship Completion Certificate (PDF)
├── Presentation/       # Internship Presentation
└── README.md           # Repository overview (this file)
```

---

## 📖 Report Highlights

- **Problem Statement:** Centralizing scattered task information into a single, reliable, database-backed interface.
- **Methodology:** Incremental development across requirement analysis, UI design, backend development, database integration, frontend integration, and testing/debugging phases.
- **Key Outcomes:** Practical experience building REST APIs, connecting a React frontend to a Node/Express backend, and performing CRUD operations against MongoDB with validation and error handling.
- **Future Enhancements:** JWT-based authentication, real-time updates via WebSockets, due dates/reminders, and CI/CD-based cloud deployment.

---

##  Acknowledgement

I would like to thank **UniConverge Technologies** and **upSkillCampus**, in association with **AICTE** and **The IoT Academy**, for the internship opportunity, and the **School of Computer Science and Engineering, IILM University, Greater Noida**, for the academic framework that supported this internship.

---

## 📬 Contact

**Akshat Maurya**
B.Tech CSE, Batch 2024–2028
IILM University, Greater Noida
