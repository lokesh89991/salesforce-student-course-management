# 🎓 Student Course Management System (Salesforce CRM)

## 📖 Project Overview
This project is a Salesforce Lightning application designed to manage students and courses efficiently. It demonstrates data modeling, lookup relationships, and Lightning app configuration.

---

## 🏗️ Architecture

Course (Parent)
   ⬇
Student (Child via Lookup Relationship)

One Course → Many Students  
Each Student → One Course

---

## 🔹 Objects Created

### 1️⃣ Course Object
Fields:
- Course Name
- Course Fee
- Duration
- Course Type
- Trainer Name

### 2️⃣ Student Object
Fields:
- Student Name
- Email
- Phone
- Date of Birth
- Admission Date
- Fees Status
- Course (Lookup Field)

---

## 🔗 Relationship
Implemented a Lookup Relationship:
Student → Course

This allows:
- Multiple students linked to one course
- Automatic related list on Course record

---

## ⚙️ Features Implemented

- Custom Objects
- Custom Fields
- Lookup Relationship
- Custom Tabs
- Lightning App Configuration
- Profile-Based Access
- Navigation Customization

---

## 📊 Working Flow

1. Admin creates Course records
2. Admin creates Student records and selects Course
3. Course record displays related Students automatically

---

## 🖼️ Project Screenshots

### Course Object
![Course Object](screenshots/course-object.png)

### Student Object
![Student Object](screenshots/student-object.png)

### Relationship
![Relationship](screenshots/relationship.png)

### Course Related Students
![Course Related Students](screenshots/course-related-students.png)

### Student Details
![Student Details](screenshots/student-details.png)

---

## 🧠 Concepts Used

- Salesforce Data Modeling
- Lookup Relationship
- Lightning Experience
- App Manager
- Object Manager
- Page Layout Customization

---

## 🚀 Future Enhancements

- Implement Many-to-Many using Enrollment Object
- Add Flow Automation
- Create Reports and Dashboards
- Add Validation Rules

---

## 👨‍💻 Author
Pinnama Raju Sai Lokesh
