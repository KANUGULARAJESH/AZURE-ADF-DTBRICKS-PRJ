# AZURE-ADF-DTBRICKS-PRJ
Comprehensive Azure Data Engineering project using real-world e-commerce datasets and modern cloud technologies. This repository contains all resources, code, scripts, and documentation for building an end-to-end data pipeline leveraging Azure Data Factory, Azure Data Lake Gen2, Databricks (PySpark), and Azure Synapse Analytics.

Enterprise Data Platform & Governance Layer
Core Responsibilities
Component	Responsibility
SSO / Identity Federation	Secure enterprise login using Google Workspace
User & Group Management	Automated provisioning through SCIM
Workspace Access Control	Environment-level access management
RBAC Authorization	Group-based role assignment
Unity Catalog Governance	Fine-grained data access control
Data Governance	Centralized catalog and schema security
Secure Storage Access	IAM role-based access to S3
Databricks Security & Governance Capabilities
SSO & Identity Federation
Trust established with Google Workspace
SAML 2.0 based authentication
No separate Databricks credentials
User & Group Provisioning
Automated user creation via SCIM
Group synchronization from Google Workspace
Automated lifecycle management
Access Control
Workspace-level permissions
Group-based RBAC model
Least privilege access
Unity Catalog Governance
Catalog-level permissions
Schema-level permissions
Table-level permissions
Centralized governance and auditing
Key Security Principles
Centralized enterprise authentication
Group-based access control
Fine-grained governance using Unity Catalog
No direct user access to storage
Automated onboarding/offboarding
Audit & compliance ready architecture
Key Benefits
Secure enterprise-grade platform
Centralized governance model
Simplified access management
Scalable multi-environment architecture
Reduced operational overhead
Strong compliance and audit support
