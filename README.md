# SQL_Project
# 🧪 Laboratory Database Management System (SQL Project)

Welcome to my SQL-based Laboratory Database Management System, developed as part of my graduate coursework in Health Informatics at Rutgers University. This project demonstrates how relational databases can streamline clinical workflows, improve data integrity, and support better patient outcomes.

## 📌 Project Overview

This system models the end-to-end data flow of a clinical laboratory, from patient registration to test results and billing. It includes seven interconnected tables and supports advanced queries for operational insights and quality improvement.

## 🗂️ Database Schema

- **Doctors**: Tracks physician details and specialties  
- **Patients**: Stores patient demographics and links to assigned doctors  
- **Appointments**: Manages scheduling between patients and doctors  
- **Test_Orders**: Logs ordered lab tests and associated costs  
- **Test_Results**: Records outcomes of lab tests  
- **Billing_Info**: Handles financial transactions and billing status  
- **Survey**: Captures patient satisfaction and service feedback  

## 🔍 Key Features

- Relational schema with foreign key constraints  
- Transaction control using `START TRANSACTION`, `ROLLBACK`, and `COMMIT`  
- Complex SQL queries for clinical and operational insights  
- Views and indexing for performance optimization  
- Real-world scenarios like identifying patients without test results, analyzing satisfaction trends, and calculating billing totals by specialty

## 📊 Sample Queries

- Patients with appointments but no test orders  
- Doctors treating patients under 50 after a specific date  
- Average test cost per patient  
- Satisfaction analysis by test type and result  
- Specialty-based billing and satisfaction metrics

## 🎯 Objectives

This project aims to:
- Simulate a scalable, regulatory-compliant lab database  
- Demonstrate SQL proficiency in healthcare data contexts  
- Support clinical decision-making and operational reporting  
- Highlight the intersection of informatics, analytics, and patient care


