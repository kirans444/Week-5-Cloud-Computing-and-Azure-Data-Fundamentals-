# ☁️ Enterprise Cloud Infrastructure & Azure Data Fundamentals

## 📌 Project Background & Context
**Role:** Associate Cloud Data Analyst (Bootcamp Architecture & Governance Project)  
**Environment:** Microsoft Azure Cloud Ecosystem  

**Context:**  
As data scales, understanding where information lives, how it is secured, and how it moves through cloud architecture is critical before any analysis can begin. As part of my Data Analyst Bootcamp, this project focused on hands-on cloud infrastructure deployment, database provisioning, and cost estimation within Microsoft Azure. I acted as an internal cloud data consultant to evaluate deployment strategies, provision relational cloud databases, and write optimized data extraction scripts to simulate modern, cloud-hosted corporate workflows.

---

## 📑 Infrastructure Solutions & Deployment Architecture

### 1. Cloud Service Model Evaluation (Case Study: DataCore Enterprises)
Evaluated organizational workflows to match business infrastructure needs against Azure service models, delivering technical recommendations to stakeholders:
*   **Infrastructure as a Service (IaaS):** Recommended for *DataCore Enterprises* utilizing **Azure Virtual Machines** and **Azure Storage**. This framework gave the client maximum control over their operating systems and database architecture while offloading physical hardware management.
*   **Platform as a Service (PaaS):** Scaled development efficiency by deploying **Azure SQL Database** and **Azure App Service**, enabling data teams to focus strictly on data modeling and application architecture rather than server maintenance.

### 2. Hybrid Deployment & Regulatory Compliance
Mapped cloud strategies to industry requirements, utilizing public, private, and hybrid environments. 
*   *Application Case:* For heavily regulated sectors like healthcare, a **Hybrid Cloud** blueprint was analyzed—restricting highly sensitive patient records to private cloud databases to comply with data residency laws, while deploying front-end appointment management systems to cost-effective public cloud instances.

---

## 💰 Cloud Financial Planning & Cost Metrics
Utilizing the **Azure Pricing Calculator**, I architected a cost blueprint for an Enterprise Business Intelligence infrastructure consisting of cloud-hosted relational databases, ETL data pipelines, and reporting instances.

### 📊 Modeled Operational Metrics:
*   **Estimated Monthly Operational Expenditure (OpEx):** £5,811.87
*   **Estimated Annual Operational Expenditure (OpEx):** £69,742.40
*   **Target SLA Availability Framework:** Provisioned architecture aligns with Azure's standard **99.99% availability SLA**, minimizing potential business downtime risks to less than 53 minutes annually.
*   **Infrastructure Maintenance Target:** Transitioning legacy workflows to Azure SQL (PaaS) drops local infrastructure administration overhead by **an estimated 30-40%**, freeing engineering resources for core development.

---

## 🗄️ Database Provisioning & Production-Scale SQL

I deployed and managed cloud-native structured storage engines within the Azure Portal environment, establishing live data connections for downstream analysis:
*   **Azure SQL Database:** Deployed managed relational resources leveraging built-in high availability, automated backup cycles, and native cloud security protocols.
*   **Azure Database for PostgreSQL:** Provisioned open-source, enterprise-grade scalable relational endpoints.

### 🔍 Programmatic Data Extraction & Customer Filtering
Applied relational querying logic within active Azure cloud environments to isolate target consumer records for cross-departmental stakeholders (e.g., Marketing, Customer Success).

```sql
-- Scenario: Automated Targeted Customer Segmentation for Regional Campaigns
SELECT 
    CustomerID,
    FirstName,
    LastName,
    EmailAddress
FROM 
    SalesLT.Customer
WHERE 
    FirstName LIKE 'A%'
    AND LastName LIKE '%A';
