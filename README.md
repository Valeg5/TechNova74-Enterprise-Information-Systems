# TechNova Consulting: Enterprise Information Systems Simulation

A comprehensive digital transformation and IT consulting enterprise simulation developed as a collaborative group project for the *Information Systems* curriculum in the Department of Applied Informatics at the **University of Macedonia** (Team 74).

The project simulates an emerging IT Consulting firm delivering modern enterprise solutions across seven foundational business technology verticals: Agile governance, corporate web architecture, business process modeling, customer relationship management (CRM), business intelligence (BI), predictive machine learning, and conversational AI.

---

## Core Enterprise Modules & Deliverables

### 1. Agile Project Management & Governance
* **Stack:** Atlassian Jira, Confluence, Google Drive.
* **Implementation:** Established a formal Team Collaboration Agreement and utilized Kanban boards with sprint roadmaps and Gantt timelines to manage deliverables. Comprehensive documentation and peer-review workflows were centralized in Confluence.

### 2. Corporate Identity & Web Presence
* **Stack:** WordPress (Twenty Seventeen Theme), Pantheon.io hosting, GTranslate, WPForms Lite, Generative AI (ChatGPT, DALL-E).
* **Implementation:** Designed the corporate branding, logo, and service portfolio inspired by Tier-1 consulting firms (Deloitte, Accenture, KPMG). Deployed a live corporate portal featuring multilingual support and interactive contact workflows.
* **Live Portal:** `https://dev-tech-nova-consulting.pantheonsite.io/`

### 3. Business Process Modeling & Queuing Simulation
* **Stack:** SAP Signavio Process Manager.
* **Implementation:** Modeled financial transaction and approval workflows. Executed 5-day simulations comparing standard demand (50 transactions) against high-demand stress testing (100 transactions).
* **Key Finding:** Identified severe operational bottlenecks under heavy loads where teller resource saturation (>95% shift utilization) led to an exponential cycle time increase from ~26 hours to ~341 hours, demonstrating queuing theory principles in practice.

### 4. CRM & Cloud Enterprise Platforms
* **Stack:** Salesforce Trailhead Platform.
* **Implementation:** Completed enterprise development modules covering Apex programming, Dynamic Forms, Lightning App Builder, Reports & Dashboards, and custom Aura Components (1,600 Trailhead points achieved).

### 5. Business Intelligence & Data Storytelling
* **Stack:** Tableau Public.
* **Implementation:** Engineered interactive dashboards and multi-dimensional visual analyses:
  * **Global Wine Market:** Price trend timelines (1987–2017), country-level production heatmaps, and quality treemaps.
  * **IMDb Cinematic Financials:** Scatter plots and area charts evaluating budget vs. gross revenue correlation, demonstrating that production expenditure does not guarantee commercial success.
* **Dashboards:** [Tableau Public Profile / Dashboards](https://public.tableau.com/views/2025_17655792687180/Dashboard1)

### 6. Predictive Machine Learning (AutoML)
* **Stack:** Altair AI Studio (formerly RapidMiner).
* **Implementation:** Developed a Decision Tree classification model on the standard **Car Evaluation** dataset using 5-fold cross-validation.
* **Key Finding:** Feature selection experiments proved that safety rating (`safety`) forms the root decision factor. Removing redundant attributes (`number_of_doors`) eliminated noise, increasing overall classification accuracy to **93.58%**.

### 7. Conversational AI with RAG Architecture
* **Stack:** Botpress Cloud, Web Audio API, Knowledge Bases.
* **Implementation:** Deployed an automated customer-service AI agent leveraging Retrieval-Augmented Generation (RAG) indexed on the official Greek National Pet Registry portal (`pet.gov.gr`). Configured conversation state-machines to provide accurate answers and resolved conversation flow loops during rigorous testing.

---

## Project Team (Team 74)

* **Valentinos Goudas** (Student ID: ics23170)
* **Panagiotis Papakondylis**
* **Theodoros Tourpeslis**
* **Nikolaos Heliotis**
* **Nikolaos Christidis**

Department of Applied Informatics, University of Macedonia
