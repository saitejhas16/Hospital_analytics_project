# 🏥 Hospital Resource Utilization Analytics

## 📌 Project Overview
This project is a **data-driven hospital analytics solution** designed to monitor, analyze, and optimize the use of hospital resources.  
Built using **MySQL, Power BI, and DAX**, the system provides real-time dashboards and detailed reports on **patient inflow/outflow, bed occupancy, staff allocation, and equipment availability**.  

The aim is to help hospital administrators make **faster, evidence-based decisions** and ensure resources are allocated efficiently.

---

## 🚀 Tech Stack
- **Database**: MySQL (relational schema + sample data)  
- **Visualization**: Power BI (interactive dashboards + reports)  
- **DAX**: Custom KPIs and calculated measures  
- **Connector**: MySQL ODBC driver  

---

## 🗄️ Database Schema
The database `hospital_resource_db` includes:  
- **Patients** → demographics, diagnosis, condition status  
- **Departments** → hospital departments & head doctors  
- **Beds** → occupancy and type of bed (ICU, General, Emergency)  
- **Staff** → doctors, nurses, technicians, shifts, availability  
- **Admissions** → admission & discharge records  
- **Resource_Utilization** → daily inflow, outflow, staff counts  
- **Equipment** → units, availability, and maintenance status  

👉 See [`hospital_resource_seed.sql`](hospital_resource_seed.sql) for schema + seed data.

---

## 📊 Dashboard Overview

### 🔹 KPIs
- **Current Inpatients**  
- **Average Length of Stay (LOS)**  
- **Bed Occupancy %**  
- **Staff Availability %**  
- **Equipment Availability %**  
- **Critical Patients Count**  

### 🔹 Visuals
- **Line Chart** → Patient inflow vs outflow trend  
- **Donut Chart** → Patient distribution by department  
- **Bar Chart** → Reasons for admission (heart attack, pregnancy, diabetes, etc.)  
- **Matrix** → Bed occupancy vs staff availability by department  
- **Funnel Chart** → Patient journey (Admissions → Diagnosed → Critical → Recovering → Stable → Discharged)  
- **Gauges** → Bed occupancy %, Staff availability %, Equipment availability %  
- **Slicers** → Date, Department, Bed Type, Staff Role, Patient Condition  

---

## 📑 Detailed Reports

### 1. **Patients Data Report**
- Patient demographics (age group distribution)  
- Patient condition status split (Critical / Recovering / Stable)  
- Diseases by age group  
- Average LOS = **5.5 days**  

### 2. **Staff Data Report**
- Staff availability status (Available, Occupied, On Leave)  
- Staff distribution by role (Doctors, Nurses, Admin, Technicians)  
- Shift-wise allocation  

### 3. **Equipment Data Report**
- Total vs available equipment units  
- Maintenance status breakdown (Operational vs Under Maintenance)  
- Equipment availability by department  

### 4. **Hospital Operations Report**
- Patient inflow/outflow trend  
- Department-wise occupancy %  
- Department-wise staff availability %  
- Equipment availability %  

---

## 🏆 Key Insights
- Bed occupancy varied between **25%–75%** across departments.  
- Equipment availability maintained at **86.8% overall**.  
- Average hospital stay = **5.5 days**.  
- Staff shortages in certain departments (as low as 20% availability).  
- Funnel showed patient drop-off from **Admissions → Diagnosed → Stable/Discharged**.  

---

## ✨ Future Improvements
- Integrate **Python predictive model** (ARIMA/Prophet) for admissions forecasting.  
- Automate daily refresh in **Power BI Service**.  
- Add real-time **alerts** for critical metrics (e.g., bed occupancy > 90%).  

---
## 🤝 Let's Collaborate!

I'm open to collaboration on Python,data analysis, SQL automation, and media analytics projects.

📧 Email: [saitejhas49@gmail.com](mailto:saitejhas49@gmail.com)  
🔗 LinkedIn: [L.N. Sai Tejhas](https://linkedin.com/in/lnsaitejhas)

---

> Thank you for exploring this project! ⭐ If you found it helpful, consider giving the repo a star!

