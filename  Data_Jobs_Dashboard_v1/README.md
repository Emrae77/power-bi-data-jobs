# Data Jobs Dashboard (v1) – Market Overview & Job Title Drill-Through

## Introduction

This project explores the 2024 data job market for **job seekers, job transitioners, and job swappers**. The goal is to centralize information that is usually scattered across multiple job platforms and provide a clear view of **job demand, salaries, and role characteristics**.

The dashboard is built in Power BI and focuses on both **high-level market monitoring** and **deep, job-title-specific analysis** via drill-through.

---

## Dataset & Context

- Real-world dataset of **2024 data-related job postings**
- Roles such as:
  - Data Engineer  
  - Data Analyst  
  - Data Scientist  
  - Senior / Lead variants  
- Key fields:
  - Job title, location, platform, schedule type
  - Yearly and hourly salary
  - Remote / on-site flags
  - Degree requirement mention
  - Health insurance mention
  - Posting dates

This combination supports both trend analysis and role-level profiling.

---

## Business Questions

This dashboard is designed to answer:

1. **Market Size & Trend**
   - How many data jobs are available?
   - How has the volume of postings changed over time?

2. **Role Demand**
   - Which job titles appear most frequently?
   - How are jobs distributed across different roles?

3. **Compensation**
   - What are the median yearly and hourly salaries by job title?
   - How do different roles compare in terms of pay?

4. **Job Title Profile (via Drill-Through)**
   - What is the salary range for a specific job title?
   - How common is remote work for that role?
   - How often is a degree explicitly required?
   - How frequently is health insurance mentioned?
   - Where are these jobs located globally?
   - Which platforms and schedule types dominate for that title?

---

## Dashboard Structure

### 1. Main Page – “Data Jobs Dashboard”

Key components:

- **KPI Cards**
  - Job Count  
  - Average Job Rating  
  - Median Yearly Salary  
  - Median Hourly Salary  

- **Jobs Over Time**
  - Line chart showing job count by month  
  - Highlights changes in demand across 2024

- **Job Counts by Title**
  - Bar chart ranking the most common data roles

- **Hourly vs Median Salary**
  - Scatter plot comparing hourly vs yearly pay across roles

- **Job Stats Table**
  - Job count, median salaries, and mini trend indicators by title
  - Acts as a launching point for drill-through

### 2. Drill-Through Page – “Job Title Drill Through”

When a specific job title is selected, this page shows:

- **Salary Gauges**
  - Yearly and hourly salary (min, max, and current median)

- **Work Conditions**
  - Donut charts for:
    - Work From Home %
    - No Degree Mention %
    - Health Insurance %

- **Jobs Globally**
  - Map visual for geographic distribution of postings

- **Job Platform & Job Schedule Type**
  - Bar and stacked visuals showing:
    - Where roles are posted
    - Full-time, contractor, and other schedule breakdowns

---

## Skills & Techniques Demonstrated

- **Power Query (ETL)**
  - Data cleaning, type conversion, and feature creation

- **Data Modeling**
  - Structured model suitable for drill-through and filtering

- **DAX**
  - Measures such as:
    - Job Count
    - Median Yearly Salary
    - Median Hourly Salary

- **Visualization Design**
  - KPI cards, line charts, bar charts, scatter plots, tables, gauges, maps, and donuts
  - Consistent styling and layout

- **Interactivity**
  - Job title filtering
  - Drill-through to a detailed job-title page
  - Navigation back to overview

---

## Screenshots

- **Overview page**

  ![Data Jobs Dashboard Overview](images/dashboard1_overview.png)

- **Job Title Drill-Through page**

  ![Job Title Drill-Through](images/dashboard1_drillthrough.png)

---

## Summary

Version 1 of the Data Jobs Dashboard serves as a **market overview and diagnostic tool**. It allows users to:

- Understand overall demand and salary levels,
- Compare data roles,
- And then dive into **one specific job title** for detailed insight.

This version is ideal when the goal is to monitor the market and investigate particular roles in depth.
