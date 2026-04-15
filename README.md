# HR Job Market Analysis in Finland

Power BI dashboard analyzing HR job postings in Finland from **1 January to 1 April 2026**.

## Overview
This dashboard provides an overview of the HR job market in Finland, focusing on:
- number of open jobs
- HR branches
- seniority distribution
- language requirements
- required experience
- multi-function positions

## Key Metrics
- **Count of Open Jobs**
- **Count of HR Branches**
- **FIN as Main Language**
- **ENG as Additional Language**
- **Multi-function Positions %**
- **Average of Experience**
- **Experience Unspecified %**

## Notes
- “Several” years of experience is counted as **3 years**
- Unspecified experience is excluded from average experience
- Multi-function positions include non-HR tasks or tasks across multiple HR branches
- Language charts reflect stated language requirements only
- FIN = Finnish, SWE = Swedish, ENG = English

## Tools Used
- **Power BI**
- **Power Query**
- **DAX**

## Files
- `dashboard.pbix` — Power BI report file
- `images/` — dashboard screenshots
- `analysis.ipynb/` — skills analysis in python

## Purpose
This project was created to explore hiring trends in Finnish HR roles and present them in a clear, visual dashboard format.

The ipynb file consolidates all the key visualizations generated during the HR skill demand analysis. These plots illustrate the top skills across different HR branches, overall skill demands, and specific breakdowns for IT/AI/Tech skills and HR systems/tools.

- Data Source: Briefly mention the HR dataset used and its primary purpose.
- Skill Extraction: Explain how skills were extracted from the 'Requirements' column (e.g., using string splitting and lowercasing).
- Categorization: Describe how skills were categorized into HR branches, IT/AI/Tech, and HR Systems/Tools, including the keywords used for identification.
- Consolidation Logic: Detail the specific consolidation rules applied for HR Systems/Tools (e.g., combining 'hr systems expertise' into 'hr systems experience', 'advanced excel' into 'excel', and various Microsoft Office related terms into 'microsoft office skills').
- Visualization: Mention the types of visualizations used (bar charts) and what they represent (top skills, overall demands, etc.).
- Key Findings: Reiterate the main conclusions from the 'Conclusion' section of the notebook, highlighting the most in-demand skills, IT/AI/Tech trends, important HR systems, and key advantages.
