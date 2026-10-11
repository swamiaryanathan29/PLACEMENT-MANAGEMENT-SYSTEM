# 🎓 Placement Management System

[![Python 3.10+](https://img.shields.io/badge/python-3.10+-blue.svg)](https://www.python.org/downloads/)
[![Flask](https://img.shields.io/badge/flask-000000?logo=flask&logoColor=white)](https://flask.palletsprojects.com/)
[![SQL](https://img.shields.io/badge/database-SQL-003B57?logo=sqlite&logoColor=white)](https://en.wikipedia.org/wiki/SQL)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

> An enterprise campus recruitment and placement database management platform. Features relational schema design, role-based REST APIs with JWT authentication, and a custom lightweight DBMS engine with B+ Tree indexing.

**Advisor:** Prof. Yogesh Kumar Meena

---

### 📊 System Architecture & Project Modules

| Module | Core Functionality | Technologies |
|:---|:---|:---|
| 🗄️ **[Module-1: Relational Schema](./Module-1/)** | 9+ normalized relational tables, schema design & SQL production dumps | PostgreSQL / MySQL, Relational Algebra |
| 📐 **[Module-2: Architecture & ER](./Module-2/)** | End-to-end ER diagrams, 9 system UML sequence & dataflow diagrams | ER Modeling, UML, UI Mockups |
| 🔐 **[Module-3: Backend & APIs](./Module-3/)** | Flask REST APIs, JWT authentication, Role-Based Access Control (RBAC) & CIMS integration | Python, Flask, PyJWT, RESTful Services |
| ⚡ **[Module-4: Custom Storage Engine](./Module-4/)** | Custom lightweight DBMS featuring B+ Tree indexing (accelerating queries up to 160x over 10k records) | Python, Custom B+ Tree Data Structures, Buffer Management |

---

## ⚙️ Key Technical Highlights

1. **Normalized Database Architecture:**
   * Structured relational database spanning 9+ interconnected tables ensuring 3NF normalization, referential integrity, and cascading delete constraints.

2. **Secure RESTful Backend:**
   * Developed role-based endpoints (Student, Recruiter, Placement Cell Admin) protected by JSON Web Tokens (JWT).
   * Interfaced with campus CIMS database via read-only endpoints for verified credential validation.

3. **Custom B+ Tree Indexing Engine:**
   * Implemented disk-based B+ Tree data structures for internal table indexing.
   * Benchmarking demonstrated up to **160x faster retrieval speeds** compared to full-table sequential scans across 10,000+ candidate records.

---

## 📁 Repository Modules & Links

* 🗄️ **[`Module-1/`](./Module-1/)** — Production database schema, table definitions, and SQL scripts.
* 📐 **[`Module-2/`](./Module-2/)** — High-resolution ER models and complete UML workflow diagrams.
* 🔐 **[`Module-3/`](./Module-3/)** — Flask REST API microservices, authentication middleware, and CIMS connectors.
* ⚡ **[`Module-4/`](./Module-4/)** — Custom lightweight DBMS storage engine with B+ Tree index benchmark suites.
