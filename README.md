<p align="center">
  <img src="https://www.especial.gr/wp-content/uploads/2019/03/panepisthmio-dut-attikhs.png" alt="UNIWA" width="150"/>
</p>

<p align="center">
  <strong>UNIVERSITY OF WEST ATTICA</strong><br>
  SCHOOL OF ENGINEERING<br>
  DEPARTMENT OF COMPUTER ENGINEERING AND INFORMATICS
</p>

<p align="center">
  <a href="https://www.uniwa.gr" target="_blank">University of West Attica</a> ·
  <a href="https://ice.uniwa.gr" target="_blank">Department of Computer Engineering and Informatics</a>
</p>

---

<p align="center">
  <strong>Analysis and Design of Information Systems</strong>
</p>

<h1 align="center">
  Real Estate Marketing Analysis and Design
</h1>

<p align="center">
  <strong>Vasileios Evangelos Athanasiou</strong><br>
  Student ID: 19390005
</p>

<p align="center">
  <a href="https://github.com/Ath21" target="_blank">GitHub</a> ·
  <a href="https://www.linkedin.com/in/vasilis-athanasiou-7036b53a4/" target="_blank">LinkedIn</a>
</p>

<hr/>

<p align="center">
  <strong>Supervision</strong>
</p>

<p align="center">
  Supervisor: Georgios Miaoulis, Professor<br>
</p>

<p align="center">
  <a href="https://ice.uniwa.gr/emd_person/17375/" target="_blank">UNIWA Profile</a> ·
  <a href="https://www.linkedin.com/in/georgiosmiaoulis/" target="_blank">LinkedIn</a>
</p>

<p align="center">
  Supervisor: Georgios Bardis, Assistant Professor
</p>
<p align="center">
  <a href="https://ice.uniwa.gr/en/emd_person/georgios-bardis/" target="_blank">UNIWA Profile</a>
</p>

<p align="center">
  Supervisor: Alexandros Bousdekis, Senior Researcher<br>
</p>

<p align="center">
  <a href="https://imu.ntua.gr/wp/person/albous/" target="_blank">Academic Profile</a> ·
  <a href="https://gr.linkedin.com/in/alexandros-bousdekis-17624487" target="_blank">LinkedIn</a>
</p>

<p align="center">
  Supervisor: Georgia Theodoropoulou, Postdoctoral Researcher<br>
</p>

<p align="center">
  <a href="https://www.researchgate.net/profile/Georgia-Theodoropoulou-4" target="_blank">UNIWA Profile</a>
</p>

<p align="center">
  Co-supervisor: Theodosios Pavlidis, Special Technical Laboratory Staff<br>
</p>

<p align="center">
  <a href="https://ice.uniwa.gr/emd_person/17586/" target="_blank">UNIWA Profile</a>
</p>

</hr>

---

<p align="center">
  Athens, January 2023
</p>

---

<p align="center">
  <img src="https://www.gimagency.gr/wp-content/uploads/2023/04/real-estate-marketing.jpg" width="250"/>
</p>

---

# README

## Real Estate Marketing Analysis and Design

This repository contains a specialized study on **Real Estate Marketing Strategy**, developed for the course **“Analysis and Design of Information Systems”** at the **University of West Attica (UNIWA)**.

The project analyzes the systematic procedures involved in **real estate marketing**, utilizing structured modeling techniques to describe the professional interaction between the **Real Estate Agent** and the **Client**.

---

## Table of Contents

| Section | Folder                             | Description                                                        |
| ------: | ---------------------------------- | ------------------------------------------------------------------ |
|       1 | `docs/`                            | Project documentation for the Real Estate Marketing system         |
|     1.1 | `docs/Real-Estate-Marketing.pdf`   | English documentation describing the real estate marketing process |
|     1.2 | `docs/Αγοραπωλησία-Ακινήτου.pdf`   | Greek documentation of the real estate purchase/sale process       |
|       2 | `diagrams/`                        | Exported diagrams illustrating business workflows                  |
|     2.1 | `diagrams/B2.png` – `B8.png`       | Core process diagrams for real estate marketing                    |
|     2.2 | `diagrams/B9.A0.png` – `B9.A6.png` | Detailed subprocess diagrams of stage B9                           |
|     2.3 | `diagrams/B10.png`                 | Final aggregated process diagram                                   |
|       3 | `visio/`                           | Editable Microsoft Visio source diagrams                           |
|     3.1 | `visio/B2.vsdx` – `B8.vsdx`        | Visio files for core marketing processes                           |
|     3.2 | `visio/B9.A0.vsdx` – `B9.A6.vsdx`  | Visio files for detailed B9 subprocesses                           |
|     3.3 | `visio/B10.vsdx`                   | Final process model (Visio source)                                 |
|       4 | `README.md`                        | Repository overview and project description                        |
|       5 | `INSTALL.md`                       | Usage instructions                                                 |

---

## 1. Methodologies Used

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

## 2. The Marketing Process

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
