# aero-museum

# Alberta Aerospace Museum - Data and Business Analysis ✈️🏛️

This repository contains a comprehensive suite of projects developed for the Alberta Aerospace Museum as part of the **BTM 211** (Management Information Systems) course at the University of Alberta. The suite demonstrates a full lifecycle approach to information system development, from initial data modeling and database implementation to project management and advanced business intelligence.

**Project Goal:** To design, implement, and analyze an information system solution for the Alberta Aerospace Museum to address their data management challenges and provide actionable insights.

## Project Components

This project suite is divided into four key components, each representing a crucial phase in information system development:

### 1. Data Modeling (DM)

* **Objective:** To conceptualize and design a robust and normalized database structure for the museum's operational data.
* **Description:** This component involved creating an Entity-Relationship Diagram (ERD) to visually represent the relationships between various entities (e.g., Employees, Exhibits, Visitors, Artifacts, Loans) within the museum's ecosystem. The design focused on achieving data integrity, minimizing redundancy, and ensuring scalability for future growth.
* **Tools Used:** `draw.io`
* **Key Deliverables:**
    * `data-model.drawio.png`: The final ERD illustrating the database schema.
    * `DM-problem-defn.pdf`: Data Modeling requirements document.

### 2. Database (DB)

* **Objective:** To implement the designed data model into a functional relational database and demonstrate data manipulation capabilities.
* **Description:** Based on the ERD, a SQLite database was created. This involved defining tables, setting up primary and foreign key constraints, and populating the database with sample data (from `AAM-data - Data.csv`). Advanced SQL queries were developed to retrieve, update, and analyze data efficiently.
* **Tools Used:** SQLite
* **Key Deliverables:**
    * `database.db`: The SQLite database file.
    * `DB.pdf`: Database assignment document, including SQL queries and outputs.
    * `AAM-data.xlsx - Data.csv`: Raw data used for database population.

### 3. Project Management (PM)

* **Objective:** To plan, organize, and document the entire information system project, adhering to professional project management methodologies.
* **Description:** This phase encompassed outlining project scope, objectives, deliverables, timelines, and resource allocation. A comprehensive project management document was created, detailing stakeholder analysis, risk assessment, and communication plans, ensuring a structured approach to project execution.
* **Tools Used:** Microsoft Word (for documentation)
* **Key Deliverables:**
    * `PM-req-doc.pdf`: The Project Management document, detailing the project plan and execution strategy.

### 4. Business Analytics (BA)

* **Objective:** To transform raw museum data into actionable insights through interactive visualizations and dashboards.
* **Description:** Leveraging the structured data from the implemented database, this component focused on creating compelling business intelligence dashboards using Tableau. Visualizations were designed to highlight key performance indicators (KPIs) related to visitor demographics, exhibit performance, employee metrics, and artifact loan trends, enabling data-driven decision-making for museum management.
* **Tools Used:** Tableau
* **Key Deliverables:**
    * `AAM-analysis.twbx`: The Tableau Packaged Workbook containing interactive dashboards and visualizations.
    * `BA-req-doc.pdf`: Business Analytics requirements and analysis document.

## How to Explore the Project

To view and interact with the project artifacts:

1.  **Clone this repository:**
     ```bash
    git clone [https://github.com/git-samia/aero-museum.git](https://github.com/git-samia/aero-museum.git)
    cd aero-museum
    ```

2.  **Data Modeling (ERD):**

    * Open `data-model.drawio.png` directly in your web browser or any image viewer.

3.  **Database (SQLite):**

    * Download and install a SQLite browser (e.g., [DB Browser for SQLite](https://sqlitebrowser.org/)).
    * Open `database.db` with the SQLite browser to explore the schema and data.
    * Review `DB.pdf` for the SQL queries and their results.

4.  **Project Management:**

    * Open `PM-req-doc.pdf` with any PDF viewer to review the project plan.

5.  **Business Analytics (Tableau):**

    * Download and install [Tableau Public](https://public.tableau.com/en-us/s/) or [Tableau Reader](https://www.tableau.com/products/reader).
    * Open `AAM-analysis.twbx` with Tableau Public/Reader to interact with the dashboards.
    * Review `BA-req-doc.pdf` for the analysis and requirements.

## Skills Demonstrated

* **Data Modeling & Database Design:** Entity-Relationship Diagrams (ERDs), Normalization, Schema Design.
* **Database Management:** SQLite, SQL (DDL, DML, DQL), Database Population.
* **Project Management:** Requirements Gathering, Project Planning, Documentation, Stakeholder Analysis.
* **Business Intelligence & Data Visualization:** Tableau Desktop, Interactive Dashboard Creation, Data Storytelling, KPI Analysis.
* **Data Analysis:** Transforming raw data into actionable insights.
* **Documentation:** Creating clear and comprehensive project documentation.

## Repository Structure
```
.
├── AAM-analysis.twbx
├── AAM-data.xlsx
├── BA-req-doc.pdf
├── DB.pdf
├── DM-problem-defn.pdf
├── PM-req-doc.pdf
├── README.md
├── data-model.drawio.png
└── database.db
```

## License
No specific license defined.
