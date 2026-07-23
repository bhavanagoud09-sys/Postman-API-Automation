# Postman API Automation Framework

![Postman](https://img.shields.io/badge/Postman-API%20Testing-orange)
![Newman](https://img.shields.io/badge/Newman-Automation-blue)
![JavaScript](https://img.shields.io/badge/Language-JavaScript-yellow)
![GitHub](https://img.shields.io/badge/GitHub-Repository-black)
![License](https://img.shields.io/badge/License-MIT-green)

A production-style REST API Automation Framework built using **Postman**, **JavaScript**, and **Newman**.

This project demonstrates Functional API Testing and API Automation by validating CRUD operations on an E-Commerce REST API using JavaScript assertions, Environment Variables, API Chaining, and HTML Reporting.

---

# Table of Contents

- Project Overview
- Features
- Technology Stack
- Project Structure
- API Test Scenarios
- Installation
- Run Tests
- HTML Report
- Framework Design
- Folder Description
- Future Enhancements
- Author
- License

---

# Project Overview

The objective of this project is to automate REST API testing for an E-Commerce application using Postman.

The framework validates:

- GET APIs
- POST APIs
- PUT APIs
- DELETE APIs

using JavaScript test scripts, Environment Variables, API Chaining, Newman CLI, and HTML Reports.

---

# Features

- Functional API Testing
- REST API Automation
- CRUD Operations
- JavaScript Assertions
- Environment Variables
- API Chaining
- Newman CLI Execution
- HTML Report Generation
- GitHub Ready Project Structure

---

# Technology Stack

| Tool | Purpose |
|------|---------|
| Postman | API Testing |
| Newman | CLI Execution |
| JavaScript | Assertions |
| DummyJSON | Test API |
| Git | Version Control |
| GitHub | Repository Hosting |

---

# Project Structure

```
Postman-API-Automation
│
├── Collections
├── Environment
├── Reports
├── TestData
├── README.md
├── package.json
└── .gitignore
```

---

# API Test Scenarios

## GET

- Get All Products
- Get Product by ID

## POST

- Create Product

## PUT

- Update Product

## DELETE

- Delete Product

---

# Validations Performed

- Status Code Validation
- Response Time Validation
- JSON Schema Validation
- Response Body Validation
- Environment Variable Validation
- API Chaining Validation

---

# Installation

Clone the repository

```bash
git clone https://github.com/YOUR_GITHUB_USERNAME/Postman-API-Automation.git
```

Install Newman

```bash
npm install
```

---

# Run Tests

Execute collection

```bash
npm test
```

Generate HTML Report

```bash
npm run report
```

---

# HTML Report

The framework generates an HTML execution report after every Newman run.

The report contains:

- Total Requests
- Total Assertions
- Passed Tests
- Failed Tests
- Response Time
- Execution Summary

---

# Framework Design

```
Postman Collection
        │
        ▼
Environment Variables
        │
        ▼
JavaScript Assertions
        │
        ▼
Newman Execution
        │
        ▼
HTML Report
```

---

# Folder Description

| Folder | Description |
|---------|-------------|
| Collections | Postman Collection |
| Environment | Environment Variables |
| Reports | Newman HTML Reports |
| TestData | Test Data Files |

---

# Future Enhancements

- Data Driven Testing
- JSON Schema Validation
- CI/CD using GitHub Actions
- Jenkins Integration
- API Monitoring
- Docker Execution

---

# Author

**Bhavana G**

QA Analyst with 4 years of experience in Manual Testing of Oracle Retail applications including Oracle Retail Merchandising Foundation Cloud Service (MFCS), Oracle Retail Order Broker (OB), Oracle Retail Order Management System (OMS), Salesforce Commerce Cloud (SFCC), and Oracle Retail Sales Audit (ReSA).

This repository showcases my hands-on learning and project work in REST API Automation using Postman, JavaScript, and Newman.

Currently transitioning into QA Automation with hands-on experience in Playwright Automation and API Testing.

### GitHub

https://github.com/bhavanagoud09-sys

---

# License

This project is licensed under the MIT License.
