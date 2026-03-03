# Excel_Deloitte_Forensic Technology Project

## **Project Summary**

This project simulates a **Deloitte Excel-based forensic analytics project** classifying **gender pay equality data** to generate actionable business insights within an organization.
Daikibo Industrials received internal complaints regarding possible salary inequality. The Forensic Technology team generated an **Equality Score algorithm** to measure compensation fairness across factories and job roles.

## **Business Objective**

Help leadership identify potential discrimination risks by converting raw equality scores into clear investigation categories.
My role was to transform analytical output into actionable business intelligence using Excel-based classification logic.

## Dataset Description

The dataset includes:

1.**Factory** — Operational location
2.**Job Role** — Employee designation
3.**Equality Score** — Range from -100 to +100
      0 = Perfect equality
      Higher deviation = Higher inequality risk

## Methodology

### Data Understanding

1.Reviewed compensation equality scoring model
2.Validated dataset structure
3.Checked score distribution

### Classification Logic

Added a new column:

**Equality Class**

**Score Range**	              **Classification**

1.-10 to +10	                 Fair
2.-20 to -10 / 10 to 20	           Unfair
3.< -20 or > 20	                 Highly Discriminative

### Excel Automation

Used logical functions to automate classification:

=IF(ABS(C2)<=10,"Fair",IF(ABS(C2)<=20,"Unfair","Highly Discriminative"))

## KPI’s

1.Converted numerical analytics into decision-ready categories
2.Enabled rapid identification of high-risk departments
3.Improved interpretability for HR and compliance teams
4.Demonstrated forensic analytics workflow

## Skills Demonstrated

1.Forensic Data Analysis
2.Business Analytics
3.Excel Automation
4.Data Classification
5.Problem Solving
6.Analytical Thinking
7.Governance & Compliance Awareness

## Tools & Technologies

1.Microsoft Excel
2.Data Classification Logic
3.Forensic Analytics Approach

## Business Impact

This analysis supports:

1.Ethical compensation review
2.Risk-based investigation prioritization
3.Data-driven HR decision-making
