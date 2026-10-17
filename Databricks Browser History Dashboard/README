### Browser History Dashboard

# Description
Browser History Dashboard – an interactive report designed to analyze personal web browsing habits: which pages are visited most often, when, and how this changes over time. Built end-to-end in Databricks, it covers the full path from a raw CSV export to a published AI/BI dashboard. The report presents my own Chrome browsing history from July 18 to October 15, 2026.

# Tech Stack
 Databricks Free Edition – main platform for the project

 Unity Catalog Volumes – storage for the raw CSV file

 PySpark – data cleaning and sessionization

 Delta Lake – storage of the cleaned session table

 Databricks SQL – datasets and Metric View

 AI/BI Dashboards – front end layer

# Data Source
The data comes from my own Google Chrome browsing history, exported with the "Quick Chrome History Export" extension as a flat CSV file. The raw export contains one record per page load, including every page refresh, with columns such as date, time, title, URL, visit count and transition type.

# Features and Highlights

Project Motivation:
A personal project created to explore Databricks and AI/BI Dashboards on a dataset I know well. While simple in scope, the raw data required real preparation: the export logs every page refresh as a separate record, so a single visit can appear as dozens of rows within one minute, and the search engine, used as a start page, dominates every ranking.
 
Solution:
The project covers the full workflow, from a raw CSV file to a published dashboard:

 Sessionization – Consecutive page loads of the same website are merged into one session if the gap between them is shorter than 30 minutes. Each session has a start time, end time, duration and number of page views. This turns refreshes into real visits and makes the numbers reflect actual behavior.

 Data Cleaning – Website names are extracted from URLs, normalized and filtered. Google is excluded as a start page so that it does not distort the analysis of other websites.

 Data Model – Dimension tables Calendar and Pages are connected to the fact tables through relationships, so a single date range and page filter control all visuals on the page.

 Overview Page – Total number of visits, top pages ranking and a detailed table of all sessions with start and end time.

 Habits Page – Focused on the top 5 most visited websites (all-time ranking):
  KPI cards showing the highest week, the lowest week, the most active day of the week and the most active time of day.
  Weekly trend of visits per website, with weeks without activity shown as zero instead of being skipped.
  Heatmap of activity by day of the week and 2-hour time ranges, both in total and separately for each website in its brand color.
  
<img width="1497" height="812" alt="image" src="https://github.com/user-attachments/assets/1539dd4e-dc11-4fdd-93aa-5d07071394a2" />

<img width="1512" height="809" alt="image" src="https://github.com/user-attachments/assets/5f7d8ba4-4da0-4cda-a0c6-fe7365283c52" />

<img width="1568" height="781" alt="image" src="https://github.com/user-attachments/assets/841ffe28-e589-4cb8-8e20-f807a7b33533" />

