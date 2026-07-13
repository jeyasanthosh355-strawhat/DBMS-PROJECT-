# 🛒 E-Commerce Order Management Database System

## 📌 Project Overview

The **E-Commerce Order Management Database System** is a semester-long database project developed to analyze, design, and implement a centralized database for an online shopping platform. The project follows a structured Software Development Life Cycle (SDLC), beginning with requirement analysis and progressing through database design, normalization, SQL implementation, and report generation.

This repository contains the deliverables for **Week 1**, which focus on understanding the business requirements and preparing the Software Requirement Specification (SRS) document that serves as the foundation for the remaining phases of the project.

---

## 🎯 Project Objectives

The primary objectives of this project are to:

* Analyze the business requirements of an E-Commerce Order Management System.
* Understand the workflow of an online shopping platform.
* Identify the core entities and their roles within the system.
* Document functional and non-functional requirements.
* Define the project scope, assumptions, and constraints.
* Prepare a professional Software Requirement Specification (SRS).
* Build a strong foundation for future database design and implementation.

---

## 📂 Repository Structure

```text
Week1/
│── Requirement_Analysis_Report.pdf
│── Business_Requirement_Document.pdf
│── SRS_Document.pdf
│── README.md
```

---

## 📄 Week 1 Deliverables

This repository includes the following documents:

* **Requirement Analysis Report** – Analysis of the business scenario and system requirements.
* **Business Requirement Document** – Business goals, processes, and system requirements.
* **Software Requirement Specification (SRS)** – A structured document describing the complete system requirements.
* **README.md** – Project overview and repository documentation.

---

## 🗂 Core Entities

The project is based on the following mandatory entities:

* Customer
* Category
* Product
* Supplier
* Order
* Order Details
* Payment
* Shipment
* Review

These entities will be used consistently throughout all phases of the project, including database design, ER diagrams, normalization, SQL implementation, and report generation.

---

## 🛠 Technologies & Concepts

* Database Management System (DBMS)
* Requirement Analysis
* Software Requirement Specification (SRS)
* Business Process Analysis
* Database Design
* Entity Relationship Modeling (Upcoming)
* Normalization (Upcoming)
* SQL (Upcoming)

---

## 🚀 Future Work

The following phases will be completed in the upcoming weeks:

* Entity Relationship (ER) Diagram
* Relational Schema Design
* Database Normalization
* SQL Table Creation
* Data Insertion
* SQL Queries
* Report Generation
* Database Testing and Validation

---

## 👨‍💻 Author

** Santhosh**

Bachelor of Computer Applications (BCA)

Semester Database Management System Project

---

## 📜 License

This repository is created for academic and educational purposes as part of a college semester project.










Week 2                                                                                                                                                                                                                                               E-Commerce Order Management Database System

Introduction

This project focuses on the Entity and Relationship Analysis of the E-Commerce Order Management Database System. The objective is to identify the entities required for the system, define their attributes, determine the primary and foreign keys, and analyze the relationships between them. This analysis provides the foundation for designing an efficient, consistent, and well-structured relational database.

Objectives
Identify all entities used in the system.
Define attributes for each entity.
Identify Primary Keys (PK) and Foreign Keys (FK).
Apply database constraints such as NOT NULL, UNIQUE, DEFAULT, and CHECK.
Analyze relationships between entities.
Determine the cardinality of each relationship.
Prepare a complete Entity and Relationship Analysis Report.
Project Files
Week2/
│── Entity_Analysis_Report.pdf
│── Entity_Relationship_Analysis.pdf
│── README.md
Entities Identified

The database consists of the following entities:

Customer
Category
Supplier
Product
Orders
Order_Details
Payment
Shipment
Review
Relationship Analysis

The following relationships are identified in the system:

Customer → Orders (One-to-Many)
Category → Product (One-to-Many)
Supplier → Product (One-to-Many)
Orders → Order_Details (One-to-Many)
Orders → Payment (One-to-One)
Orders → Shipment (One-to-One)
Customer → Review (One-to-Many)
Product → Review (One-to-Many)
Orders ↔ Product (Many-to-Many through Order_Details)
Key Features
Customer Registration Management
Product and Category Management
Supplier Management
Inventory Tracking
Order Processing
Payment Recording
Shipment Tracking
Customer Review Management
Relationship and Cardinality Analysis
Deliverables

The Week 2 submission includes:

Entity Identification Report
Entity Attribute List
Primary Key and Foreign Key Identification
Relationship Analysis
Cardinality Analysis
Entity and Relationship Analysis Report
Technologies Used
Database Design Concepts
Entity Relationship (ER) Modeling
Relational Database Principles
Documentation using Microsoft Word and PDF
GitHub for Project Submission
Conclusion

The Entity and Relationship Analysis provides a clear understanding of how data is organized and connected within the E-Commerce Order Management Database System. The identified entities, keys, relationships, and cardinalities help create a normalized database that reduces redundancy, maintains data integrity, and supports efficient business operations. This analysis serves as the foundation for developing the ER Diagram and implementing the database in the next phase of the project.
