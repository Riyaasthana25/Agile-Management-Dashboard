# Agile-Management-Dashboard

## Project Overview
The Agile Management Dashboard is a web-based tool designed to streamline the management and tracking of agile development projects. This dashboard helps project managers, team leads, and developers to easily monitor project progress, manage tasks, and stay aligned with agile methodologies such as Scrum.
The dashboard provides insights into the project’s velocity, sprint progress, task status, and team performance in a visually intuitive manner.

## Tech Stack

- **Frontend**: HTML, CSS, JavaScript
- **Framework**: Flask 
- **Backend**: Python
- **Database**: sqlalchemy
- **Visualization**: Matplotlib/Seaborn/Plotly 
- **Authentication**:Two-Factor Authentication(2FA), Multi-Factor Authentication (MFA)
- **Testing**: Unit-test, Py-test
- **Automation**: Scheduler


## Implemented Features

### 🔐 Login and Role Management System
- Home page for navigation and platform exploration
- Secure sign-up with admin review and approval flow
- Admin dashboard to manage user requests
- Real-time monitoring with account approval notifications
- Login with Two-Factor Authentication
- Forgot Password with Multi-Factor Authentication

### 🆕 New Project Creation & Intimation
- Pop-up form to create projects with fields like Project ID, Name, Description, Product Owner, Start/End Date, and Status
- Sprint and User Story setup with story points
- Email notifications sent to team members post-creation of Project

### 📋 Project Overview Section
- Displays all project details with status
- ‘View Details’ for project insights
- ‘Edit’ access limited to Product Owners/Scrum Masters

### ✏️ Product Owner / Scrum Master Edit Suite
- Authorized users can update project info via the ‘Edit’ button

### 🔍 Detailed Project Insights
- Sprint Calendar and User Story Overview
- Metrics like total stories, completed stories, and story points
- Sprint schedule including velocity and completion percentage

### 📈 Performance Analytics
- **Donut Chart** – Status distribution (Not Started, Ongoing, Pending, Completed)
- **Burnup Chart** – Total effort vs. completed effort over sprints
- **Burndown Chart** – Remaining work tracked across sprints
- **Velocity Chart** – Team capacity visualized via story points
- **Team Leaderboard** – Highlights team rankings based on completed story points

### 📬 Automated Periodic Reporting
- Weekly/monthly summary emails
- Deadline reminder emails
- Downloadable PDF for project summaries

---

## Agile Process Alignment

Our dashboard supports and enhances key Agile practices:

### 📆 Scrum Events
- **Sprint Launch**: Sprint planning and task allocation  
- **Daily Stand-ups**: Track progress, identify blockers  
- **Sprint Review**: Present and evaluate completed work  
- **Sprint Retrospective**: Reflect and improve for the next sprint  
- **Milestones**: Track important checkpoints in the project

### 🧾 Scrum Artifacts
- **Product Backlog**: Centralized feature/task list  
- **Sprint Backlog**: Tasks committed for the sprint  
- **Stand-up Meeting Insights**  
- **Sprint Review / Retrospective Documentation**

---

## Benefits

- Encourages real-time collaboration and visibility  
- Automates status updates and reporting  
- Helps teams stay on schedule with proactive planning  
- Boosts efficiency and motivation with clear performance analytics  
- Supports continuous improvement via feedback-driven sprints  

---

## License
This project is licensed under the MIT License - see the LICENSE file for details.


---