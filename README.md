# 🚀 The New Republic  
### Smart City Municipal Management System

A modern database-driven smart-city platform designed to centralize citizen management, municipal services, transportation systems, and digital governance operations through a powerful Oracle relational database architecture.

---

# 🌍 Overview

**The New Republic** is inspired by real-world digital governance platforms such as:

- 🇦🇪 Dubai Smart City Portal  
- 🇸🇬 Singapore OneService  
- 🇪🇬 Digital Egypt  
- 🏙️ Egypt’s New Administrative Capital (NAC)

The project simulates the infrastructure of a modern city by managing:

🏢 Buildings  
👥 Citizens  
🪪 Citizen ID Cards  
🛠️ Municipal Services  
📨 Service Requests  
🚗 Transport Vehicles  

It demonstrates how smart cities can efficiently organize and process massive interconnected datasets using Oracle Database technologies and advanced SQL concepts.

---

# ☁️ Built Using Oracle Live SQL Cloud

This project was fully designed, implemented, and tested using:

## 🟠 Oracle Live SQL Cloud

Oracle Live SQL provided a complete cloud-based development environment for:

✅ Database Design  
✅ SQL Query Execution  
✅ PL/SQL Development  
✅ Trigger Implementation  
✅ Relational Database Testing  
✅ Cloud-Based Database Operations  

The entire system was developed and validated directly on Oracle’s cloud infrastructure, showcasing real-world Oracle database development workflows.

---

# ✨ Key Features

✅ Citizen Residency Management  
✅ Building Occupancy Tracking  
✅ Municipal Service Management  
✅ Service Request Processing  
✅ Digital Identity Card System  
✅ Vehicle Registration Management  
✅ Stored Procedures & SQL Functions  
✅ Automated Database Triggers  
✅ Complex Analytical Reports  
✅ Relational Database Modeling  
✅ ER Diagram & Relational Mapping  

---

# 🏗️ System Architecture

The system revolves around several interconnected entities that simulate real municipal operations.

## 📌 Core Entities

- 👤 Citizens
- 🏢 Buildings
- 🪪 Citizen Cards
- 🛠️ Services
- 📨 Service Requests
- 🚗 Transport Vehicles

---

## 🔗 Relationships

- A citizen resides in one building 🏢
- Citizens may own multiple vehicles 🚗
- Citizens may possess multiple ID cards 🪪
- Citizens can request multiple municipal services 📨
- Services can be requested by many citizens 🛠️

---

# ⚙️ Technologies Used

| Technology | Purpose |
|---|---|
| 🟠 Oracle Live SQL Cloud | Cloud Database Environment |
| 💾 SQL | Database Queries |
| ⚡ PL/SQL | Procedures, Functions & Triggers |
| 🧩 ER Modeling | Database Design |
| 🏗️ Relational Mapping | Schema Construction |

---

# 🧠 Database Components

## 🏛️ DDL (Data Definition Language)

Implementation includes:

- CREATE TABLE
- PRIMARY KEY Constraints
- FOREIGN KEY Relationships
- Data Integrity Constraints
- Relational Structure Design

---

## ✍️ DML (Data Manipulation Language)

Supported operations:

- ➕ INSERT
- ✏️ UPDATE
- ❌ DELETE

---

# ⚡ Procedures & Functions

## 🔧 Procedure — `update_citizen_age`

Updates a citizen’s age dynamically using PL/SQL.

```sql
BEGIN
    update_citizen_age(101, 30);
END;
/
```

---

## 📊 Function — `count_citizens_in_building`

Returns the total number of citizens living in a specific building.

```sql
SELECT count_citizens_in_building(1) FROM dual;
```

---

# 🤖 Automated Trigger

## 📨 `trg_default_request_status`

Automatically sets the service request status to:

```sql
'Pending'
```

if no status is provided during insertion.

This ensures consistency and automation inside the database system.

---

# 📈 Advanced System Reports

The project includes multiple advanced SQL analytical reports.

---

## 👴 Citizens Older Than Average Age

Analyzes city demographics and population distribution.

---

## 🏢 Buildings With More Than 3 Residents

Tracks building occupancy and density statistics.

---

## 🛠️ Services With At Least One Request

Identifies active municipal services being used by citizens.

---

## 🪪 Citizens With Active Cards

Verifies identity validity and service eligibility.

---

## 🚗 Vehicles Owned By Service Users

Connects transportation records with active municipal participation.

---

# 🎯 Project Goals

✅ Simulate real-world smart city infrastructure  
✅ Demonstrate advanced database concepts  
✅ Apply relational database design principles  
✅ Showcase Oracle SQL & PL/SQL implementation  
✅ Build scalable municipal system architecture  

---

# 🌐 Real-World Inspiration

The project is heavily inspired by modern digital transformation initiatives including:

🇦🇪 Dubai Smart Government  
🇸🇬 Singapore Smart Nation  
🇪🇬 Digital Egypt Initiative  
🏙️ New Administrative Capital (NAC)  

---

# 🧪 Learning Outcomes

This project demonstrates practical knowledge in:

- 🧠 Database Design
- ⚙️ Oracle SQL
- ⚡ PL/SQL Programming
- 🔗 Relational Algebra
- 📊 Query Optimization
- 🏙️ Smart City Infrastructure
- 🗂️ Data Modeling
- 🏛️ Municipal Information Systems

---

# 🚀 Future Enhancements

Potential future upgrades include:

- 🌐 Web-Based Dashboard
- 🔐 Authentication & Authorization
- 📡 Real-Time Analytics
- 🤖 Smart Service Automation
- 🔗 API Integration
- 🗺️ GIS & Smart Mapping
- ☁️ Cloud Infrastructure Support

---

# 👨‍💻 Contributors

- 👤 Mohamed Hazem Ahmed  
- 👤 Yahya Mohamed Salah El-Dein  
- 👤 Mostafa Ossama Mostafa  
- 👤 Islam Ahmed Mahmoud  

---

# 📜 Summary

**The New Republic** represents a scalable and modern smart-city database platform capable of simulating essential municipal operations through a fully structured relational architecture.

By integrating:

🏢 Buildings  
👥 Citizens  
🪪 Identity Systems  
🛠️ Municipal Services  
🚗 Transportation Records  
📨 Administrative Workflows  

the project demonstrates how modern cities can leverage database technologies to improve organization, governance, digital transformation, and public service efficiency.

---

# ⭐ If you found this project interesting, consider giving it a star!
