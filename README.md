# Data Management Services for UK Healthcare Staffing Agency

## Overview

**Role:** Senior Software Engineer  
**Timeline:** 18/04/2022 - 31/03/2023  
**Objective:** Modernized data management and reporting systems for a healthcare staffing agency, addressing issues related to data sources, ETL processes, and system performance. Transitioned to a cloud-based data warehouse solution to enhance efficiency, scalability, and data accessibility.  
**Technologies:** SQL Server, MySQL, Data Warehouse/ETL, SSIS, Power BI, Azure DevOps, Azure SQL Database, Azure Synapse Analytics, Azure Data Lake Gen2

## Current Situation

### Issues Identified

1. **Fragmented Data Sources:** 
   - Data is scattered across multiple locations, making it challenging to manage and access.
   - The existing Delaware House system is outdated and has been maintained by various teams over the years.

2. **Lack of Documentation:**
   - The business logic is not well-documented, making it difficult to trace the actual logic and official documentation.
   - ETL flows are numerous and interdependent but lack comprehensive documentation.
   - Versioning of source code and logic is unclear, leading to confusion about the current state and historical changes.

3. **ETL Performance Problems:**
   - Salary calculation ETL processes are slow and prone to errors.
   - Issues with ETL processes lead to delays in generating salary results, requiring significant time for troubleshooting and resolution.

### Key Areas for Improvement

1. **Documentation and Version Control:**
   - Implement proper documentation for business logic.
   - Establish version control for both source code and ETL processes.
   - Document ETL dependencies to improve transparency and facilitate onboarding.

2. **Performance Optimization:**
   - Analyze and enhance the performance of ETL processes to reduce processing time and errors.

## Proposed Solution: Modern Cloud-Based Data Warehouse

### Objective

To transition from the existing on-premise system to a modern cloud-based data warehouse, leveraging Azure technologies to create a more efficient, scalable, and maintainable solution.

### Solution Approach

1. **Data Warehouse Migration:**
   - **Technology Stack:** Azure Synapse Analytics, Azure Data Factory, Azure SQL Database, Azure Data Lake Gen2.
   - **Migration Strategy:** 
     - Assess current data sources and ETL flows.
     - Design and implement a cloud-based data warehouse using Azure Synapse Analytics and Azure Data Lake Gen2.
     - Migrate data and ETL processes to the new system.

2. **Documentation and Version Control:**
   - **Business Logic Documentation:**
     - Develop comprehensive documentation for business logic.
     - Create and maintain official documentation accessible to all team members.
   - **Version Control Implementation:**
     - Integrate version control systems for source code and ETL processes using Azure DevOps.
     - Ensure that all changes are tracked and documented.

3. **ETL Process Improvement:**
   - **Performance Enhancement:**
     - Review and optimize existing ETL processes.
     - Implement Azure Data Factory for improved ETL performance and management.
   - **Error Handling and Monitoring:**
     - Set up monitoring and alerting mechanisms to detect and address issues proactively.

4. **Documentation for ETL Dependencies:**
   - **Dependency Mapping:**
     - Create detailed documentation for ETL dependencies and interconnections.
     - Develop a clear overview of main servers and their roles in ETL flows.
   - **Onboarding and Knowledge Transfer:**
     - Ensure new and existing team members have access to up-to-date documentation.
     - Provide training and resources for effective knowledge transfer.

### Expected Benefits

- **Improved Data Management:** Centralized and modernized data infrastructure enhances data accessibility and management.
- **Enhanced Performance:** Faster ETL processes and improved performance for critical operations like salary calculations.
- **Better Documentation:** Comprehensive documentation and version control ensure transparency and ease of maintenance.
- **Scalability and Flexibility:** Cloud-based solution provides scalability and flexibility to adapt to future needs and technologies.

---

This document outlines the current challenges and the proposed approach to building a modern, cloud-based data warehouse, ensuring a more efficient and maintainable system for the healthcare staffing agency.
