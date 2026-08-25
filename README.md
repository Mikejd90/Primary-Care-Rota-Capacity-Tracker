# 🩺 Primary Care Rota & Capacity Tracker PCN & GP practice Project

> **⚠️ DEMO PURPOSE ONLY:** This application is a high-fidelity prototype built with synthetic data for demonstration, portfolio, and evaluation purposes only. It is **not** connected to any live General Practice, Primary Care Network (PCN), Integrated Care Board (ICB), or NHS Electronic Staff Record (ESR) systems. Do not input real patient or staff personal identifiable information (PII).
> **Prototype / Portfolio:** Demonstration. Created to showcase healthcare-focused web development, data visualisation, privacy-aware design and digital transformation concepts, do not use with live real data, fictional data only displayed

---

## 📌 About the Project
The **Primary Care Rota & Capacity Tracker** is an enterprise-grade web application engineered specifically for General Practice surgeries and Primary Care Networks (PCNs). Designed to solve the operational complexities of multi-site healthcare management, the platform automates workforce distribution across branch surgeries, enforces compliance with NHS Additional Roles Reimbursement Scheme (ARRS) financial caps, tracks inter-site travel expenses, and manages Agenda for Change (AfC) overtime—all within an accessible, responsive interface built to NHS design standards.

---

## 🛠️ Technology Stack
* **Frontend Architecture:** Vanilla JavaScript (ES6+), HTML5, and CSS3 (Single-Page Application architecture).
* **UI/UX Design System:** Built utilising NHS UK Frontend guidelines and design tokens for clinical accessibility (WCAG AA compliant contrast, accessible typography, and responsive grid layouts).
* **Data Handling & State Management:** Client-side reactive state engine supporting real-time conflict detection, CSV file parsing, and dynamic filtering by site, role, and week.
* **Export & Document Generation:** Integrated local blob generators supporting **iCal (.ics)** calendar sync, **CSV** exports, **Rich Text (.rtf)**, and print-ready CSS stylesheets for PDF generation.
* **Deployment Ready:** Static-ready SPA deployable instantly to GitHub Pages, Vercel, or Netlify.

---

## 🚀 Core Features & Capabilities

* **Multi-Site Rota Rotation Management:** Seamlessly schedule staff across multiple branch surgeries with live visibility over clinic capacity and room allocations.
* **NHS ARRS Financial Cap Compliance:** Real-time tracking of workforce expenditure against national reimbursement limits and multidisciplinary role benchmarks.
* **Automated Leave & Clash Alerts:** Intelligent conflict detection that highlights scheduling overlaps and flags clinical discipline safety thresholds (e.g., >30% leave alerts).
* **Inter-Site Mileage & Travel Calculator:** Computes business travel expenses between branch sites with integrated policy notices regarding contractual *Employee Arrangements*.
* **Microsoft Teams Directory Integration:** Centralized clinician contact hub with deep-linking (`msteams://`) for instant peer-to-peer messaging and patient care escalations.
* **Agenda for Change (AfC) Overtime Management:** Tracks additional hours worked beyond the standard 37.5-hour week, calculating Time-and-a-Half (1.5x), Bank Holiday enhancements, or Time Off In Lieu (TOIL).
* **Comprehensive Audit Trail & Governance Log:** Information Governance (IG) compliance log recording all administrative overrides, shift adjustments, and payroll calculations.
* **Master Rota Book & Reception Router:** Printable landscape master books for staff rooms alongside a patient symptom-to-ARRS clinician routing tool for practice receptionists.

---

## 🔮 Future Roadmap & Scalability

As this project evolves from a high-fidelity prototype into a production-grade healthcare product, the following advanced architectural enhancements are planned:

1. **Role-Based Access Control (RBAC) Integration:**  
   Implementing granular, token-based authentication (OAuth2 / JWT) with multi-tiered permissions—separating standard clinical views from Practice Manager financial controls and ICB oversight dashboards.
2. **Progressive Web App (PWA) & Mobile Portal:**  
   Enabling mobile-first access for frontline staff to check personal shift rotas, submit annual leave requests, and log travel mileage on the go.
3. **Electronic Staff Record (ESR) API Synchronisation:**  
   Building backend API connectors to automatically pull staff competencies, mandatory training expiry dates (e.g., BLS, Safeguarding), and DBS renewals directly from NHS data feeds.
4. **AI-Driven Rota Optimisation:**  
   Introducing a predictive scheduling algorithm that suggests optimal workforce distributions based on historical patient footfall heatmaps and travel distance minimization.

---
🟡 Prototype / Portfolio Demonstration

Created to showcase healthcare-focused web development, data visualisation, privacy-aware design and digital transformation concepts, do not use with live real data, fictional data only

## 📄 License & Terms of Use

**Demonstration and Portfolio Use Only**  
Copyright (c) 2026. This project is shared strictly for portfolio display, technical demonstration, and evaluation purposes. 

* **No Production Warranty:** This provided / showcased "as is", without warranty of any kind, express or implied. 
* **Data Restriction:** This repository contains synthetic dummy data only. Unauthorized use with live NHS patient data or real staff PII is strictly prohibited.
