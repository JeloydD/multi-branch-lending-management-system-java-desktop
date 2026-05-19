# Dolferta Lending System

A centralized multi-branch Lending Management System developed for **Dolferta Company** using **Java (J2SE)** and **Java Swing** desktop technology.

This system was designed to replace the company’s traditional manual workflow and provide real-time monitoring, reporting, and transaction management across multiple branch locations while maintaining strict security controls required by the business owner.

---

# 📌 Project Overview

Before the implementation of this system, Dolferta Company relied entirely on manual processes for handling lending operations. Since the company operates across **three different branch locations**, daily management became increasingly difficult for the owner.

The company needed a solution capable of handling:

- Borrower loan applications
- Loan approvals
- Loan releasing
- Daily collections
- Cashier tally reports
- Ledger management
- Balance sheets
- Transaction monitoring
- Employee activity monitoring
- Multi-branch transaction synchronization

To solve these operational challenges, a custom desktop-based centralized lending system was developed using Java Swing and a remotely hosted MySQL database.

---

# 🖥️ System Architecture

Unlike modern browser-based systems, this project was intentionally developed as a **desktop application** due to the company owner's strict security requirements.

The company preferred:
- Controlled access
- Device-level authorization
- Employee activity monitoring
- Restricted external access
- Centralized data visibility

The application uses:
- **Java Swing (J2SE)** for the desktop interface
- **MySQL Database Hosting** from GoDaddy
- Real-time database synchronization through host connection
- Remote deployment and maintenance updates

Although the company has GoDaddy hosting, only the **MySQL hosting service** is utilized. The system does not use cPanel or any browser-based environment.

---

# 🔒 Security Features

Security was one of the highest priorities during development.

The system implements a strict access-control mechanism where:

- All users must first be registered by the system administrator
- All computers/devices must also be registered before use
- Registered user credentials alone are NOT enough to access the system
- Login is denied if the computer itself is not authorized

This means that even if someone has:
- A copy of the software
- Valid user credentials

They still cannot access the system unless the machine is officially registered in the database.

This additional layer of device authorization provides enhanced operational security for sensitive lending and financial records.

---

# 🌐 Multi-Branch Real-Time Monitoring

One of the major goals of the system was centralized business monitoring across all branches.

Because all branches are connected to a single hosted MySQL database:

- Transactions are synchronized in real time
- Data entries from all branches become immediately visible
- The owner can monitor operations remotely
- Daily employee activities can be reviewed centrally
- Branch performance can be checked without physical visits

This setup allows the business owner to:
- Travel outside the country
- Monitor transactions remotely
- Track employee productivity
- Review branch reports anytime

without needing to visit each branch daily.

---

# ✨ Core Features

## Loan Management
- Borrower registration
- Loan application processing
- Loan approval workflow
- Loan releasing management

## Collection & Payment Monitoring
- Daily collection tracking
- Payment history management
- Outstanding balance monitoring

## Financial Reporting
- Cashier tally reports
- Ledger reports
- Daily transaction reports
- Balance sheet generation

## Multi-Branch Management
- Centralized branch monitoring
- Real-time transaction synchronization
- Cross-branch visibility

## Employee Monitoring
- User activity tracking
- Login monitoring
- Access restriction management

## Security & Access Control
- User authorization
- Computer/device registration
- Restricted login validation
- Administrative access management

---

# 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Java (J2SE) | Core application development |
| Java Swing | Desktop graphical user interface |
| MySQL | Centralized database |
| JDBC | Database connectivity |
| GoDaddy MySQL Hosting | Remote database hosting |
| Remote Access Tools | System deployment and updates |

---

# 📸 Screenshots & System Preview

Due to business security and data privacy considerations, only a limited prototype version of the system is publicly showcased in this repository.

The screenshots and preview videos intentionally exclude several sensitive modules, internal tools, security configurations, and financial operations used by the actual production environment.

The shared media is primarily intended for:
- Educational purposes
- System flow demonstration
- UI structure reference
- Lending process visualization
- Developer inspiration

---

# 📂 Recommended Repository Structure

```bash
project-root/
│
├── screenshots/
│   ├── dashboard.png
│   ├── borrower-module.png
│   ├── loan-approval.png
│   ├── collections.png
│   ├── reports.png
│   └── user-monitoring.png
│
├── previews/
│   └── lending-system-preview.mp4
│
└── README.md
```



---

# 🎬 System Prototype Demo Videos

The following videos showcase selected prototype workflows of the Lending System project.  
For security and privacy reasons, only limited features and non-sensitive modules are publicly demonstrated.

These videos are intended to help developers understand:
- Lending workflow processes
- Loan transaction flow
- Report generation structure
- Multi-module integration
- Real-world lending operations

Although the interface shown is a prototype version, the core focus of the project is the actual business logic and operational process behind the system.

---

## 1️⃣ Salary Loan Entry to Printing of Reports
> Demonstration of the complete salary loan processing workflow, from borrower loan entry up to report generation.

🎥 YouTube Demo Link:  
<a href="https://www.youtube.com/watch?v=B4u2zdgEsQc" target="_blank">
  <img src="https://img.youtube.com/vi/B4u2zdgEsQc/hqdefault.jpg" alt="Watch the video on YouTube"/>
</a>

---

## 2️⃣ Business Loan Entry to Printing of Reports
> Demonstration of business loan application processing, transaction management, and report printing workflow.

🎥 YouTube Demo Link:  
<a href="https://www.youtube.com/watch?v=69Goz_TktVU" target="_blank">
  <img src="https://img.youtube.com/vi/69Goz_TktVU/hqdefault.jpg" alt="Watch the video on YouTube"/>
</a>

---

## 3️⃣ Pensioner Loan Entry to Printing of Reports
> Demonstration of pensioner loan processing, monitoring, and financial reporting workflow.

🎥 YouTube Demo Link:  
`PASTE_YOUR_YOUTUBE_LINK_HERE`


---

# 📈 Project Impact

After deployment, the system significantly improved the company’s operational efficiency by:

- Eliminating most manual processes
- Improving transaction accuracy
- Centralizing branch monitoring
- Reducing reporting delays
- Improving employee accountability
- Simplifying financial record management
- Providing real-time operational visibility

The project became an essential part of the company’s daily lending operations.

---

# 📂 Project Status

✅ Completed  
✅ Deployed in production  
✅ Supports 3 branch locations  
✅ Real-time centralized monitoring operational

---

# 👨‍💻 Developer

**Jeloyd Derla**  
Freelance Software Developer & Content Creator

I build real-world business systems, desktop applications, web applications, and digital solutions designed to solve operational challenges.

Beyond coding, I also create and edit content for businesses and social media platforms.

---

# 📄 License

This project was developed as a private/custom business solution for Dolferta Company.

Unauthorized redistribution or commercial reuse may require approval from the company owner.
