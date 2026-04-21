# 👋 Hi, I'm Khine Zar Hein
🎓 Computer Science Student @ Cal Poly Pomona (Class of 2027)

💻 Full-Stack Developer | Open Source Contributor | SWE Internship Candidate

📍 West Covina, CA

---

## 🚀 About Me

I  enjoy building software that solves real problems with clean architecture and reliable functionality.

- Building BurmaLingo — an English learning web app for Burmese speakers where structured classes cost half a month's salary in Myanmar. 10-level curriculum, SM-2 spaced repetition built from scratch, OpenAI GPT-4o-mini for AI feedback, Stripe billing. Live at burmalingo.vercel.app
- Built Inventra, a full-stack inventory and sales platform with JWT auth, automated email receipts via Resend, daily stock alerts with APScheduler, and a React/TypeScript analytics dashboard — deployed across 4 cloud services with CI/CD
- Built a Flask REST API during the MLH Production Engineering Hackathon that sustained 500 concurrent users at 76 RPS with zero failures using Redis caching, Nginx load balancing, and Docker
- Contributing to Submitty, an open-source university grading platform, with 4 pull requests across grading, privacy, and access control systems
- Currently completing CodePath's Advanced Technical Interview Prep while actively pursuing Software Engineering internships

---

## 💻 Technical Skills

**Languages**           
Java • Python • JavaScript • TypeScript • PHP • SQL • HTML • CSS         

**Backend & Infrastructure**     
FastAPI • Flask • Express.js • PostgreSQL • Redis • Nginx • Docker • Gunicorn • SQLAlchemy • APScheduler • Resend API • OpenAI API • GitHub Actions   

**Frontend & Tools**
React • Next.js • TypeScript • Tailwind CSS • Vite • Recharts • Git • Cypress • Vagrant • Linux/Unix • VS Code            

**Core Skills**    
Full-Stack Development • MVC Architecture • LLM Integration • REST APIs • Automated Testing • CI/CD • JWT Authentication • Data Structures & Algorithms 

---

## 🌍 Open Source Contributions

### Submitty
Open source course management and grading platform used by universities worldwide.

**Contributions:**
- Contributed 5 pull requests across grading, privacy, and access control systems in a production platform serving thousands of students and instructors
- Fixed a PHP bug in SubmissionController.php where bulk upload file conflict detection assumed filenames always contain a dot, causing silent merge failures
- Developed Cypress E2E tests validating privacy protections and grading workflows across student, TA, and instructor roles
- Fixed forum access control incorrectly excluding limited-access graders from staff functionality
- Expanded bulk upload sample datasets to improve automated grading test coverage
- Debugged CI failures and resolved flaky Cypress tests across multiple modules
- Addressed reviewer feedback across 3+ review cycles with maintainers

| PR | Description | Status |
|---|---|---|
| [#12535](https://github.com/Submitty/Submitty/pull/12535) | Cypress E2E tests for overridden grade banner | ✅ Merged |
| [#12562](https://github.com/Submitty/Submitty/pull/12562) | Legal name privacy tests across roles | 🔄 In Review |
| [#12571](https://github.com/Submitty/Submitty/pull/12571) | Bulk upload sample dataset expansion | 🔄 In Review |
| [#12607](https://github.com/Submitty/Submitty/pull/12607) | PHP bug fix for file conflict detection | 🔄 In Review |
| [#12715](https://github.com/Submitty/Submitty/pull/12715) | Forum access control audit | 🔴 Closed — behavior was intentional |

### Hyperledger Cacti              
Open source blockchain interoperability framework under LF Decentralized Trust.           

**Contributions:**         
- Updated outdated "Hyperledger Cactus" references to "Hyperledger Cacti" across core documentation files            

| PR | Description | Status |
|---|---|---|
| [#4267](https://github.com/hyperledger/cacti/pull/4267) | docs: update Cactus references to Cacti in contributing.md | 🔴 Closed — change not needed |
| [#4268](https://github.com/hyperledger/cacti/pull/4268) | docs: update Cactus references to Cacti in build.md | 🔄 In Review |

---

## 🌟 Featured Projects

### 🌏 BurmaLingo — English Learning Web App for Burmese Speakers
In Myanmar, a single level of English class from a well-known teacher costs roughly half a month's basic salary — for a seat in a 100-person Zoom class where the teacher doesn't know your name. Cheaper video courses cover only one level with no structured progression. Other apps weren't built for Burmese speakers. BurmaLingo is the structured, affordable alternative.

**Stack:** TypeScript • Tailwind CSS • FastAPI • PostgreSQL • MVC • JWT • OpenAI API • GitHub Actions

-10-level curriculum (Beginner I through IELTS Practice) with placement test on signup            
-SM-2 spaced repetition algorithm implemented from scratch for vocabulary scheduling              
-Integrated OpenAI GPT-4o-mini for AI writing and translation feedback — server-side rate limiting enforces free vs paid access    
-Stripe subscription billing with webhook-based free/pro tier access control         
-MVC architecture — SQLAlchemy models, FastAPI routers as controllers, React frontend as view layer        
-CI/CD pipeline with GitHub Actions running pytest and TypeScript build checks on every push         

[📂 GitHub](https://github.com/Khine12/burmalingo) | [🌐 Live](https://burmalingo.vercel.app)

---

### 📦 Inventra — Inventory & Sales Management Platform
Full-stack inventory management platform for small businesses with automated stock tracking, email receipts, and scheduled daily alerts.

**Stack:** Python • FastAPI • PostgreSQL • React • TypeScript • JWT • Resend • APScheduler • pytest • GitHub Actions

- Built production REST API with automatic stock deduction and server-side negative stock guard
- Integrated Resend API to fire email receipts automatically after every transaction
- Added APScheduler to email sellers daily about low-stock and expiring items — no manual trigger
- Deployed across 4 cloud services with GitHub Actions CI/CD running 9 pytest tests on every push

[📂 Backend](https://github.com/Khine12) | [📂 Frontend](https://github.com/Khine12) | [🌐 Live Demo](https://khine12.github.io)

---

### ⚙️ MLH Production Engineering Hackathon — Flask REST API
Production-grade REST API completing the Reliability, Scalability, and Incident Response quest tracks.

**Stack:** Python • Flask • PostgreSQL • Redis • Nginx • Docker • Locust • pytest • GitHub Actions

- Redis caching + Nginx load balancing across 2 Gunicorn containers — 500 concurrent users at 76 RPS, 0 failures
- Structured JSON logging, live metrics endpoint, Discord alerting with auto-recovery detection
- 83% pytest coverage across 19 tests, GitHub Actions CI/CD with Docker Compose

[📂 GitHub](https://github.com/Khine12)

---

### 📅 ShiftSync — Full-Stack Shift Scheduling Platform *(collaborative)*
Web-based scheduling application for small businesses, built as a 3-person team project.

**Stack:** Next.js (TypeScript) • Express.js (TypeScript) • PostgreSQL • JWT Authentication

- Designed and implemented a Messenger-style in-app messaging system with persistent PostgreSQL storage
- Fixed a bug where managers weren't automatically added to team membership on team creation
- Fixed authentication state management across the frontend navbar

[📂 GitHub](https://github.com/Khine12) | [🌐 Live Demo](https://shiftsync13.vercel.app/)      

---

## 📚 Technical Training

**CodePath — Advanced Technical Interview Prep** | Feb 2026 - May 2026                                    
Selected for a competitive program focused on data structures, algorithms, and Python problem solving under time constraints.

---

## 🎓 Education

**California State Polytechnic University, Pomona**              
B.S. in Computer Science — Expected Dec 2027 | GPA: 3.7

**Los Angeles City College**                 
Associate Degree, 2025 | GPA: 3.7 | Transferred with Honors

---

## 📫 Connect With Me

🌐 Portfolio: [khine12.github.io](https://khine12.github.io)             
💼 LinkedIn: [linkedin.com/in/khine-zar-hein](https://linkedin.com/in/khine-zar-hein)            
📧 Email: khinezarhein1@gmail.com                     

---

## ⚡ Current Focus

- Building BurmaLingo — targeting July 2026 launch
- Contributing to Submitty open source project
- Preparing for Software Engineering internships
- Practicing Data Structures & Algorithms (CodePath)
