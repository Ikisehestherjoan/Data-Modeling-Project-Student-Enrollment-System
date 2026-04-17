# 🎓 Education Data Model Project – LearnSphere Academy

## 📌 Project Overview

LearnSphere Academy is an online education platform that offers courses in technology, business, and creative skills. Its users include students, instructors, and corporate organizations that sponsor employee learning.

Students enroll in courses, attend lessons, complete assignments, and receive certifications. Instructors manage course delivery and track performance, while organizations sponsor students and monitor progress.

The platform generates revenue through:

* Course purchases
* Subscriptions
* Corporate partnerships

This project focuses on designing a **scalable and structured database system** to support analytics on student performance, revenue trends, and course engagement.

---

## 🎯 Objectives

* Design a **conceptual ERD** to represent business requirements
* Develop a **logical data model** with primary and foreign keys
* Properly model:

  * Many-to-many relationships
  * One-to-many relationships
  * Optional dependencies

---

## 🧠 Conceptual Data Model

The conceptual model defines the high-level structure of the system:

* Students enroll in courses
* Instructors teach courses
* Payments are made per enrollment
* Sponsors may optionally cover payments

📷
![Conceptual ERD](Database%20Modelling/Conceptual%20Erd.png)

---

## 🏗️ Logical Data Model

The logical model translates the conceptual design into structured tables with defined keys and relationships.

### 🔑 Key Design Decisions

* Introduced an **Enrollment** table to resolve the many-to-many relationship between Students and Courses
* Linked **Payment** to Enrollment to ensure financial accuracy
* Modeled **Sponsor** as an optional entity (nullable relationship)

📷
![Logical ERD](Database%20Modelling/LOGICAL_ERD_\(Education_Casestudy\).png)

---

## 🗂️ Core Entities

* Student
* Course
* Instructor
* Enrollment
* Payment
* Sponsor

---

## 🔑 Key Features

* Fully normalized database design
* Proper use of primary and foreign keys
* Clear cardinality and relationships
* Scalable and analytics-ready structure

---

## 🚀 Future Improvements

* Implement SQL schema (DDL scripts)
* Build and automate ETL pipelines (Python / PySpark)
* Develop Power BI dashboards for analytics

---

## 💼 Project Value

This project demonstrates:

* Strong understanding of **data modeling concepts**
* Ability to translate business requirements into **technical design**
* Readiness for **data engineering and analytics roles**

