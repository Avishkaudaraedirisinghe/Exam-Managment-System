Exam Management System (EMS)
A centralized, web-based platform to streamline examination workflows at university level. EMS automates exam scheduling, grading, result publication, performance tracking and mitigation handling, providing role-based access for students, lecturers and administrators.

🚀 Features
User Roles & Permissions

Students: view/edit profile, see exam schedules & grades
Lecturers: enter/update continuous assessment (CA) & final exam (FE) marks, view enrolled courses, generate reports
Administrators: publish exam schedules, generate reports, publish final results
Exam Scheduling

Publish and display exam dates
Grading & Result Management

Intuitive interface for grade entry and updates
Instant student access to published results
Performance Tracking

Graphical reports of student performance over time
Aggregated views for departmental trends
🛠️ Technology Stack
Tier	Technologies
Frontend	HTML · Tailwind CSS · JavaScript
Backend	Python · Django
Database	MySQL
Tools	Git · VS Code · Figma
📐 Architecture
Three-tier architecture:

Presentation Layer (UI) – Tailwind-styled pages, dynamic behavior via JavaScript
Application Layer (Django) – RESTful views, URL routing, business logic
Data Layer (MySQL) – normalized schema for users, courses, exams, grades, requests
⚙️ Getting Started
Prerequisites
Python 3.10+
MySQL server
Git
Installation
Clone repository
git clone https://github.com/<your-org>/exam-management-system.git
cd exam-management-system
