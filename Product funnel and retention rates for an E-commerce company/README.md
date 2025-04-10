# E-commerce User Activity Analysis: Funnel & Cohort Retention

---

**Project Status:** Completed 02/2025
**Last Updated:** April 9, 2025

## Project Overview

This repository presents a business analytics project focused on extracting key performance metrics from raw e-commerce website user activity logs. Completed as part of the TripleTen curriculum, this project simulates the responsibilities of a Junior Analyst tasked with providing insights into user conversion and retention.

Using Google Sheets as the primary analysis tool, I transformed event-level data into actionable business intelligence, building a conversion funnel and performing monthly cohort analysis to understand customer behavior patterns over time.

## Key Objectives

* Analyze user journeys to construct a multi-stage conversion funnel (product view -> cart -> purchase) based on unique user activity.
* Calculate critical website conversion rates, both overall and between sequential steps.
* Implement data preparation techniques to structure user purchase data for monthly cohort analysis, identifying each user's acquisition month.
* Calculate and present month-over-month retention rates for different customer acquisition cohorts.
* Deliver findings within a professionally formatted, well-documented, and easy-to-understand spreadsheet report suitable for executive review.

## Analysis Focus Areas

* Website Conversion Funnel Performance
* Monthly Customer Retention (Cohort Analysis based on First Purchase)

## Tools & Technologies Utilized

* **Primary Software:** Google Sheets
* **Key Techniques & Functions:**
    * Advanced Pivot Table analysis (including unique counts)
    * Data Filtering and structuring
    * Complex Formulas: `VLOOKUP`, `TEXT`, `DATEDIF`, logical functions, rate calculations
    * Cohort Analysis methodology implementation in a spreadsheet environment
    * Data Visualization (within Google Sheets)
    * Spreadsheet Formatting & Documentation Best Practices (incl. Executive Summary, TOC)

## Methodology

The analysis was conducted end-to-end within Google Sheets, involving these key steps:

1.  **Funnel Construction:** Utilized Pivot Tables on the `raw_user_activity` data to count unique users at each stage (view, cart, purchase) and calculated relevant conversion rates.
2.  **Cohort Data Preparation:** Filtered for purchase events, determined each user's first purchase date using Pivot Tables and `VLOOKUP`, and then created necessary time-based columns (`event_month`, `first_purchase_month`, `cohort_age`) using `TEXT` and `DATEDIF`.
3.  **Retention Analysis:** Aggregated the prepared purchase data into monthly cohorts using Pivot Tables (unique user counts by cohort and age). Calculated retention rates in a separate structured table by comparing active users each month to the initial cohort size.
4.  **Reporting & Documentation:** Organized all findings, methodologies, and assumptions into a polished spreadsheet, including an Executive Summary and Table of Contents, ensuring clarity and readability.

## Key Metrics & Insights Enabled

* Quantified website performance by visualizing the user conversion funnel and calculating precise conversion rates between key stages.
* Revealed customer loyalty trends by calculating and presenting monthly retention rates for distinct user acquisition cohorts, highlighting how long customers remain active after their first purchase.

## Project Deliverables

* **Comprehensive Analysis Spreadsheet (Google Sheet):** https://1drv.ms/b/c/e19f4da4f3d3fb01/EQOicKpQ-2RDp4mIPgq6Z_MBsvYIIQ5ofbPmKa1ljR1BQQ?e=R7zbgx
    *(This sheet contains all data tabs, analysis tabs (funnel, cohort prep, retention), and documentation)*
* **Detailed Project Requirements:**(https://github.com/Jord2285/TripleTen_projects/blob/main/Product%20funnel%20and%20retention%20rates%20for%20an%20E-commerce%20company/Requirements.txt) *(Provides context on the original project specifications)*

## Repository Navigation

The core work product for this project is the **Google Sheet linked above**. It contains the raw data, all data preparation steps, the final analyses (conversion funnel, cohort retention rates), and comprehensive documentation within dedicated sheets.

---
