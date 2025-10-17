# Dremio Learning Path Guidelines

## Introduction
This document provides a structured learning journey for anyone adopting Dremio — from newcomers to advanced users optimizing large-scale analytics.  
It is built around Dremio University courses, official documentation, and open-source GitHub resources.  
The purpose is to help every learner — analyst, engineer, developer, product owner, or administrator — grow their Dremio expertise step by step, through both theoretical understanding and hands-on practice with real datasets.

---

## User Personas

### Data Analyst
**Goal:** Explore data, build dashboards, and write performant SQL queries.  
**Focus Areas:**
- Navigating Dremio’s user interface  
- Creating and querying Virtual Datasets (VDS)  
- Using reflections to improve dashboard speed  
- Understanding dataset lineage and semantic structure  
**Key Courses:**  
- [Dremio Fundamentals (Software)](https://university.dremio.com/course/dremio-fundamentals-software)  
- [SQL Fundamentals for Data Analysts](https://university.dremio.com/course/sql-data-analysts)

---

### Data Engineer
**Goal:** Connect, transform, and optimize data sources.  
**Focus Areas:**
- Setting up and managing data sources (Oracle, S3, etc.)  
- Understanding query pushdown and tuning performance  
- Designing and managing reflections  
- Integrating Apache Iceberg  
**Key Courses:**  
- [Dremio Fundamentals (Software)](https://university.dremio.com/course/dremio-fundamentals-software)  
- [Data Reflection Fundamentals](https://university.dremio.com/course/reflection-fundamentals)

---

### Developer / Application Integrator
**Goal:** Build applications that leverage Dremio as a backend.  
**Focus Areas:**
- Using REST / JDBC / ODBC APIs  
- Embedding Dremio SQL in application code  
- Automating metadata and lineage retrieval  
- Integrating with dashboards or pipelines  
**Key Courses / Resources:**  
- [Dremio Fundamentals (Software)](https://university.dremio.com/course/dremio-fundamentals-software)  
- [Dremio REST API Reference](https://docs.dremio.com/current/reference/api/)  
- Blog: [Automating Dremio dbt Models with GitHub Actions](https://www.dremio.com/blog/automating-dremio-dbt-with-github-actions/)  
- GitHub Repositories:  
  - [dremio/dremio-oss](https://github.com/dremio/dremio-oss) — open-source core engine  
  - [dremio/dremio-cloud-tools](https://github.com/dremio/dremio-cloud-tools) — scripts and utilities for deployment  
  - [developer-advocacy-dremio/quick-guides-from-dremio](https://github.com/developer-advocacy-dremio/quick-guides-from-dremio) — quick guides and examples

---

### Data Product Owner / Architect
**Goal:** Govern, document, and standardize datasets as reusable products.  
**Focus Areas:**
- Organizing the catalog and naming conventions  
- Managing privileges and governance  
- Documenting dataset ownership and usage  
- Building a semantic layer for discovery  
**Key Courses:**  
- [Data Product Fundamentals](https://university.dremio.com/course/data-product-fundamentals)

---

### Platform Administrator
**Goal:** Manage users, permissions, and overall Dremio performance.  
**Focus Areas:**
- Environment setup and maintenance  
- Role-based access control  
- Resource queues and workload management  
- System monitoring, logs, and tuning  
**Key Courses:**  
- [Dremio Fundamentals (Software)](https://university.dremio.com/course/dremio-fundamentals-software)  
- Advanced administration materials in official docs

---

## Recommended Learning Path

| Stage | Focus | Recommended Content | Key Outcomes |
|-------|--------|---------------------|---------------|
| 1. Orientation | Understand Dremio’s architecture and purpose | [Dremio Fundamentals (Software)](https://university.dremio.com/course/dremio-fundamentals-software), [Dremio 101 Deep Dive](https://www.dremio.com/lakehouse-deep-dives/dremio-101/) | Learn how Dremio fits in a data ecosystem |
| 2. Querying & Exploration | Build Virtual Datasets, query, and explore | Fundamentals + [Getting Started Tutorials](https://docs.dremio.com/tutorials/) | Confident SQL use and data exploration |
| 3. Performance Optimization | Reflections, pushdown, job profiling | [Data Reflection Fundamentals](https://university.dremio.com/course/reflection-fundamentals), [Reflections Best Practices](https://docs.dremio.com/current/sonar/reflections/best-practices/) | Diagnose and tune slow queries |
| 4. Governance & Data Products | Structure and document datasets | [Data Product Fundamentals](https://university.dremio.com/course/data-product-fundamentals), [Semantic Layer Docs](https://docs.dremio.com/current/help-support/best-practices/) | Apply consistent naming and ownership |
| 5. Advanced Engineering / Integration | APIs, Iceberg, automation | [Apache Iceberg Course](https://university.dremio.com/course/apache-iceberg), [Dremio REST API Reference](https://docs.dremio.com/current/reference/api/) | Integrate Dremio with applications and pipelines |
| 6. Certification & Validation | Earn credentials | [Dremio University Credentials](https://university.dremio.com/credentials) | Demonstrate verified skills |

---

## Usage Guidelines

- Combine theory and practice: perform live exercises after each module.  
- Work with real datasets to reinforce learning.  
- Always inspect **Job Profiles** to see what is pushed down vs processed internally.  
- Encourage peer reviews for queries, reflections, and dataset organization.  
- Use badges and credentials as progress milestones.  
- Maintain a shared “Dremio Playbook” of tips, reflection designs, and performance tricks.  
- Refer to open-source repositories for automation and deployment ideas.

---

## References

- [Dremio REST API Reference](https://docs.dremio.com/current/reference/api/)  
- [Official Dremio Documentation Portal](https://docs.dremio.com/current/)  
