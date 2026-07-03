# Security and Risk Management e-Portfolio

**Student Name:** Sopheaktra CHEA[cite: 5]
**Student ID:** 12702030[cite: 5]
**Group:** 3[cite: 5]
**Module:** Security and Risk Management
**Date:** July 2026

Welcome to my learning and development e-Portfolio. This page collates the artefacts demonstrating my academic progress, details my individual contributions to group projects, and critically evaluates the evolution of our technical strategies over the duration of this module.

---

## 1. Artefacts Showcase

To demonstrate the application of knowledge and understanding, the following core artefacts highlight the progression of my work from initial risk identification to advanced disaster recovery engineering:

*   **Artefact 1: Risk Identification and Digitalisation Strategy Report (Unit 6)**
    *   **Description:** A comprehensive risk assessment for the client 'Pampered Pets' comparing physical operations with a proposed digital transformation[cite: 5]. This utilized the ISO-IEC 27005 framework for physical assets and the STRIDE methodology for cloud environments[cite: 5].
    *   **Evidence:** `[Insert Link to Risk Identification Report PDF Here]`
*   **Artefact 2: Network & Security Architecture Diagrams**
    *   **Description:** Technical schematics I designed to map the transformation from the highly vulnerable "Current Network Architecture" to the "Proposed High Availability (HA) & Secure Access Architecture"[cite: 5].
    *   **Evidence:** `[Insert Link to Diagram Images Here]`
*   **Artefact 3: Peer and Self-Evaluation Report**
    *   **Description:** A reflective document capturing team dynamics, peer feedback, and my self-evaluation of my role within Group 3[cite: 6].
    *   **Evidence:** `[Insert Link to Peer Evaluation PDF Here]`
*   **Artefact 4: Final Executive Summary & Quantitative Risk Model (Unit 11)**
    *   **Description:** The culmination of the module, featuring a mathematically driven Decision Tree risk model and the engineering of a sub-minute RTO/RPO Active-Active Disaster Recovery architecture.
    *   **Evidence:** `[Insert Link to Unit 11 Final Report PDF Here]`

---

## 2. Individual Contributions to Group Projects

During the module's collaborative phases, particularly within Group 3, I worked closely with my team member Sarah Khalid[cite: 5]. We established an effective workflow by dividing tasks based on our core strengths; Sarah managed the academic research, while I operated as the lead coordinator for the technical architecture and infrastructure planning[cite: 6].

My direct contributions included:

### A. Technical Security Architecture
*   I was responsible for designing the "Proposed High Availability (HA) & Secure Access Architecture"[cite: 5]. I engineered the public-facing application path by integrating a Cloud WAF, Elastic Load Balancers, and a Tokenized PCI-DSS Payment Gateway[cite: 5].
*   For internal security, I designed the access paths requiring hardware endpoint hardening, VLAN segmentation, and an MFA/RBAC authentication engine[cite: 5].

### B. Planning & Strategic Coordination
*   I structured the technical project timeline, developing an 8-month (32-week) Gantt chart that logically distributed a $50,000 budget across core perimeter defense, HA storefront deployment, and SIEM integration[cite: 5].
*   I formulated the "Hybrid Supply Chain" compromise strategy, balancing cost-reduction via international hardware suppliers while securing the premium brand identity by retaining local agricultural sources[cite: 5].

### C. Team Dynamics & Peer Evaluation
*   **Effectiveness:** Our team operated highly effectively due to clear role delegation[cite: 6]. Sarah's proactive communication and clear updates were vital in keeping the project on track and streamlining the final integration[cite: 6].
*   **Constructive Self-Reflection:** Reflecting on my contributions, I recognized that my greatest strength lies in designing technical security architectures[cite: 6]. Moving forward, my goal is to improve how I balance highly technical system designs with broader executive writing, ensuring that my final reports are shorter and easier to understand for non-technical stakeholders[cite: 6].

---

## 3. Evaluation of Final Project (Unit 11) vs. Initial Status Document (Unit 6)

Comparing our initial status document (Unit 6 Pampered Pets Report) with the final project output (Unit 11 Executive Summary) reveals a significant maturation in both risk methodology and architectural resilience.

*   **Risk Analysis Methodology:** In Unit 6, our approach was fundamentally qualitative. We utilized ISO 27005 and STRIDE to identify broad categorical risks (e.g., untrusted Wi-Fi gateways and aging hardware end-points)[cite: 5]. By Unit 11, we evolved to a highly rigorous **Quantitative Decision Tree Analysis**. This allowed us to calculate precise mathematical probabilities (e.g., an 8.5% risk of quality loss) and attach direct financial impact metrics, moving from subjective estimation to actionable executive intelligence.
*   **System Architecture & Disaster Recovery:** The Unit 6 proposal introduced baseline high availability, relying on basic Cloud WAFs and Load Balancers across twin zones[cite: 5]. However, this lacked a concrete Disaster Recovery Service Level Agreement. In Unit 11, the architecture was drastically upgraded to a true **Active-Active Multi-Region Cloud Architecture**. By leveraging Kubernetes containerisation (to prevent vendor lock-in) and synchronous data replication (~12ms latency), the final design guaranteed an aggressive sub-minute RTO and RPO, while strictly enforcing EU Data Sovereignty (GDPR) via geofencing.
