<p align="center">
  <img src="https://www.especial.gr/wp-content/uploads/2019/03/panepisthmio-dut-attikhs.png"
       alt="UNIWA"
       width="150"
       style="margin-bottom: 10px;" />
</p>

<p align="center" style="line-height: 1.5;">
  <strong style="font-size: 18px;">UNIVERSITY OF WEST ATTICA</strong><br>
  <span style="font-size: 14px;">SCHOOL OF ENGINEERING</span><br>
  <span style="font-size: 14px;">DEPARTMENT OF COMPUTER ENGINEERING AND INFORMATICS</span>
</p>

<hr style="width: 60%; margin: 20px auto;"/>

<p align="center" style="font-size: 16px; font-weight: 600;">
  Analysis and Design of Information Systems
</p>

<h1 align="center" style="letter-spacing: 1px; margin-top: 10px;">
  Real Estate Marketing Analysis and Design
</h1>

<p align="center" style="margin-top: 20px; line-height: 1.8;">
  <strong style="font-size: 16px;">Vasileios Evangelos Athanasiou</strong><br>

  <a href="https://github.com/Ath21" target="_blank"
     style="text-decoration: none; margin: 0 6px; padding: 6px 12px;
            border-radius: 6px; background-color: #24292e; color: #ffffff;
            font-size: 13px;">
    GitHub
  </a>

  <a href="https://www.linkedin.com/in/vasilis-athanasiou-7036b53a4/" target="_blank"
     style="text-decoration: none; margin: 0 6px; padding: 6px 12px;
            border-radius: 6px; background-color: #0a66c2; color: #ffffff;
            font-size: 13px;">
    LinkedIn
  </a>
  <br>

  <span style="font-size: 13px;">Student ID: 19390005</span>
</p>

<p align="center" style="margin-top: 16px; font-size: 14px;">
  <strong>Supervisor:</strong> Theodosios Pavlidis<br>
  <span style="font-size: 13px;">Special Technical Laboratory Staff</span><br>

  <a href="https://ice.uniwa.gr/emd_person/17586/" target="_blank"
     style="text-decoration: none; padding: 6px 14px;
            border-radius: 6px; border: 1px solid #555;
            color: #333; font-size: 13px; display: inline-block; margin-top: 6px;">
    UNIWA Profile
  </a>
</p>

<p align="center" style="margin-top: 20px; font-size: 13px; color: #555;">
  Athens, December 2022
</p>



## Overview

This repository contains a specialized study on **Real Estate Marketing Strategy**, developed for the course **“Analysis and Design of Information Systems”** at the **University of West Attica (UNIWA)**.

The project analyzes the systematic procedures involved in **real estate marketing**, utilizing structured modeling techniques to describe the professional interaction between the **Real Estate Agent** and the **Client**.

---

## Table of Contents

| Section | Folder | Description |
|------:|--------|-------------|
| 1 | `docs/` | Project documentation for the Real Estate Marketing system |
| 1.1 | `docs/Real-Estate-Marketing.pdf` | English documentation describing the real estate marketing process |
| 1.2 | `docs/Αγοραπωλησία-Ακινήτου.pdf` | Greek documentation of the real estate purchase/sale process |
| 2 | `diagrams/` | Exported diagrams illustrating business workflows |
| 2.1 | `diagrams/B2.png` – `B8.png` | Core process diagrams for real estate marketing |
| 2.2 | `diagrams/B9.A0.png` – `B9.A6.png` | Detailed subprocess diagrams of stage B9 |
| 2.3 | `diagrams/B10.png` | Final aggregated process diagram |
| 3 | `visio/` | Editable Microsoft Visio source diagrams |
| 3.1 | `visio/B2.vsdx` – `B8.vsdx` | Visio files for core marketing processes |
| 3.2 | `visio/B9.A0.vsdx` – `B9.A6.vsdx` | Visio files for detailed B9 subprocesses |
| 3.3 | `visio/B10.vsdx` | Final process model (Visio source) |
| 4 | `README.md` | Repository overview and project description |


---

## Methodologies Used

The documentation employs the following industry-standard system modeling techniques to provide a complete and structured view of the real estate marketing process:

- **B1 – Verbal Analysis**  
  A detailed, text-based description of the real estate marketing procedure, outlining all steps, actors, and decision points.

- **B2 – Use Case Analysis (UML Use Cases)**  
  UML-based use case diagrams illustrating system functionality from the initial client request to the completion and logging of the transaction.

- **B3 – Organizational Entities (OEs)**  
  Identification and analysis of organizational roles involved in the process, including:
  - Client  
  - Real Estate Agent  

- **B4 – Functional Decomposition**  
  Breakdown of the overall system functionality into smaller, manageable sub-functions to clarify responsibilities and system behavior.

- **B5 – Process Decomposition**  
  Decomposition of the real estate marketing workflow into sequential and interrelated processes, highlighting process flow and dependencies.

- **B6 – IDEF3 Workflow Diagram**  
  Modeling of the operational workflow, focusing on process sequencing and execution logic.

- **B7 – IDEF3 State Transition Diagram**  
  Representation of system state changes throughout the lifecycle of a real estate marketing request.

- **B8 – Data Flow Diagram (DFD)**  
  Visualization of how data is generated, processed, stored, and transferred within the system.

- **B9 – IDEF0 Diagram**  
  Functional modeling of the system, emphasizing:
  - Inputs (Client Identification, Property Information)  
  - Outputs  
  - Controls (Agency Policy, Legal Regulations)  
  - Mechanisms (Property Database, Real Estate Agent)

- **B10 – Entity Relationship (E–R) Model**  
  Conceptual data model defining entities, attributes, and relationships required to support the real estate marketing process.

---

## The Marketing Process

The core system is based on the interaction between two primary entities:

- **Client**
- **Real Estate Agent**

The workflow includes the following key steps:

1. **Client Request**  
   The process begins when a client requests professional real estate marketing services.

2. **Identity & Property Validation**  
   The agent verifies the client’s identity and confirms property ownership and details.

3. **Database Verification**  
   Existing records are checked to ensure consistency and eligibility.

4. **Policy Compliance**  
   The request is evaluated against agency standards and legal requirements.

5. **Finalization**  
   - If all checks succeed:  
     - The transaction is logged  
     - The marketing phase is initiated  
   - Otherwise:  
     - The request is rejected or returned for correction

---

## Installation Guide

Clone this repository to your local machine. 
```bash
git clone https://github.com/Analysis-of-Information-Systems/Real-Estate-Marketing.git
``` 
