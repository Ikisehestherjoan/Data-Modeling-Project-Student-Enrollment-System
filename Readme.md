---

> **Data Modeling Project: Student Enrollment System (Conceptual & Logical Design)**

---

## 📌 Project Overview
## 🎓 1. EDUCATION SECTOR CASE STUDY
Case Study: LearnSphere Academy

LearnSphere Academy is an online education platform that provides courses in tech, business, and creative skills. Its users include students, instructors, and corporate organizations that sponsor employee learning.

Students enroll in courses, attend lessons, complete assignments, and receive certificates upon completion. Instructors create courses and track student performance. Organizations can sponsor multiple students and monitor their progress.

The platform generates revenue through course purchases, subscriptions, and corporate partnerships.

The Head of Data at LearnSphere wants to build a data warehouse to analyze student performance, revenue trends, and course engagement.
This project focuses on designing a structured and scalable database system for a student enrollment platform. The work covers both conceptual and logical data modeling, ensuring proper normalization and clear relationship mapping.

---



## 🎯 Objectives

* Design a **conceptual ERD** to represent business requirements
* Develop a **logical data model** with primary and foreign keys
* Ensure proper handling of:

  * Many-to-many relationships
  * One-to-many relationships
  * Optional dependencies

---

## 🧠 Conceptual Data Model

The conceptual model defines the high-level structure of the system, including:

* Students enroll in courses
* Instructors teach courses
* Payments are made per enrollment
* Sponsors may optionally cover payments

📷 *![Alt text](Database Modelling/Conceptual Erd.png)*

---

## 🏗️ Logical Data Model

The logical model translates the conceptual design into structured tables with defined keys and relationships.

### Key Design Decisions:

* Introduced an **Enrollment table** to resolve the many-to-many relationship between students and courses
* Linked **Payment to Enrollment** to maintain financial accuracy
* Modeled **Sponsor as an optional entity**

📷 *![Alt text](Database Modelling/LOGICAL_ERD_(Education_Casestudy).png)*

---

## 🗂️ Entities

* Student
* Course
* Instructor
* Enrollment
* Payment
* Sponsor

---

## 🔑 Key Features

* Normalized database design
* Proper use of primary and foreign keys
* Clear cardinality 
* Scalable and analytics-ready structure

---

## 🚀 Future Improvements

* Implement SQL schema
* Build and Automate  ETL pipeline
* Develop analytical dashboards

---
