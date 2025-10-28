# 🧭 ISMS Scoping Document – ISO/IEC 27001:2022

## 📖 Overview
The **ISMS Scope** defines the **boundaries and applicability** of the Information Security Management System (ISMS) within an organization.  
Establishing a clear and well-defined scope is essential to ensure that the ISMS covers all relevant business processes, information assets, and technologies — while excluding areas that are not applicable.

---

## 🎯 Objective
To define **what parts of the organization** are covered under the ISMS, **what is included/excluded**, and **why**.  
This ensures that the ISMS remains focused, manageable, and aligned with organizational goals and compliance needs.

---

## 🧩 Clause Reference
**ISO/IEC 27001:2022 – Clause 4.3: Determining the Scope of the ISMS**

> “The organization shall determine the boundaries and applicability of the information security management system to establish its scope.”

---

## 🏢 Key Components of an ISMS Scope

### 1. Organizational Boundaries
- Identify **departments, business units, or subsidiaries** included in the ISMS.  
- Define **physical locations** (headquarters, branches, data centers, remote offices).

### 2. Information Assets
- Determine which **information assets, systems, and data** are covered.  
- Include both **on-premises** and **cloud-based** systems.

### 3. Activities and Processes
- Specify the **business processes** and **services** that fall under the ISMS.  
- Exclude processes not relevant to information security (with justification).

### 4. Technology and Infrastructure
- Include relevant **hardware, software, and networks** supporting in-scope processes.  
- Consider dependencies on **third-party services** and **cloud providers**.

### 5. Legal and Regulatory Requirements
- Identify applicable **laws, standards, and contractual obligations** influencing the ISMS.

### 6. Exclusions (if any)
- Clearly document exclusions and explain **why** they do not impact ISMS objectives or compliance.

---

## 🧱 Sample ISMS Scope Statement

> **Organization:** ABC Company Pvt. Ltd.  
> **Scope Statement:**  
> “The Information Security Management System (ISMS) of ABC Company Pvt. Ltd. covers the management, storage, and processing of customer and corporate data related to the design, development, deployment, and support of cloud-based software solutions.  
> The ISMS includes activities performed at the corporate office (Mumbai) and development center (Bangalore).  
> Third-party cloud hosting environments (Microsoft Azure and AWS) used for service delivery are included in the scope.  
> HR, marketing, and non-IT administrative functions are excluded as they do not process sensitive or customer-related data.”  

---

## 🗂️ Supporting Documents

| Document | Description | Owner |
|-----------|-------------|--------|
| **ISMS Scope Statement** | Defines the ISMS coverage and applicability | ISMS Manager |
| **Context Analysis Report** | Provides inputs from Clause 4.1 & 4.2 | Compliance Officer |
| **Asset Inventory Register** | Lists information assets within scope | IT Team |
| **Network Diagram** | Visualizes systems and boundaries | Infrastructure Lead |

---

## 🔍 Steps to Define the ISMS Scope

```mermaid
flowchart TD
    A[Identify Business Objectives] --> B[Review Context & Interested Parties]
    B --> C[Identify Information Assets & Processes]
    C --> D[Determine Boundaries & Exclusions]
    D --> E[Draft Scope Statement]
    E --> F[Review & Approve by Management]
    F --> G[Publish and Communicate Scope]
    
    style A fill:#e3fcef,stroke:#22863a
    style G fill:#e8e8e8,stroke:#555
