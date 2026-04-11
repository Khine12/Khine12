# 👋 Hi, I'm Khine Zar Hein
🎓 Computer Science Student @ Cal Poly Pomona (Class of 2027)

💻 Full-Stack Developer | Open Source Contributor | SWE Internship Candidate

📍 West Covina, CA

---

## 🚀 About Me

I enjoy building software that solves real problems with clean architecture and reliable functionality. My recent work spans production-grade backend systems, collaborative full-stack applications, and open source contributions to platforms used by thousands of users.

I built a **Flask REST API** during the MLH Production Engineering Hackathon that sustained 500 concurrent users at 76 RPS with zero failures using Redis caching, Nginx load balancing, and Docker. 

I'm also contributing to **Submitty**, an open-source university grading platform, with 5 pull requests covering Cypress E2E testing, PHP bug fixes, and access control improvements. 

As a collaborative project, I'm building **ShiftSync** — a shift scheduling platform using Next.js, Express.js, and PostgreSQL.

Currently completing **CodePath's Advanced Technical Interview Prep** while actively pursuing Software Engineering internships.

---

## 💻 Technical Skills

**Languages**   
Java • Python • JavaScript • TypeScript • PHP • SQL • HTML • CSS  

**Backend & Infrastructure**    
FastAPI • Flask • Express.js • PostgreSQL • Redis • Nginx • Docker • Gunicorn • SQLAlchemy • APScheduler • Resend API • GitHub Actions    

**Frontend & Tools**    
React • Next.js • TypeScript • Vite • Recharts • Firebase (Auth/Firestore) • Git • Cypress • Vagrant • Linux/Unix • VS Code    

**Core Skills**     
Full-Stack Development • REST APIs • Automated Testing • CI/CD • JWT Authentication • OOP • Data Structures & Algorithms • Debugging • Responsive UI Development     

---

## 🌍 Open Source Contributions

### Submitty
Open source course management and grading platform used by universities worldwide.

**Contributions:**
- Contributed 5 pull requests (1 merged, 4 in review) improving testing infrastructure, grading workflows, and access control in a production platform serving thousands of students and instructors
- Fixed a PHP bug in SubmissionController.php where bulk upload file conflict detection assumed filenames always contain a dot, causing silent merge failures
- Developed Cypress E2E tests validating privacy protections and grading workflows across student, TA, and instructor roles
- Fixed forum access control incorrectly excluding limited-access graders from staff functionality
- Expanded bulk upload sample datasets to improve automated grading test coverage
- Filed bug reports identifying CI pipeline failures on main, leading to maintainer fixes
- Reviewed pull requests by other contributors, identifying linting errors, accessibility issues, and root causes
- Debugged CI failures and resolved flaky Cypress tests across multiple modules
- Addressed reviewer feedback across 3+ review cycles with maintainers

**Pull Requests:**

| PR | Description | Status |
|----|-------------|--------|
| [#12535](https://github.com/Submitty/Submitty/pull/12535) | Cypress E2E tests for overridden grade banner | ✅ Merged |
| [#12562](https://github.com/Submitty/Submitty/pull/12562) | Legal name privacy tests across roles | 🔄 In Review |
| [#12571](https://github.com/Submitty/Submitty/pull/12571) | Bulk upload sample dataset expansion | 🔄 In Review |
| [#12607](https://github.com/Submitty/Submitty/pull/12607) | PHP bug fix for file conflict detection | 🔄 In Review |
| [#12715](https://github.com/Submitty/Submitty/pull/12715) | Forum access control audit | 🔄 In Review |

---

## 🌟 Featured Projects

### 📦 Inventra — Inventory & Sales Management Platform
Full-stack inventory management platform for small businesses with automated stock tracking, email receipts, and scheduled daily alerts.

**Stack:** Python • FastAPI • PostgreSQL • React • TypeScript • JWT • Resend • APScheduler • pytest • GitHub Actions

- Built production REST API with automatic stock deduction after each sale and server-side negative stock guard
- Integrated Resend API to fire email receipts automatically after every transaction via custom domain `noreply@khinezarhein.com`
- Added APScheduler to email sellers daily about low-stock and expiring items — no manual trigger required
- Deployed across 4 cloud services: Render (API) + Neon (PostgreSQL) + Vercel (Frontend) + Resend (Email)
- 9 pytest tests passing with GitHub Actions CI/CD running on every push to main

📂 [Backend](https://github.com/Khine12/inventra) | 
📂 [Frontend](https://github.com/Khine12/inventra-frontend) | 
🌐 [Live Demo](https://inventra-frontend-alpha.vercel.app) | 
📖 [API Docs](https://inventra-api-ernr.onrender.com/docs)

### ⚙️ MLH Production Engineering Hackathon — Flask REST API
Built a production-grade REST API completing the Reliability, Scalability, and Incident Response quest tracks.

**Stack:** Python • Flask • PostgreSQL • Redis • Nginx • Docker • Locust • pytest • GitHub Actions

- Implemented Redis caching and Nginx load balancing across 2 Gunicorn containers — sustained **500 concurrent users at 76 RPS with 0 failures** under Locust load testing
- Added structured JSON logging, live metrics endpoint, Discord alerting with auto-recovery detection, and 83% pytest coverage across 19 tests
- Set up GitHub Actions CI/CD pipeline with Docker Compose orchestration and auto-restart policy

📂 [GitHub](https://github.com/Khine12/PE-Hackathon-Template-2026)

---

### 📅 ShiftSync — Full-Stack Shift Scheduling Platform *(collaborative team project)*
Web-based scheduling application for small and medium-sized businesses, built as a 3-person team project.

**Stack:** Next.js (TypeScript) • Express.js (TypeScript) • PostgreSQL • JWT Authentication

**My Contributions:**
- Designed and implemented a Messenger-style in-app messaging system with persistent PostgreSQL storage
- Fixed a bug where managers weren't automatically added to team membership on team creation
- Fixed authentication state management across the frontend navbar

**Key Features:**
- Manager shift assignment and schedule management
- Employee shift swap requests and availability tracking
- Real-time in-app messaging between team members
- Role-based access control for managers and employees
- Deployed on Vercel and Render

📂 [GitHub](https://github.com/TAndronaco/CS4800-Worker-Schedule-Project)

---

### 🧹 CozyChores — Full-Stack Group Chore Manager
Full-stack web app designed to help roommates organize shared responsibilities.

**Stack:** JavaScript • HTML • CSS • Firebase Auth • Cloud Firestore

- Built secure authentication, real-time Firestore sync, group chat, and task tracking
- Implemented CRUD operations, task filtering, and mobile-first responsive UI

📂 [GitHub](https://github.com/Khine12/CozyChores) | 🌐 [Live Demo](https://khine12.github.io/CozyChores/)

---

### 🗓️ RhythmTasks — Full-Stack Weekly Planner
Weekly task planner designed to improve productivity and organization.

**Stack:** JavaScript • HTML • CSS • Firebase Auth • Cloud Firestore

- Built full-stack planner with secure login, password reset, and real-time cloud sync
- Created interactive UI with collapsible day views, real-time clock, and weekly summary dashboard

📂 [GitHub](https://github.com/Khine12/RhythmTasks) | 🌐 [Live Demo](https://khine12.github.io/RhythmTasks/)

---

### 🌐 Portfolio Website
Personal site showcasing projects and technical progress.

📂 [GitHub](https://github.com/Khine12/Khine12.github.io) | 🌐 [Live](https://khine12.github.io)

---

## 📚 Technical Training

**CodePath — Advanced Technical Interview Prep** *Feb 2026 - May 2026*

Selected for a competitive program focused on data structures, algorithms, and Python-based problem solving under time constraints.

---

## 🎓 Education

**California State Polytechnic University, Pomona**

B.S. in Computer Science — Expected Dec 2027 | GPA: 3.7

**Los Angeles City College**

Associate Degree, 2025 | GPA: 3.7 | Transferred with Honors

---

## 📫 Connect With Me

- 🌐 Portfolio: [khine12.github.io](https://khine12.github.io)
- 💼 LinkedIn: [linkedin.com/in/khine-zar-hein](https://linkedin.com/in/khine-zar-hein)
- 📧 Email: khinezarhein1@gmail.com

---

## ⚡ Current Focus
- Preparing for Software Engineering internships
- Contributing to open source
- Building real-world full-stack systems
- Practicing Data Structures & Algorithms

---
