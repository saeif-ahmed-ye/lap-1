# Lab 1: Project Plan & Environment Setup
**Project Title:** 小组分工看板系统 (Dynamic Team Task Board System)  
**Developer:** Saeif Ahmed  
**Course:** Software Engineering Laboratory  

---

## 1. Project Overview & Objectives
The **小组分工看板系统 (Dynamic Team Task Board System)** is a web-based collaboration application designed to dynamically handle task allocation, team project milestones, and group responsibilities. Unlike rigid, hardcoded tools, this system allows users to configure custom project titles, team types, and member rosters dynamically upon initialization.

### Core Objectives:
* **Dynamic Initialization:** Allow users to define project metadata (title, category/type, and member list) on startup.
* **Kanban Task Board:** Provide a centralized visual board tracking tasks across stages (To-Do, In Progress, Completed).
* **Data Persistence:** Use an embedded SQLite database to securely store board configurations, members, and task assignments.

---

## 2. Tech Stack & Environment Architecture
* **Backend Framework:** Python Flask (v3.1.3)
* **Database:** SQLite (Embedded relational database)
* **Frontend:** HTML5, CSS3, JavaScript (Responsive Kanban layout)
* **Version Control:** Git & GitHub (`https://github.com/saeif-ahmed-ye/lap-1.git`)
* **Environment Isolation:** Python Virtual Environment (`venv` via MSYS2 UCRT64)

---

## 3. System Architecture & Modules
1. **Setup & Configuration Module:** Dynamic form for inputting team name, project type, and member roster.
2. **Task Management Module:** CRUD operations (Create, Read, Update, Delete) for tasks mapped to specific members and statuses.
3. **Database Layer:** Relational tables connecting workspaces, members, and tasks.
4. **Web UI Interface:** Responsive, card-based dashboard for interactive task tracking.

---

## 4. Development Roadmap (Lab Milestones)
* **Lab 1:** Requirements Analysis, System Planning, and Environment Initialization.
* **Lab 2:** Database Schema Design & Dynamic Setup Backend Routes.
* **Lab 3:** Frontend UI Integration & Kanban Board Dashboard Layout.
* **Lab 4:** Full CRUD Functionality & Interactive State Management.
* **Lab 5:** Testing, Bug Fixing, and Final GitHub Deployment.