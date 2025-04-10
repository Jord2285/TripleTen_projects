# Shopify App Market Analysis with Power BI

---

**Project Status:** Completed 03/2025
**Last Updated:** April 9, 2025

## Project Overview

This repository showcases a data analysis project utilizing Microsoft Power BI to explore the Shopify App marketplace ecosystem. Using publicly scraped data, this project simulates an analytical review aimed at understanding key characteristics of available apps, patterns in user reviews, and factors potentially correlating with app success, such as developer engagement.

The goal was to leverage Power BI's capabilities in data modeling, DAX calculations, and visualization to extract meaningful insights from the provided dataset.

## Key Objectives

* Characterize the overall Shopify app landscape by visualizing key metrics like app count, review volume trends over time, and the relationship between ratings and review counts.
* Analyze user reviews by developing custom DAX metrics to assess review impact ('helpful reviews') and quantify developer responsiveness ('developer answered').
* Investigate potential correlations between developer engagement (replying to reviews) and average app ratings.
* Compare developer performance based on aggregated review metrics and responsiveness, focusing specifically on apps with a significant number of reviews.
* Demonstrate proficiency in using Power BI Desktop for end-to-end analysis, from data modeling and DAX formula creation to building structured reports with diverse visualizations.

## Analysis Focus Areas

* Shopify App Landscape Characterization
* User Review Analysis (including Sentiment/Helpfulness Proxy)
* Developer Responsiveness & Performance Comparison

## Tools & Technologies Utilized

* **Primary Software:** Microsoft Power BI Desktop
* **Key Techniques Demonstrated:**
    * Data Modeling: Establishing and managing relationships between tables within Power BI.
    * DAX (Data Analysis Expressions): Writing calculated columns using functions like `IF`, `ISBLANK`, and arithmetic operations to create new metrics.
    * Data Visualization: Implementing various visual types (KPI Cards, Line Charts, Scatter Plots, Bar Charts, Text Boxes) appropriately.
    * Report Structuring: Organizing visualizations logically across multiple report pages.
    * Filtering: Applying visual-level filters to target specific data segments.

## Methodology

The analysis was conducted using Power BI Desktop, following these steps:

1.  **Data Connection & Modeling:** Imported the dataset from `shopify.xlsx` and created a many-to-one relationship between the `reviews` and `apps` tables based on the app identifier.
2.  **DAX Metric Creation:** Developed calculated columns in the `reviews` table using DAX to quantify `helpful_reviews` and `developer_answered` status.
3.  **Visualization & Report Building:** Created visualizations specified in the project requirements on three distinct report pages ("App Landscape", "Reviews", "App Reviews"), ensuring correct data representation and configuration (e.g., continuous axis for dates, appropriate aggregations). Applied visual-level filtering where required.
4.  **Interpretation:** Analyzed the generated visuals and added text annotations where necessary to explain findings (e.g., interpreting the rating vs. reviews scatter plot).

## Project Showcase & Deliverables

Due to the typical size and sharing limitations of Power BI `.pbix` files, the results of this project are presented via screenshots of the key visualizations within the structured report.

* **Project Visualization Screenshots:** Please view the screenshots capturing each required visual (Tasks 1.1 through 3.3) in the folder linked below.
    **https://1drv.ms/u/c/e19f4da4f3d3fb01/ESbV9flcbr1OgrwV95NyT5oBKIWJ0LjFK53CQp8hq-TcGg?e=PC8NZ6**

* **Detailed Project Requirements:** https://github.com/Jord2285/TripleTen_projects/blob/main/PowerBI%20Shopify%20developer%20apps%20and%20ratings%20analysis/Requirements.txt *(Provides context on the original project specifications and tasks)*

## Repository Navigation

Navigate to the `/screenshots` folder (link above) within this repository to view the final visualizations created for this project. Each screenshot corresponds to a specific analytical task outlined in the `PROJECT_REQUIREMENTS.md` file and demonstrates the final appearance of the Power BI report pages.

---
