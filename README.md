# Security and Risk Management e-Portfolio

**Student Name:** Sopheaktra CHEA
**Student ID:** 12702030
**Group:** 3
**Module:** Security and Risk Management
**Date:** July 2026

Welcome to my e-Portfolio for Learning and Development. This page brings together the artefacts that illustrate my academic achievement, outlining my individual contributions to group projects and assessing our technical tactics throughout this module.

--- 

## 1. Artefacts Showcase

The following core artefacts explain how my work has progressed from the first assessment of risk, through to advanced disaster recovery engineering, to show the application of knowledge and understanding:

* **Artefact 1: Risk Identification and Digitalisation Strategy Report (Unit 6)**
    * **Description:** A detailed risk analysis for the client ‘Pampered Pets’ between physical operations and a projected digital transformation. This used the ISO-IEC 27005 framework for physical assets and the STRIDE approach for cloud environments.
    * **Evidence:** [[Risk Identification  Report-Group 3.pdf](https://github.com/cheasopheaktra/Security-Risk-Management-Portfolio/blob/9f622d165a4fedd82b2dc86c13cdefbeb873bb82/Risk%20Identification%20%20Report-Group%203.pdf)]

* **Artefact 2: Network & Security Architecture Diagrams** 
    * **Description:** Technical diagrams I created to illustrate the transition from the very insecure "Current Network Architecture" to the "Proposed HA & Secure Access Architecture".
    * **Evidence:**
        1. **Current Network Usage:** ![Current Network Usage](current%20network%20useage%20V.2.2.png)
        2. **Proposed HA Architecture:** ![Proposed HA Architecture](HA%20V.1.png)

* **Artefact 3: Peer and Self-Evaluation Report**
    * **Description:** An introspective piece on team dynamics, peer criticism and my own evaluation of my involvement in Group 3.
    * **Evidence:** [Sopheaktra_CHEA_12702030_Peer_Evaluation.pdf](https://github.com/cheasopheaktra/Security-Risk-Management-Portfolio/blob/main/Sopheaktra_CHEA_12702030_Peer_Evaluation.pdf)

* **Artefact 4: Final Executive Summary & Quantitative Risk Model (Unit 11)**
    * **Description:** The module culminates in a mathematically based Decision Tree risk model and the engineering of a sub-minute RTO/RPO Active-Active Disaster Recovery architecture.
    * **Evidence:** 
        1. **Project Timeline:** ![Project Timeline Gantt Chart](Project%20Timeline%20Gantt%20Chart.png)  
        2. **Full DR Strategy Report:** [Digitalisation Risk, Quantitative Modelling, and Disaster Recovery v.1.1.pdf](Digitalisation%20Risk%2C%20Quantitative%20Modelling%2C%20and%20Disaster%20Recovery%20v.1.1.pdf)

--- 

## 2. Contributions of Individuals to Group Projects

During the collaborative stages of the curriculum, I worked with my teammate Sarah Khalid in Group 3. The division of labor according to our core competencies resulted in a successful workflow. Sarah was in charge of the academic research and I was the main coordinator of the technological architecture and infrastructure planning.

My direct contributions:

### A. Technical Security Architecture
* I designed the "Proposed High Availability (HA) & Secure Access Architecture". 
* I architected the public-facing application path with Cloud WAF, Elastic Load Balancers and a Tokenized PCI-DSS Payment Gateway.
* For internal security, I designed the access channels needing hardware endpoint hardening, VLAN segmentation, and an MFA/RBAC authentication engine.

### B. Coordination of Planning & Strategy
* I created an 8-month (32 week) Gantt chart to properly allocate a $50,000 budget across core perimeter protection, HA storefront deployment and SIEM integration for the technical project timeline.
* I developed the “Hybrid Supply Chain” compromise strategy, balancing cost-reduction through overseas hardware suppliers while protecting the premium brand identity by retaining local agriculture sources.

### C. Team Dynamics and Peer Assessment
* **Validity:** Our team was very effective since we delegated the roles well. Sarah’s proactive communication and concise updates played an important role in keeping the project on track and expediting the final integration.
* **Constructive Self-reflection:** I realized, however, that my most significant ability was in creating technological security architectures. In the future, I want to strengthen my ability to mix highly technical system designs with broader executive writing, making sure my final reports are shorter and easier to digest for non-technical stakeholders.

--- 

## 3. Evaluation of the Final Project (Unit 11) vs Initial Status Document (Unit 6)

When we look back at our first document on status (Unit 6 Pampered Pets Report) and compare that with the end output of the project (Unit 11 Executive Summary) we can see a great maturing of risk technique and architectural resilience.

* **Methodology of Risk Analysis:** Our approach in Unit 6 was essentially qualitative. Using ISO 27005 and STRIDE, we identified general category risks (e.g. untrusted Wi-Fi gateways and aging hardware end-points). We progressed to a highly rigorous **Quantitative Decision Tree Analysis** by Unit 11. This gave us the ability to derive specific statistical probabilities (e.g. 8.5% probability of quality loss) and assign direct financial impact indicators, shifting away from subjective estimation to actionable executive knowledge.
* **System Architecture & Disaster Recovery:** The Unit 6 plan provided baseline high availability using simple Cloud WAFs and Load Balancers across dual zones. However, this was not backed up with a formal Disaster Recovery Service Level Agreement. In Unit 11, the architecture was dramatically improved to a real **Active-Active Multi-Region Cloud Architecture**. The final solution achieved an aggressive sub-minute RTO and RPO using Kubernetes containerisation (avoiding vendor lock-in) and synchronous data replication (~12ms latency), and strongly enforced EU Data Sovereignty (GDPR) via geofencing.
