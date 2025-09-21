# clinic_booking
clinic_booking assignment
# Clinic Booking System Database (MySQL)

## 📌 Overview
This project implements a **relational database management system** for a **Clinic Booking System** using **MySQL**.  
It is part of the assignment (Frameworks, Question 1) where the objective is to **design and implement a full-featured relational database** with proper schema, constraints, and relationships.

---

## 🏥 Use Case
The **Clinic Booking System** manages:
- Patients
- Doctors
- Appointments
- Prescriptions
- Bills

It ensures efficient handling of:
- Scheduling appointments
- Storing medical prescriptions
- Tracking billing and payments

---

## 📂 Database Schema

### **Tables**
1. **Patients** – stores patient details  
2. **Doctors** – stores doctor details with specialization  
3. **Appointments** – links patients and doctors (many-to-many)  
4. **Prescriptions** – medications linked to an appointment  
5. **Bills** – one-to-one billing record per appointment  

### **Relationships**
- One Patient ⟶ Many Appointments  
- One Doctor ⟶ Many Appointments  
- One Appointment ⟶ Many Prescriptions  
- One Appointment ⟶ One Bill  

Constraints used:
- **PRIMARY KEY**
- **FOREIGN KEY**
- **NOT NULL**
- **UNIQUE**
- **ON DELETE CASCADE**

---

## ⚙️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/<your-repo-name>.git
   cd <your-repo-name>
