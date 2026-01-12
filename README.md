# H&O Company — Construction Business Platform

**Production-ready web platform designed to digitalize construction company operations, customer interactions, and internal workflows.**

This project reflects a real-world business application built with scalability, maintainability, and performance in mind — not a demo or tutorial project.

👉 **Live Demo:** https://hocompany1.com/

---


## 📸 Application Preview

<table>
  <tr>
    <td><img src="screenshots/dashboard-overview.png" alt="Dashboard Overview" width="300"/></td>
    <td><img src="screenshots/job-application-form.png" alt="Job Application Flow" width="300"/></td>
  </tr>
  <tr>
    <td><img src="screenshots/pro-build.png" alt="Admin Panel" width="300"/></td>
    <td><img src="screenshots/calendar-scheduling.png" alt="Scheduling Calendar" width="300"/></td>
  </tr>
  <tr>
    <td colspan="2"><img src="screenshots/payment-flow.png" alt="Payment Flow" width="620"/></td>
  </tr>
</table>



## 🧩 Business Context

Construction companies typically manage job applications, scheduling, payments, and customer communication through disconnected tools or manual processes.

This fragmentation leads to:
- operational inefficiency  
- lack of visibility  
- poor user experience for both clients and administrators  

---

## 💡 Solution Overview

H&O Company centralizes these workflows into a single web platform that enables:
- structured job application management  
- role-based access and administration  
- scheduling and calendar coordination  
- secure online payments  
- transparent ratings and feedback  

The focus is on **real usability, clean UX, and long-term maintainability**, similar to production environments.

---

## ⚙️ Technical Architecture & Decisions

- **React** for a modular, component-driven frontend architecture  
- **RESTful PHP API** with **MySQL** for backend data handling  
- **Axios** for consistent and predictable API communication  
- **React Context & custom hooks** to separate business logic from UI  
- **Google OAuth** for frictionless authentication  
- **PayPal integration** for real-world payment flows  
- **React Big Calendar** for scheduling visualization  

**Key priorities during development:**
- predictable data flow  
- reusable and isolated components  
- proper loading and error handling  
- responsive behavior across devices  

---

## ✨ Core Functionality

- User registration and Google authentication  
- Job application submission and status tracking  
- Role-based UI behavior (admin vs user views)  
- Ratings and feedback system  
- Calendar-based scheduling  
- Secure payment handling  

---

## 📁 Project Structure

```txt
api/        → PHP REST API (authentication, business logic, database access)
public/     → Static assets and application metadata
src/
 ├─ components/
 ├─ pages/
 ├─ features/
 ├─ hooks/
 ├─ context/
 └─ styles/
