# 📊 Meta Ad Performance Dashboard | End-to-End Business Intelligence Project

<p align="center">

![Power BI](https://img.shields.io/badge/Power%20BI-Data%20Visualization-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-Advanced-blue?style=for-the-badge)
![Power Query](https://img.shields.io/badge/Power%20Query-Data%20Transformation-success?style=for-the-badge)
![Business Intelligence](https://img.shields.io/badge/Business%20Intelligence-End--to--End-orange?style=for-the-badge)
![Data Modeling](https://img.shields.io/badge/Data%20Modeling-Star%20Schema-purple?style=for-the-badge)

</p>

---

# 🚀 Project Overview

This project demonstrates a complete **Business Intelligence (BI) workflow** using **Microsoft Power BI** to analyze **Meta (Facebook & Instagram) advertising performance**.

Instead of focusing only on dashboard design, this project follows the complete BI development lifecycle—from understanding business requirements to delivering interactive business insights.

The solution converts raw marketing data into meaningful information that enables decision-makers to monitor campaign performance, evaluate customer engagement, analyze advertising effectiveness, and optimize marketing investments.

---

# 🎯 Business Goal

Marketing teams invest significant budgets across multiple advertising campaigns on Facebook and Instagram.

However, answering questions such as:

- Which campaign is performing the best?
- Which audience is more engaged?
- Which ad type generates better CTR?
- Which country contributes the highest engagement?
- How does engagement change over time?
- Which campaigns require optimization?

can be difficult when data is spread across multiple tables.

This dashboard provides a centralized Business Intelligence solution to answer these questions through interactive visual analytics.

---

# 📷 Dashboard Preview

## Dashboard Overview

![Dashboard Overview](Images/01_Dashboard_Overview.png.png)

---

## Interactive Dashboard (Filtered View)

![Filtered Dashboard](Images/02_Dashboard_Filtered_View.png.png)

---

# ⭐ Project Highlights

### Business Intelligence

- End-to-End BI Development
- Business Requirement Analysis
- Marketing Analytics
- KPI Monitoring
- Interactive Reporting

### Data Preparation

- Data Cleaning
- Data Transformation
- Power Query
- Data Validation
- Relationship Management

### Data Modeling

- Star Schema Design
- Fact & Dimension Tables
- Optimized Relationships
- Calendar Table
- Field Parameters

### Advanced Analytics

- DAX Measures
- Time Intelligence
- Dynamic Measure Selection
- KPI Calculations
- Marketing Performance Analysis

### Dashboard Development

- Executive KPI Cards
- Interactive Slicers
- Geographic Analysis
- Demographic Analysis
- Weekly Trend Analysis
- Hourly Trend Analysis
- Tooltip Pages
- Conditional Formatting

---

# 🛠 Technologies Used

| Category | Technology |
|-----------|------------|
| BI Tool | Microsoft Power BI |
| Data Transformation | Power Query |
| Data Modeling | Star Schema |
| Language | DAX |
| Dataset | Excel (.csv/.xlsx) |
| Reporting | Interactive Dashboard |
| Analytics | Business Intelligence |

---

# 📈 Key Performance Indicators (KPIs)

The dashboard provides interactive analysis of the following marketing KPIs:

- Total Impressions
- Total Clicks
- Total Shares
- Total Comments
- Total Purchases
- Total Engagements
- Click Through Rate (CTR)
- Engagement Rate
- Conversion Rate
- Purchase Rate
- Total Marketing Budget
- Average Budget per Campaign

---

> 📌 **This project demonstrates practical Business Intelligence skills including data preparation, data modeling, DAX development, time intelligence, and interactive dashboard design to support data-driven marketing decisions.**
>
> ---

# 💼 Business Problem

Digital marketing teams invest millions of dollars across Meta platforms such as **Facebook** and **Instagram** to run advertising campaigns.

However, marketing data is often distributed across multiple datasets, making it difficult to answer important business questions in real time.

Some of the common business challenges include:

- Which advertising campaign delivers the highest engagement?
- Which ad type performs better?
- Which audience segment is the most responsive?
- How effective is the advertising budget?
- Which geographic regions generate maximum engagement?
- How do engagement and conversions change over time?
- Which campaigns require optimization?

Without an interactive Business Intelligence solution, answering these questions requires manual analysis and significant effort.

This project addresses these challenges by transforming raw advertising data into an interactive analytical dashboard.

---

# 🎯 Project Objectives

The primary objective of this project is to develop an interactive Business Intelligence dashboard that enables stakeholders to monitor advertising performance and make data-driven marketing decisions.

### Business Objectives

- Monitor overall advertising performance.
- Track marketing KPIs in real time.
- Analyze campaign effectiveness.
- Compare Facebook and Instagram performance.
- Understand audience demographics.
- Evaluate advertising ROI.
- Support strategic marketing decisions.

### Technical Objectives

- Perform data cleaning using Power Query.
- Build a scalable Star Schema data model.
- Create reusable DAX measures.
- Implement Time Intelligence calculations.
- Design an interactive dashboard.
- Enable dynamic KPI selection using Field Parameters.
- Deliver actionable business insights.

---

# 🏢 Business Requirements

The dashboard was designed to meet the following reporting requirements.

### Executive Reporting

- Overall campaign performance
- Budget utilization
- Marketing KPIs
- Executive summary

### Campaign Analysis

- Campaign-wise performance
- Ad type comparison
- CTR analysis
- Conversion analysis

### Customer Analysis

- Gender distribution
- Age analysis
- Geographic distribution
- Interest-based segmentation

### Time Analysis

- Weekly trends
- Hourly trends
- Monthly calendar analysis
- Time Intelligence reporting

---

# 🔄 End-to-End Business Intelligence Workflow

The project follows a complete Business Intelligence lifecycle.

![Project Workflow](Images/06_Project_Workflow.png.png)

### BI Development Process

```text
Business Requirements
        ↓
Data Collection
        ↓
Power Query (Data Cleaning)
        ↓
Data Modeling
        ↓
DAX Development
        ↓
Time Intelligence
        ↓
Dashboard Development
        ↓
Business Insights
```

---

# 📂 Dataset Overview

The dashboard has been developed using multiple datasets that simulate Meta advertising performance.

### Tables Used

| Table | Description |
|--------|-------------|
| ads | Advertisement details including platform, campaign, audience and ad type |
| ad_events | Event-level advertising activities and engagement records |
| campaigns | Campaign information, duration and marketing budget |
| users | User demographic information such as age, gender, location and interests |
| Calendar Table | Custom date table created for Time Intelligence |
| Dynamic Measure Table | Field Parameter table for KPI selection |

---

# 📦 Dataset Relationships

The project uses a **Star Schema** data model consisting of fact and dimension tables.

Fact Table

- ad_events

Dimension Tables

- ads
- campaigns
- users
- Calendar Table

Supporting Table

- Dynamic Measure Selector

This modeling approach improves performance, simplifies DAX calculations, and ensures efficient filtering across visuals.

---

---

# 🧹 Data Cleaning & Transformation (Power Query)

Before creating the dashboard, the raw advertising data was prepared and transformed using **Power Query Editor** to ensure high-quality and reliable reporting.

### Data Cleaning Activities

✔ Removed duplicate records

✔ Checked and handled missing values

✔ Corrected data types

✔ Renamed columns for better readability

✔ Standardized categorical values

✔ Verified data consistency

✔ Optimized tables for reporting

✔ Prepared data for relationship modeling

### Why Data Cleaning?

Clean and well-structured data is essential for accurate reporting, efficient DAX calculations, and reliable business insights.

---

# 🏗 Data Modeling

A robust **Star Schema** data model was designed to establish efficient relationships between fact and dimension tables.

This approach improves dashboard performance, simplifies filtering, and enables scalable report development.

## Data Model

![Data Model](Images/03_Data_Model_Star_Schema.png.png)

---

## Data Model Architecture

### Fact Table

| Table | Purpose |
|--------|---------|
| **ad_events** | Stores event-level advertising interactions such as clicks, engagements, conversions, purchases, and timestamps. |

---

### Dimension Tables

| Table | Purpose |
|--------|---------|
| **ads** | Advertisement details including platform, campaign, ad type, target audience, and interests. |
| **campaigns** | Campaign information including budget, duration, start date, and end date. |
| **users** | User demographic details such as age, gender, country, and interests. |
| **Calendar Table** | Custom date dimension used for Time Intelligence calculations. |

---

### Supporting Table

| Table | Purpose |
|--------|---------|
| **Dynamic Measure Selector** | Field Parameter table used for switching KPIs dynamically. |

---

# ⭐ Data Modeling Highlights

- Star Schema Design
- One-to-Many Relationships
- Fact & Dimension Modeling
- Optimized Filtering
- Calendar Table Integration
- Scalable Architecture
- Performance-Oriented Model

---

# ⚡ DAX Development

Multiple reusable DAX measures were created to calculate business KPIs and support interactive reporting.

### Core Measures

- Total Impressions
- Total Clicks
- Total Shares
- Total Comments
- Total Purchases
- Total Engagements

### Marketing KPIs

- Click Through Rate (CTR)
- Engagement Rate
- Conversion Rate
- Purchase Rate
- Total Budget
- Average Budget per Campaign

### Dynamic Measures

The dashboard implements **Field Parameters** allowing users to switch between KPIs dynamically without creating multiple visuals.

This improves dashboard usability while reducing report complexity.

---

# 📅 Time Intelligence

A dedicated **Calendar Table** was created to enable Time Intelligence calculations and trend analysis.

### Implemented Features

- Custom Calendar Table
- Month Analysis
- Weekly Trend
- Hourly Trend
- Date Hierarchy
- Calendar Slicer
- Time-Based Filtering

These calculations allow users to analyze advertising performance across different time periods and identify seasonal or behavioral trends.

---

# 💡 Interactive Dashboard Features

The dashboard includes multiple interactive components to enhance user experience and business analysis.

## Implemented Features

✔ Dynamic Measure Selector

✔ Interactive Tooltips

✔ KPI Cards

✔ Calendar Slicer

✔ Campaign Filters

✔ Target Interest Filters

✔ Cross Filtering

✔ Geographic Map Analysis

✔ Weekly Trend Analysis

✔ Hourly Trend Analysis

✔ Demographic Analysis

✔ Ad Type Performance Comparison

---

## 🎯 Tooltip Preview

![Tooltip](Images/04_Tooltip_KPI_Cards.png.png)

The tooltip page provides additional KPI details when users hover over dashboard visuals, allowing deeper analysis without cluttering the main dashboard.

---

---

# 📈 Dashboard Insights

The dashboard provides meaningful business insights by transforming raw advertising data into actionable information.

## Marketing Insights

### Campaign Performance

- Monitor campaign-level performance using interactive filters.
- Compare campaign effectiveness across different advertising strategies.
- Track advertising budget utilization.

### Audience Analysis

- Analyze engagement distribution by gender.
- Identify the most active age groups.
- Explore geographic engagement across different countries.
- Analyze audience interests for better targeting.

### Advertisement Analysis

- Compare Image, Video, Stories, and Carousel advertisements.
- Measure Click Through Rate (CTR).
- Evaluate Engagement Rate.
- Analyze Purchase Rate and Conversion Rate.

### Time-Based Analysis

- Monitor Weekly Engagement Trends.
- Analyze Hourly Engagement Trends.
- Perform Monthly calendar-based analysis.
- Identify performance fluctuations over time.

---

# 🖼 Dashboard Screenshots

## Dashboard Overview

![Dashboard Overview](Images/01_Dashboard_Overview.png.png)

---

## Interactive Filter View

![Filtered Dashboard](Images/02_Dashboard_Filtered_View.png.png)

---

## Data Model

![Data Model](Images/03_Data_Model_Star_Schema.png.png)

---

## Tooltip Preview

![Tooltip](Images/04_Tooltip_KPI_Cards.png.png)

---

## Project Workflow

![Workflow](Images/06_Project_Workflow.png.png)

---

# 📁 Repository Structure

```
Meta-Ad-Performance-Dashboard-PowerBI
│
├── Business_Requirements
├── Dashboard
├── Dashboard_Insights
├── Dataset
├── Domain_Knowledge
├── Images
└── README.md
```

---

# 🛠 Tech Stack

| Category | Technologies |
|-----------|--------------|
| Business Intelligence | Microsoft Power BI |
| ETL | Power Query |
| Data Modeling | Star Schema |
| Data Analysis | DAX |
| Time Intelligence | Calendar Table |
| Dataset | Excel / CSV |
| Visualization | KPI Cards, Charts, Maps, Slicers, Tooltips |

---

# 💡 Skills Demonstrated

## Business Intelligence

- Business Requirement Analysis
- KPI Development
- Dashboard Design
- Marketing Analytics
- Data-Driven Decision Making

---

## Data Preparation

- Data Cleaning
- Data Transformation
- Power Query
- Data Validation

---

## Data Modeling

- Star Schema
- Fact & Dimension Tables
- Relationship Modeling
- Calendar Table

---

## DAX

- Calculated Measures
- KPI Calculations
- Dynamic Measure Selection
- Time Intelligence

---

## Dashboard Development

- Interactive Visualizations
- KPI Cards
- Dynamic Slicers
- Tooltips
- Geographic Analysis
- Trend Analysis
- Responsive Layout

---

# 🚀 Future Improvements

This project can be further enhanced by implementing:

- SQL Database Integration
- Power BI Service Deployment
- Incremental Refresh
- Row Level Security (RLS)
- Real-Time Streaming Data
- Azure Data Factory Integration
- Automated Refresh Schedule
- Mobile Dashboard Optimization

---

# 👨‍💻 About Me

Hi, I'm **Saif Anwar**, an aspiring **Power BI Developer** and **Business Intelligence Enthusiast** passionate about transforming raw data into meaningful business insights.

I enjoy working on end-to-end BI projects involving:

- Business Requirement Analysis
- Data Cleaning
- Data Modeling
- DAX Development
- Dashboard Design
- Business Insights

I'm continuously improving my skills in Power BI, SQL, Excel, and Data Analytics while building practical portfolio projects.

---

# ⭐ If you found this project helpful

If you like this project, consider giving it a ⭐ on GitHub.

Feedback and suggestions are always welcome!

---

> **Thank you for visiting this repository!**
