<div align="center">

# Flask for Data Engineering 🚀

### A structured learning repository covering Flask, REST APIs, HTTP fundamentals, and API development concepts from a Data Engineering perspective.

<br>

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python)
![Flask](https://img.shields.io/badge/Flask-2.x-black?style=for-the-badge&logo=flask)
![REST API](https://img.shields.io/badge/REST-API-green?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Active-success?style=for-the-badge)
![Repository](https://img.shields.io/badge/Learning-Repository-orange?style=for-the-badge)

</div>

---

# 📌 About This Repository

This repository documents my journey of learning **Flask and REST API development from a Data Engineering perspective**.

Instead of only writing code, this repository focuses on:

- Understanding why APIs exist
- Building strong REST fundamentals
- Learning how applications communicate
- Understanding request-response architecture
- Designing APIs used in data engineering systems
- Preparing for Data Engineering interviews

---

# 🎯 Learning Outcomes

By completing this repository, I will be able to:

✅ Build REST APIs using Flask

✅ Handle JSON requests and responses

✅ Design API endpoints using REST principles

✅ Understand HTTP request-response lifecycle

✅ Use HTTP methods and status codes correctly

✅ Build data ingestion APIs

✅ Connect APIs with databases

✅ Build end-to-end Data Engineering projects

---

# 🏗️ System Architecture Overview

```text
Client Application
       |
       | HTTP Request
       v
+------------------+
|    Flask API     |
|------------------|
| Routing          |
| Validation       |
| Business Logic   |
| Response Handling|
+------------------+
       |
       |
       v
+------------------+
|    Database      |
|------------------|
| MySQL            |
| PostgreSQL       |
| Data Warehouse   |
+------------------+
       |
       v
Analytics / Dashboards
```

---

# 🔄 Request Lifecycle

```text
Client
   |
   | GET /employee/101
   |
   v

Flask Server
   |
   | Route Matching
   |
   v

Extract Parameters
   |
   v

Execute Function
   |
   v

Database / Business Logic
   |
   v

Dictionary Response
   |
   v

JSON Conversion
   |
   v

HTTP Status Code
   |
   v

Client
```

---

# 🧠 Key Concepts Covered

| Module | Topic | Status |
|--------|--------|---------|
| 01 | Why APIs Exist | ✅ |
| 02 | API vs REST API vs Flask | ✅ |
| 03 | Flask Application Object | ✅ |
| 04 | Routing and Decorators | ✅ |
| 05 | HTTP Methods | ✅ |
| 06 | Request Object | ✅ |
| 07 | Dynamic Routes | ✅ |
| 08 | JSON Responses | ✅ |
| 09 | HTTP Status Codes | ✅ |
| 10 | Database Integration | ⏳ |
| 11 | End-to-End Project | ⏳ |

---

# 📚 Repository Structure

```text
flask-for-data-engineering/

│
├── README.md
│
├── docs/
│   ├── 01_why_apis.md
│   ├── 02_api_vs_rest_vs_flask.md
│   ├── 03_flask_application_object.md
│   ├── 04_routing_and_decorators.md
│   ├── 05_http_methods.md
│   ├── 06_request_object.md
│   ├── 07_dynamic_routes.md
│   ├── 08_json_responses.md
│   └── 09_http_status_codes.md
│
├── diagrams/
│
├── examples/
│
├── interview_questions/
│
├── notes/
│
└── project/
```

---

# ⚙️ Technology Stack

| Category | Technologies |
|----------|--------------|
| Language | Python |
| Framework | Flask |
| API Style | REST API |
| Data Format | JSON |
| Database | MySQL |
| Future Integration | Pandas |
| Visualization | Power BI |
| Version Control | Git & GitHub |

---

# 🚀 Data Engineering Perspective

```text
Applications
      |
      v
Flask API
      |
      +------ Database
      |
      +------ Kafka
      |
      +------ Airflow
      |
      +------ Data Warehouse
      |
      v
Analytics & Dashboards
```

The goal of this repository is not merely to learn Flask syntax, but to understand how APIs are used inside real-world Data Engineering systems.

---

# 🧩 Concepts Mastered So Far

### Flask Application Object

```python
from flask import Flask

app = Flask(__name__)
```

---

### Route Example

```python
@app.route("/salary")
def salary():
    return "50000"
```

---

### Dynamic Route

```python
@app.route("/employee/<int:id>")
def employee(id):
    return {
        "id": id,
        "name": "Rahul",
        "salary": 50000
    }
```

---

### JSON Response

```python
return {
    "salary": 50000
}
```

---

### Status Code

```python
return {
    "message": "Employee Created"
}, 201
```

---

# 📈 Roadmap

```text
✅ API Fundamentals
✅ REST Principles
✅ Flask Basics
✅ Routing
✅ Request Object
✅ JSON Responses
✅ Status Codes
⬜ MySQL Integration
⬜ Pandas Integration
⬜ End-to-End Event Analytics Platform
⬜ Dockerization
⬜ Deployment
```

---

# 🎯 End Goal

Build an intermediate-level project:

### Real-Time Event Analytics Platform

```text
Application
      |
      v
Flask REST API
      |
      v
MySQL
      |
      v
Data Aggregation
      |
      v
Power BI Dashboard
```

Features:

- Event Ingestion APIs
- Analytics APIs
- Aggregated Metrics
- Revenue Tracking
- Active User Metrics
- Dashboard Reporting

---

# 📖 Why This Repository Exists

I believe understanding systems deeply is more valuable than memorizing syntax.

This repository is my attempt to:

**Learn → Document → Build → Explain → Ship**

while developing skills required for modern Data Engineering roles.

---

<div align="center">

### ⭐ If you find this repository useful, feel free to star it.

#### Built with curiosity and consistency 🚀

</div>
