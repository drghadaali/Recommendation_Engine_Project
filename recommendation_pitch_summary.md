### To:
Amira Al-Fayed

### From:
Dr. Ghada Ali | Physician-Scientist

### Subject:
Q3 Budget Proposal: Upgrade to OmniStream Media's Content Recommendation Engine

---

### Opening Statement

Dear Amira,

Ahead of the Q3 budget review, I would like to propose upgrading OmniStream Media's primary content recommendation engine. This project will use historical viewing behavior to deliver more relevant content suggestions, improve the viewer experience, and support stronger audience engagement.

### Section 1: The Analogy

Think of how Netflix recommends content to its viewers. When someone repeatedly watches science-fiction movies, finishes them, and gives them high ratings, the platform learns from that historical data and identifies similar patterns across its content library. It then recommends titles that the viewer is more likely to enjoy. OmniStream can apply the same principle by analyzing users' preferred genres, viewing duration, and ratings. As new viewing activity arrives, recommendations can be updated to reflect changing interests. The goal is to make content discovery more relevant and improve viewer engagement.

### Section 2: The Workflow

1. **Business Understanding:** We align with stakeholders on the business goal of improving content discovery and engagement and define how project success will be measured.

2. **Data Collection:** We use SQL to gather historical viewing records, including user IDs, content IDs, genres, watch duration, and ratings.

3. **Data Preparation:** We check missing or duplicate records, standardize fields, and investigate unusual values or outliers to ensure data quality.

4. **Exploratory Data Analysis (EDA):** We perform EDA to identify viewing patterns, genre preferences, rating trends, and differences across users.

5. **Model Development:** We use Python to learn from these patterns and build a model that ranks content each viewer may enjoy.

6. **Evaluation:** We test the recommendations against historical records and agreed business measures to confirm that they are relevant and useful.

7. **Deployment and Monitoring:** We integrate the model into a repeatable pipeline that supplies recommendations to the product and monitor its performance as new viewing data arrives.

### Section 3: The Tools

Our project will use industry-standard tools that support each stage of the Data Science Process. SQL will collect and organize historical viewing records, while Python will support data preparation, EDA, model development, and evaluation. Excel will help review data summaries and communicate results clearly, while Tableau will provide visual dashboards to monitor recommendation performance and business KPIs. Please refer to the supplementary tool_stage_mapping.csv file for a detailed mapping of each tool to its corresponding workflow stages. This resource allocation ensures that every stage of the proposed workflow is supported by an appropriate tool.

Best regards,

Dr. Ghada Ali