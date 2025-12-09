 # Sales Analysis Report

### 1. Project Title / Headline
🔐 NextLevel PBI Reports: RLS-Enabled Dynamic Sales Analysis & Profitability Suite A professional, secure, and multi-page Power BI solution for sales management, utilizing Row-Level Security (RLS) and advanced bookmark navigation for focused, role-based analysis.

### 2. Short Description / Purpose
This report, developed as a personal project based on a Udemy course, serves as an enterprise-grade analytics platform. It provides a secure, interactive experience for users to monitor core sales health metrics—Units Sold, Net Sales, Net Profit, and Cost of Goods—across different periods and segments. The architecture includes Row-Level Security (RLS) to restrict data visibility, ensuring each manager or team member only sees the data relevant to their assigned territory or segment.

### 3. Tech Stack & Advanced Features
This project showcases mastery of security, modeling, and visualization in Power BI:

**Security (RLS):** Implements Row-Level Security (RLS) roles for different team members, restricting data access based on the user's login and the DIM_MANAGERS table. This ensures data governance and compliance.

**Manager Filtering:** The report uses a manager slicer/filter, likely linked to the DIM_MANAGERS table, allowing high-level users (like Heather Webster) to filter performance by individual team members (e.g., Alejandro Bennett or Alex Smith).

**Dimensional Modeling:** Uses a clean Star Schema with two Fact tables (FACT_SALES) connected to Dimension tables (DIM_DATE, DIM_MANAGERS), ensuring efficient performance.

**Bookmarks & Navigation:** Custom bookmarks create an "accordion" or "single-page" navigation experience, allowing the user to dynamically switch the context of the sidebar buttons (Period, Segment, Country, Product).

**Drillthrough Filters:** The metric-specific pages (Units Sold, Net Sales, Net Profit, Cost of Goods) are enabled as drillthrough destinations, allowing quick transition from high-level KPIs to focused trend analysis.

**DAX Measures:** Includes advanced time-intelligence (e.g., YOY: 236% seen on the Net Profit page) and dynamic metrics.

### 4. Report Structure & Key Views
The report uses Home and Sales Analysis as the non-hidden landing pages, with the remaining pages serving as drillthrough targets.

**1. Home Page**
Purpose: High-impact landing page summarizing Units Sold (1,125,788), Net Sales ($118.7M), and Net Profit ($16.9M), setting the context for the Sep/21-Dec/22 period.

**2. Sales Analysis Page**
**Purpose:** The central executive dashboard for multi-metric monitoring across countries.

**Key Visuals:** Six high-level KPI cards and a detailed matrix breaking down Units Sold, Net Sales, Profit, and COGS by Country, highlighting Canada and the USA as primary contributors.

**Interactivity:** Toggle filters (High, Medium, None) are present to analyze performance based on Discount Band.

**3. Metric-Specific Analysis Pages (Drillthrough Targets)**
These pages use the sidebar navigation to analyze trends by Period, Segment, Country, and Product:

**Net Profit Page:** Visualizes profit trending by period, noting significant growth (e.g., YOY: 236%) and identifying the Government segment as the largest profit driver.

**Units Sold Page:** Tracks sales volume by period and country (Canada, France, USA leading) and confirms the Government segment and Paseo product as volume leaders.

**COGS Page:** Analyzes cost trends, showing the USA leads in total Cost of Goods and the Government segment drives the highest COGS volume.
