# 📊 TCCD Website

A multi-role event management platform for the TCCD community, built to streamline event registration, ticketing, company sponsorships, and volunteer management.

---

## 📌 Table of Contents

- [About the Project](#about-the-project)
- [Team Members](#team-members)
- [Software Tools](#software-tools)
- [Entities and Attributes](#entities-and-attributes)
- [Key Relationships](#key-relationships)
- [Current Milestone](#current-milestone)
- [Important Links](#important-links)

---

## 📖 About the Project

The TCCD Website is a full-stack application that enables different user roles (Admin, Business Representatives, Students/Graduates, and Volunteering Members) to interact with events through a tailored experience for each.

The platform handles:
- Event management and ticketing.
- Company sponsorship management.
- Volunteer coordination.
- Personal profiles and professional portfolios.

---

## 👥 Team Members

### 📦 Backend
- [Farouq DiaaEldin](https://github.com/FarouqDiaa) (Leader)
- Mostafa Mohamed Rabie
- Mostafa Ehab
- Kareem Ashraf Saeed
- Ali Bahr

### 🎨 Frontend
- [Anas Alaa Mohamed Ibrahim](https://www.github.com/AnAs101AlAa) (Leader)
- Hazem Yasser ElSayed Hassan
- Mohamed Ashraf
- Youssef Afify

### ⚙️ DevOps
- [Ahmed Mohamed Taha Wesal](http://www.github.com/tahaaa22) (Leader & Project Founder)

### 🧪 Testing
- Abdulrahman Ayman

---

## 🛠️ Software Tools

### Backend
- Framework: .NET + MVC
- Database: PostgreSQL
- API Docs: Swagger (OpenAPI)
- Testing: Moq, Fluent Assertions, xUnit

### Frontend
- Framework: React + Redux
- Styling: Bootstrap, TailwindCSS
- Testing: Jest

### DevOps
- Cloud & VM: Azure
- CI/CD: Jenkins
- Web Server: NGINX
- Containerization: Docker, Kubernetes
- IaC: Terraform, Ansible
- Monitoring: Prometheus

### Testing Tools
- Web: Cypress, Selenium
- Mobile: Appium

### Task Management
- Jira / GitHub Issues (Agile - Scrum methodology)

---

## 📊 Entities and Attributes

**User** | **Event** | **Company** | **Ticket** | **Profile**
:---|:---|:---|:---|:---
UserID (PK) | EventID (PK) | CompanyID (PK) | TicketID (PK) | ProfileID (PK)
Name | Name | Name | QR Code (Unique) | GPA
Email | Description | Details | Status | Academic Year
Password | Date |  |  | Department
Role | Location |  |  | CV (URL)
... | ... | ... | ... | ...

Additional profiles:
- Business Representative Profile
- Volunteering Member Profile

---

## 🔗 Key Relationships

- **Admin:** Full event and user management.
- **Business Representative:** Linked to one company, manage assigned events.
- **Student/Graduate:** Register for events after profile completion.
- **Volunteering Member:** Scan tickets, post event updates.

---

## 🎯 Current Milestone

📅 **Deadline:** 23-03-2025

### Features:
- Website initialization with role-based dashboards.
- Public homepage for non-logged-in users.
- User authentication (login/signup).
- CRUD event management for Admins.
- Event registration for students.
- Ticket management system.
- Volunteer event update and ticket scanning.
- Business representative event and sponsor management.

---

## 🔗 Important Links

- **Our Website:** [TCCD-CUFE](https://www.tccd-cufe.me)
- **GitHub Organization:** [Github](https://github.com/CUFE-TCCD)
