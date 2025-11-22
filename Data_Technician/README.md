# 📚 # Azure Cloud & Data Governance Portfolio Summary ☁️🛡️✨

This README outlines the key concepts and strategic tasks covered in the Data Technician Workbook focusing on **Cloud Computing** ☁️, **Microsoft Azure Services** 💻, and **Data Governance** ⚖️. The content demonstrates theoretical knowledge and practical application for planning a modern, compliant cloud data environment.

* *Content based on Week 5 Workbook.*
* *Showcasing understanding of cloud architecture and regulations.*


***

## 🎯 Workbook Objectives

This workbook's tasks and labs are structured to build a foundational understanding of the environment and laws governing modern data roles. The key areas covered are:

* **Cloud Concepts:** Understanding cloud models (IaaS, PaaS, SaaS), deployment models (Public, Private, Hybrid), and real-world benefits.
* **Legal Compliance:** Deep dive into key UK data and cyber security legislation.
* **Database Fundamentals:** Practical experience with relational and non-relational data in Azure.
* **Data Architecture:** Designing basic data solutions in Azure Fabric (Optional Task).

***

## 🧩 Core Topics Covered (By Day)

### ☁️  Cloud Computing Fundamentals

This module focuses on the theoretical and business aspects of cloud services.

| Topic | Key Concepts Covered |
| :--- | :--- |
| **Cloud Computing** | Benefits (Reduce Cost, Agility, Reliability, Innovation), alternative (On-Premises). |
| **Cloud Providers** | Features of AWS, Microsoft Azure, and Google Cloud Platform (GCP). |
| **Service Models** | Explanations and use cases for **IaaS** (Infrastructure as a Service), **PaaS** (Platform as a Service), and **SaaS** (Software as a Service). |
| **Deployment Models**| Definitions and organizational examples of **Public Cloud**, **Private Cloud**, **Hybrid Cloud**, and **Community Cloud**. |
| **Pricing** | Use of a Pricing Calculator to estimate workload costs on Azure. |

---

### ⚖️  Data Laws and Cyber Security

This module explores the legal framework for handling data and operating in a technical environment.

| Legislation/Topic | Areas of Focus |
| :--- | :--- |
| **Computer Misuse Act 1990** | Deals with Hacking/Cracking (Unauthorized Access), Ulterior Intent Offence, and Cyber-Sabotage (Unauthorised Acts with Intent to Impair). |
| **Police and Justice Act 2006** | Added powers: Criminalising Denial of Service (DoS) attacks, Increased Penalties, and Criminalising the Making/Supplying of Hacking Tools. |
| **Data Protection** | Data an employer can and cannot store about an employee (e.g., Name, Address, Sex vs. Race, Religion, Political Opinions). |
| **Copyright & Piracy** | Examples of Copyright Infringement (Download movie/music without permission) and Plagiarism, plus consequences (Legal Penalties, Security Risks). |
| **Acts Mapping** | Matching clauses to key acts: Computer Misuse Act 1990, Police and Justice Act 2006, Copyright Acts, Health and Safety (DSE) Regulations 1992, Data Protection Act 2018, and Consumer Rights Act 2015. |

---

### 💻  Azure & Database Practice

This module includes practical, lab-based tasks focusing on data management in a cloud environment.

* **Lab 1 (DP-900):** Explore Relational Data in Azure.
* **Lab 2 (SQL):** SQL querying practice using the **AdventureWorks DB**. Queries include:
    * Filtering customers using `LIKE` (`A%`, `%a`, `%o%`).
    * Finding top products based on price and color.
    * Calculating aggregate statistics (`AVG`, `SUM`, `COUNT`) and margins.
    * Subqueries (Products priced above average).
    * Joining tables (Orders with Customer Information).
* **Lab 3 (DP-900):** Explore Non-relational Data in Azure.

---

### ☁️  Assessments & Architectural Scenario

This module contains final assessments and an optional task requiring solution architecture.

* **MS Fabric Lab:** Completion of Data Factory end-to-end tutorial.
* **DP-900 Practice:** Team-based practice assessment for the Microsoft Azure Data Fundamentals exam.
* **Optional Scenario: "Paws & Whiskers" Pet Shop**
    * **Data Laws:** Identify relevant laws (GDPR, DPA 2018).
    * **Azure Services:** Recommend storage (Blob, Azure SQL), analysis tools (Azure ML, Synapse Analytics), and integration (Azure Data Factory).
    * **Data Modelling:** Define data categories (demographics, transactions, inventory) and propose a relational/data warehouse approach.
    * **Storage & Security:** Discuss Parquet/JSON formats and Azure's built-in encryption.
    * **Additional Considerations:** Backup (Azure Backup), Visualization (Power BI), and Future Scalability.
***

 


## 1. Cloud Computing Fundamentals 💡⚙️

This section defines the core concepts and delivery models essential for understanding and utilizing cloud technology.

### Benefits of Cloud Computing 🚀📈

Cloud computing enables businesses and individuals to access powerful computing resources over the internet without needing physical infrastructure.

| Benefit | Description |
| :--- | :--- |
| **Cost Reduction** | 💰 Eliminates large upfront capital expenditures on hardware and infrastructure. |
| **Scalability** | ⏫ Allows resources (storage, compute) to be easily scaled up or down based on demand. |
| **Flexibility** | 🔄 Supports remote work, real-time services, and rapid deployment of applications. |

### Service Models 🧱🧩

Cloud services are categorized by the level of management provided by the vendor versus the user.

| Model | Description | Example | User Management Focus |
| :--- | :--- | :--- | :--- |
| **IaaS** | **Infrastructure as a Service**. Provides basic computing infrastructure (servers, storage, networks). | Azure Virtual Machines | ⚙️ OS, Apps, Data |
| **PaaS** | **Platform as a Service**. Provides hardware and operating systems, allowing developers to focus on application deployment. | Azure App Service | 💻 Apps, Data |
| **SaaS** | **Software as a Service**. Provides fully managed applications over the internet. | Microsoft 365, Gmail | 📧 User Access, Data |

***

## 2. ⚖️ Data Governance and Regulations 🔒

This section covers the legal and strategic measures necessary for secure and compliant data handling, particularly for data moving to the cloud.

### Key Data Laws 📜🌍

| Law | Focus | Key Requirement |
| :--- | :--- | :--- |
| **GDPR** | General Data Protection Regulation (EU/UK) | Requires **consent** ✅, **transparency** 📢, and the **right to be forgotten** 🗑️ when processing personal data. |
| **Data Protection Act 2018** (UK) | UK implementation of GDPR | Reinforces data protection principles and outlines obligations for data controllers and processors. |

### Data Strategy and Modelling 🗃️📊

* **Data Types and Modelling:** Determining whether data should be **structured** 🧱, **semi-structured** 📐, or **unstructured** 📦 to meet business needs.
* **Data Storage Formats:** Selecting appropriate formats for storing data in Azure (e.g., transactional data in relational databases 💾, unstructured files in Blob Storage 🔗).

***

## 3. ☁️ Azure Service Recommendations 🌟

Based on typical business requirements (transactional processing, large-scale analytics, and storage), the following Azure services are recommended:

| Azure Service | Purpose | Use Case |
| :--- | :--- | :--- |
| **Azure SQL Database** | Relational Database (PaaS) | Storing transactional data (sales 🛒, customer records 👤) that requires high reliability and structure. |
| **Azure Synapse Analytics** | Data Warehousing & Analytics | Running complex queries and advanced analytics on very large datasets (**Big Data** 🐳). |
| **Azure Data Lake Storage** | Massive Storage | Storing unstructured or semi-structured data (logs 📜, backups 🛡️, media 🎬) for long-term retention and processing. |

### Additional Considerations 💡

* **Backup and Disaster
