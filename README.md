#  Capstone Management System – CS5213 Group B (Spring 2024)

This repository hosts the design, development, and deployment artifacts of the **Capstone Management System (CMS)**, created by **Group B** for the **CS5213 Software Engineering** course at the University of Oklahoma, Spring 2024.

---

##  Project Overview

The **CMS** is a Django-based web platform designed to support the full lifecycle of capstone projects for students, faculty, and administrators. Features include user authentication, team formation, calendar integration, submissions, communication, grading, and CI/CD automation.

---

##  Documents Included

-  Ticket 7: [Software Design Document (SDD)]  
  Covers system goals, architecture, UI design, milestones, sprint plans, and detailed module-level descriptions.

-  Ticket 8: [Environment Setup Guide]  
  Provides GitHub workflow structure, issue management via milestones, role responsibilities, and collaboration instructions.

---

##  Key Features & Technologies

| Feature                        | Description                                                                 |
|-------------------------------|-----------------------------------------------------------------------------|
|  Django ORM                 | Models for Users, Projects, Teams, Submissions, Grades, etc.               |
|  CI/CD                      | GitHub Actions automate testing, build, and deployment                     |
|  Login with 4x4 Matrix      | Secure login with 2FA-style matrix verification                            |
| Calendar Integration       | Canvas API-based event sync & scheduling                                   |
|  Communication System       | Messaging & forum system via Canvas API                                    |
|  Test Environment           | Automated server provision + CI for deployment                             |
|  Submission & Review       | Document upload, status updates, feedback, and Canvas grade sync           |

---

##  System Architecture

- **Frontend:** HTML, CSS (customized Django templates)
- **Backend:** Django (Python)
- **Database:** PostgreSQL
- **Deployment:** GitHub Actions (CI/CD), cloud-hosted VPS
- **Authentication:** Django with 4x4 matrix verification
- **Canvas Integration:** API for events, communication, and grading

---

##  Milestones (M1–M11)

1. Project Setup (Django)
2. Production Environment Setup (Cloud Hosting)
3. Test Environment with CI/CD
4. ORM Models Definition
5. CI/CD Integration (GitHub Actions)
6. Login + Dashboard
7. Team Formation + Access Control
8. Calendar (Canvas API)
9. Submission Page
10. Communication (Canvas API)
11. Review Page with Grade Integration (Canvas API)

---

##  Agile Development Flow

-  **Sprints:** 5-day Agile cycles with clear planning and review structure
-  **Daily Standups** and Thursday **code freeze**
-  **Friday demos** to validate progress
-  **Gantt Charts** for planning & visual tracking
-  **Role-based execution:** Dev, QA, PM, Code Reviewer, Scrum Master

---

##  Getting Started (Setup)

1. Clone the repo:  
   `git clone https://github.com/ou-cs5213-sp24/capstone-management-system.git`
2. Install Python, create virtualenv  
3. Install requirements: `pip install -r requirements.txt`
4. Apply migrations: `python manage.py migrate`
5. Run server: `python manage.py runserver`

---

##  Contributors (Group B)

- Developers, Scrum Masters, Reviewers, QA – listed in artifacts  
- University of Oklahoma, Spring 2024



