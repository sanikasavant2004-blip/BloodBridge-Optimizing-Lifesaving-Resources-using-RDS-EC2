#  BloodBridge: Optimizing Lifesaving Resources using RDS,EC2
 


## Prepared For

Smart-Internz
Cloud Practitioner Guided Project

# Final Project Report

# Table of Contents

1. Introduction
2. Problem Statement
3. Purpose of the Project
4. Scope of the Project
5. Significance of the Project
6. System Architecture
7. AWS Services Utilized
8. Proposed Solution
9. Features of the System
10. Sprint Planning & Product Backlog
11. Application Deployment Steps
12. Advantages & Disadvantages
13. Conclusion
14. Future Scope

---

# 1. Introduction

BloodBridge is a cloud-based blood management system developed using AWS services to improve blood donation, inventory management, and emergency blood request handling. Traditional blood bank systems often face delays, poor coordination, and inventory issues. BloodBridge solves these problems through real-time data management and cloud-native infrastructure.

The platform connects donors, hospitals, blood banks, and administrators through a centralized system that enables faster communication, secure data handling, and efficient blood availability tracking.

---

# 2. Problem Statement

### PS-1

A hospital administrator wants to urgently request rare blood during emergencies, but finding matching donors takes too much time because manual coordination is slow.

### PS-2

A regular donor wants to manage blood donations and eligibility schedules but does not receive timely updates about donation drives.

### PS-3

A blood bank manager wants to update inventory in real-time, but current systems are not synchronized across hospitals.

---

# 3. Purpose of the Project

The main objective of BloodBridge is to create a centralized and intelligent blood management system that ensures the right blood reaches the right patient at the right time.

The project improves:

* Emergency response
* Blood inventory visibility
* Donor engagement
* Hospital coordination
* Secure healthcare data management

---

# 4. Scope of the Project

The project includes:

* Web-based donor registration system
* Hospital blood request management
* Real-time inventory dashboard
* AWS cloud deployment
* Role-based login system
* Scalable backend architecture

Future enhancements such as AI prediction and mobile application support are also possible.

---

# 5. Significance of the Project

BloodBridge addresses several major healthcare challenges:

* Delays in emergency blood availability
* Lack of centralized blood inventory systems
* Manual data handling and errors
* Poor donor-hospital communication
* Blood wastage due to improper management

The project improves operational efficiency and helps save lives through faster access to blood resources.

---

# 6. System Architecture

## Application Layer

* Hosted on Amazon EC2
* REST APIs using Node.js / Python

## Data Layer

* Amazon RDS for relational data
* Amazon DynamoDB for real-time inventory

## Storage

* Amazon S3 for reports, images, and documents

## Authentication

* Amazon Cognito for secure login

## Monitoring

* AWS CloudWatch for logs
* AWS CloudTrail for activity tracking

## Architecture Flow

User → API Gateway → EC2/Lambda → RDS/DynamoDB → S3

---

# 7. AWS Services Utilized

## Amazon EC2

Used for hosting backend applications and APIs.

## Amazon RDS

Stores structured data such as donor profiles, hospital requests, and login credentials.

## Amazon DynamoDB

Used for real-time blood stock management and availability tracking.

## Amazon S3

Stores uploaded documents, reports, and images securely.

## Amazon Cognito

Provides secure authentication and role-based access.

## AWS CloudWatch

Used for monitoring logs and application performance.

---

# 8. Proposed Solution

BloodBridge is a cloud-native healthcare platform that provides:

* Real-time blood inventory tracking
* Donor registration and management
* Hospital request workflows
* Secure login and authentication
* Dashboard for administrators
* Monitoring and audit logs

The platform ensures seamless coordination between all stakeholders.

---

# 9. Features of the System

* Real-Time Inventory Dashboard
* Donor Management System
* Hospital Request Workflow
* Role-Based Access Control
* Secure Cloud Storage
* Notification System
* Monitoring & Logging

---

# 10. Sprint Planning & Product Backlog

| Sprint   | User Story | Description                        | Priority |
| -------- | ---------- | ---------------------------------- | -------- |
| Sprint 1 | USN-1      | User Registration & Role Selection | High     |
| Sprint 1 | USN-2      | AWS Cognito Authentication         | High     |
| Sprint 1 | USN-3      | Blood Inventory Input              | High     |
| Sprint 2 | USN-4      | Blood Request Workflow             | High     |
| Sprint 2 | USN-5      | Notification System                | Medium   |
| Sprint 3 | USN-6      | Admin Dashboard                    | Medium   |
| Sprint 3 | USN-7      | CloudWatch Logging                 | Medium   |
| Sprint 4 | USN-8      | UI/UX Improvements                 | Low      |
| Sprint 4 | USN-9      | Deployment Automation              | Medium   |
| Sprint 4 | USN-10     | Final Testing                      | High     |

---

# 11. Application Deployment Steps

## Step 1: Local Development

* Build and test the application locally
* Configure environment variables

## Step 2: AWS Deployment

* Upload frontend and backend files
* Configure AWS services

## Step 3: Infrastructure Configuration

* Configure EC2, RDS, DynamoDB, IAM roles, and Security Groups

## Step 4: Testing

* Perform integration and load testing

## Step 5: Production Release

* Configure HTTPS and DNS
* Deploy live application

---

# 12. Advantages & Disadvantages

## Advantages

* Real-time blood inventory updates
* Faster emergency response
* Secure cloud infrastructure
* Reduced blood wastage
* Better donor engagement
* Scalable architecture

## Disadvantages

* Requires stable internet connection
* AWS operational costs
* Staff training required
* Cloud security compliance needed

---

# 13. Conclusion

BloodBridge is an innovative cloud-based blood management solution designed to modernize healthcare operations. By integrating AWS services such as EC2, RDS, DynamoDB, S3, and Cognito, the platform delivers secure, scalable, and real-time blood resource management.

The system improves emergency responsiveness, reduces blood wastage, and enhances coordination among hospitals, donors, and blood banks. BloodBridge represents a major step toward smarter healthcare infrastructure and efficient lifesaving resource management.

---

# 14. Future Scope

Future enhancements include:

* AI-based blood demand prediction
* Android & iOS mobile applications
* Google Maps integration
* Blockchain-based donor history
* IoT-enabled blood transportation tracking
* Voice assistant and chatbot support
* Multilingual support
* Government healthcare integration
* Advanced analytics dashboard

These future developments will further improve healthcare efficiency and accessibility.


# Group Project By                       PRN No
Shafika Shakil Nadaf.                   2023011032057

Sanika Arjun Savant.                    2023011032083

Gauri Anil Chougale.                    2023011032011
D Y Patil Agriculture and Technical University, Talsande
