# Excel_Deloitte_Forensic Technology Project

## **Project Summary**

This project simulates a **Deloitte Excel-based forensic analytics project** classifying **gender pay equality data** to generate actionable business insights within an organization.
Daikibo Industrials received internal complaints regarding possible salary inequality. The Forensic Technology team generated an **Equality Score algorithm** to measure compensation fairness across factories and job roles.

## **Business Objective**

Help leadership identify potential discrimination risks by converting raw equality scores into clear investigation categories.
My role was to transform analytical output into actionable business intelligence using Excel-based classification logic.

## Dataset Description

The dataset includes:
•	**Factory** — Operational location
•	**Job Role** — Employee designation
•	**Equality Score** — Range from -100 to +100
      0 = Perfect equality
      Higher deviation = Higher inequality risk

## Methodology

### Data Understanding
•	Reviewed compensation equality scoring model
•	Validated dataset structure
•	Checked score distribution

### Classification Logic
Added a new column:
**Equality Class**
**Score Range**	              **Classification**
-10 to +10	                       Fair
-20 to -10 / 10 to 20	             Unfair
< -20 or > 20	                     Highly Discriminative

### Excel Automation
Used logical functions to automate classification:
=IF(ABS(C2)<=10,"Fair",IF(ABS(C2)<=20,"Unfair","Highly Discriminative"))

## KPI’s

Converted numerical analytics into decision-ready categories
Enabled rapid identification of high-risk departments
Improved interpretability for HR and compliance teams
Demonstrated forensic analytics workflow

## Skills Demonstrated
Forensic Data Analysis
Business Analytics
Excel Automation
Data Classification
Problem Solving
Analytical Thinking
Governance & Compliance Awareness

## Tools & Technologies
Microsoft Excel
Data Classification Logic
Forensic Analytics Approach

## Business Impact
This analysis supports:
Ethical compensation review
Risk-based investigation prioritization
Data-driven HR decision-making
