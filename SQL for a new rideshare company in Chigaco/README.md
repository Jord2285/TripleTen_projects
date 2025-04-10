# Zuber Ride-Sharing Market Analysis - SQL Project

---

**Project Status:** Completed 01/25
**Last Updated:** April 9, 2025

## Project Overview

This repository showcases my SQL skills through a capstone project completed for the TripleTen program. In a simulated role as an Analyst for Zuber, a hypothetical new ride-sharing company launching in Chicago, I analyzed a database containing historical taxi trip and weather data.

The primary goal was to leverage SQL to extract actionable insights about the competitive landscape and prepare data to investigate the impact of external factors (like weather) on ride characteristics, thereby informing Zuber's potential launch strategy.

## Key Objectives

* Perform Exploratory Data Analysis (EDA) using SQL to quantify competitor ride volumes and identify market leaders during specific periods.
* Compare the market activity of major taxi companies against the collective "Other" competitors.
* Isolate and prepare a specific dataset to facilitate the analysis of weather's impact ('Good' vs. 'Bad' conditions) on trip durations for the key Loop-to-O'Hare Airport route on Saturdays.
* Demonstrate proficiency in writing complex, efficient, and readable SQL queries for data extraction, transformation, and aggregation.

## Analysis Focus Areas

* Competitor Activity & Market Share Analysis (EDA)
* Data Preparation for Weather Impact Hypothesis Testing

## Tools & Technologies Utilized

* **Database Query Language:** SQL (Standard SQL syntax)
* **Key SQL Concepts Applied:**
    * Complex `JOIN` operations (including joining on timestamp data)
    * Aggregate Functions (`COUNT`, etc.)
    * Subqueries / Common Table Expressions (CTEs)
    * `CASE` Statements for conditional logic and data classification
    * Filtering (`WHERE` clause with `LIKE`, `BETWEEN`, `IN`)
    * `GROUP BY` and `ORDER BY` clauses
    * Date/Time Functions and manipulations

## Methodology

The project was executed entirely through SQL querying against a relational database schema:

1.  **EDA Querying:** Crafted SQL queries to aggregate trip counts (`COUNT`) grouped by taxi company (`cabs` table joined with `trips`) and filtered by specific date ranges and company name patterns. Compared dominant players vs. others.
2.  **Hypothesis Prep Querying:** Developed SQL queries to:
    * Identify relevant neighborhood IDs (`neighborhoods` table).
    * Classify hourly weather conditions (`weather_records`) using `CASE`.
    * Select specific trips (`trips` table) based on origin, destination, and day of the week.
    * Join the selected trips with the classified weather data based on timestamps, retrieving trip duration for further analysis.

## Key Queries & Insights Enabled

* Developed SQL scripts providing quantitative insights into competitor market share (e.g., identifying rides per company for specific dates).
* Successfully generated a structured dataset correlating ride duration with 'Good' vs. 'Bad' weather conditions for Saturday trips from the Loop to O'Hare, enabling subsequent hypothesis testing or statistical analysis.

## Project Deliverables

* **SQL Scripts:** https://1drv.ms/b/c/e19f4da4f3d3fb01/EQA0_Saqg0lGr4brnlZjYYQB2AKH7Q893J7Z20xU2n1GUA?e=3ZJ3rt
    *(Contains well-commented SQL queries for all EDA and hypothesis preparation tasks)*
* **Project Requirements:** https://github.com/Jord2285/TripleTen_projects/blob/main/SQL%20for%20a%20new%20rideshare%20company%20in%20Chigaco/Requirements.txt *(Details the original project specifications)*
    *(Note: Query results/output can be inferred by running the scripts against a compatible schema, or may be included as comments/documentation within the scripts if applicable)*
