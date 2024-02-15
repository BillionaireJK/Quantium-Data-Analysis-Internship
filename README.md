# Quantium-Data-Analysis-Internship
# Dependencies
Language: Python 3.8 /
Packages: pandas, matplotlib, mlxtend, datetime, sklearn, scipy

# Project Overview and Task Insights 
This program involves analyzing chip purchases at supermarkets, aimed at evaluating customer purchasing behaviors and the performance of trial stores with a new layout.

 # Task 1: Data Preparation and Customer Analytics
- Data Cleaning: Modified date format to datetime, removed outliers and salsas.
- Customer Behavior Analysis: Explored purchase behaviors categorized by:
- LIFESTAGE: Identifies whether a customer has a family and their life stage.
- MEMBER_TYPE: Segmentation based on price point and product preferences.
- Segment Deep Dive: Focused on Mainstream Young Singles/Couples, analyzing chip brand and packet size preferences.

Insights:
- Top contributing segments to total sales: 1. Budget older families, 2. Mainstream young singles/couples, 3. Mainstream retirees.
- Older families show higher average packet purchases, while mainstream young singles/couples represent the largest population.
- Kettles chips and 175g packets are popular across most segments.
- Mainstream young singles/couples show significant preference for Tyrells chips (28% more likely) and 270g packets (32% more likely).

# Task 2: Experimentation and Uplift Testing
- Trial Stores: Stores 77, 86, and 88 had new layouts from Feb-Apr 2019.
- Metric Analysis: Evaluated total sales and number of customers using combined scores, comparing trial and control stores through Pearson correlations and magnitude distances.
- Hypothesis Testing: Determined significance of performance differences between control stores and the trial store.

Insights:
- Control and trial store pairs identified: 
  - 77 and 233
  - 86 and 155
  - 88 and 40
- Store 77 showed a statistically significant increase in total sales in Mar and Apr, while store 86 saw an increase in Mar.
- Both stores 77 and 86 experienced significant increases in number of customers in at least 2 months.
- No significant change observed in store 88's performance due to the trial.

# Task 3: Analytics and Commercial Application
- Created a PowerPoint report employing the Pyramid Principle to present key insights from Tasks 1 and 2.

This submission comprehensively addresses data preparation, customer analytics, experimentation, and commercial application, providing actionable insights for the client.
