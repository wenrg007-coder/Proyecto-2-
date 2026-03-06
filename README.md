🧪 API Testing — Kit Management & Delivery Service
🛒 Urban Grocers
<p align="center"> <img src="https://img.shields.io/badge/QA-Testing-blue" /> <img src="https://img.shields.io/badge/API-REST-green" /> <img src="https://img.shields.io/badge/Manual%20Testing-Postman-orange" /> <img src="https://img.shields.io/badge/Bug%20Tracking-Jira-red" /> </p>
🔍 Overview

This repository showcases a manual API testing project for the Urban Grocers platform.
The project focuses on validating kit product management and delivery service business rules, ensuring correct backend behavior through structured testing and bug reporting.

Recruiters will find clear evidence of:

API validation skills

Negative testing mindset

Business rule analysis

Professional QA documentation

👩‍💻 Role

QA Tester

🧰 Tools & Technologies

🧪 Postman — API testing

🐞 Jira — Bug tracking

📄 Test Case Documentation — Structured tables

🔗 Tested Endpoints
POST /api/v1/kits/:id/products
POST /order-and-go/v1/delivery

🎯 Testing Objectives

✔ Validate correct product addition to existing kits

✔ Verify backend handling of invalid input data

✔ Check boundary values, data types, and negative values

✔ Compare expected vs actual API responses

✔ Report clear, reproducible bugs in Jira

🧪 Test Scope
🧺 Kit Product Management

Validated fields:

id

quantity

Test scenarios:

Existing and non-existing product IDs

Boundary values (29, 30, 31)

Negative, decimal, and invalid inputs

🚚 Delivery Service — Order and Go

Validated fields:

deliveryTime

productsCount

productsWeight

Test scenarios:

Valid and out-of-range values

Boundary, negative, and decimal inputs

Alphabetic and special characters
<img width="1464" height="667" alt="Captura de pantalla 2026-01-18 195212" src="https://github.com/user-attachments/assets/56f3ed9b-865a-499c-83ba-d0676853b620" />
<img width="1457" height="604" alt="Captura de pantalla 2026-01-18 210148" src="https://github.com/user-attachments/assets/3a03f42c-2460-4399-8012-0618ae156ef9" />
<img width="1457" height="622" alt="Captura de pantalla 2026-01-18 210220" src="https://github.com/user-attachments/assets/4a451e94-3820-4c65-baf4-d3e1d4678748" />

🧠 Testing Strategy (What Recruiters Care About)

🔹 Positive and negative test cases

🔹 Equivalence class partitioning

🔹 Boundary value analysis

🔹 Expected vs actual result comparison

🔹 Structured test documentation

🔹 Bug reporting with evidence

🐞 Reported Bugs (Examples)

❌ Non-existent product added to kit

❌ Negative IDs and quantities accepted

❌ Out-of-range values not validated

❌ Server error (500) when decimal values are sent

📊 Results & Impact

🚨 Identified critical backend validation issues

🧪 Designed and executed 40+ test cases

📈 Improved backend reliability and data validation

🧩 Provided clear input for bug prioritization

📘 Key QA Learnings

API testing and negative testing mindset

Business rule validation

Boundary value analysis

Professional bug reporting

Clear QA documentation

⭐ Why This Project Matters

This project demonstrates core QA skills expected from a Junior QA Tester, including:

Analytical thinking

API validation

Defect prevention

Clear communication with development teams
