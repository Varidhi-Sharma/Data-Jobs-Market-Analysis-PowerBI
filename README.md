# Data Jobs Market Analysis using Power BI 
### Project Overview  
This project presents an interactive Power BI dashboard analyzing the global data job market. The dashboard provides insights into hiring trends, salary patterns, skill demand, remote work opportunities, and hiring companies to support data-driven business.

The project was built following Business Intelligence best practices, including star schema data modeling, DAX calculations, Power Query transformations, and executive-level dashboard design.

## Business Problem
The data job market is continuously evolving, making it difficult for employers to identify current hiring trends and required skills.

This dashboard answers key business questions such as:

- Which data roles are most in demand?
- Which technical skills are requested most frequently?
- Which job roles offer the highest salaries?
- How common are remote job opportunities?
- Which companies hire the most data professionals?
- How do hiring trends change throughout the year?

## Dashboard Pages
### Page 1 – Data Jobs Market Overview
Provides an executive summary of the overall job market.

#### KPIs
- Total Job Postings
- Hiring Companies
- Remote Jobs %
- Average Yearly Salary

#### Visuals
- Monthly Job Posting Trend
- Top Data Roles by Job Demand
- Global Distribution of Data Jobs
- Distribution of Remote vs On-Site Jobs

 ### Page 2 – Skills & Salary Intelligence
Analyzes market demand for technical skills and salary trends.

#### KPIs
- Total Skills Tracked
- Average Yearly Salary
- Top Skills
  
#### Visuals
- Top 10 Most In-Demand Skills
- Highest Paying Skills
- Skill Demand by Job Roles
- Average Salary by Job Roles

### Page 3 – Strategic Hiring Insights
Provides executive-level hiring insights and business recommendations.

#### KPIs
- Highest Paying Role
- Health Insurance Coverage %
- Top Hiring Company
- Remote Salary Premium
  
#### Visuals
- Top Hiring Companies
- Health Insurance Coverage
- Average Salary by Work Mode
- Executive Summary (Key Insights & Recommendations)

## Data Model
The project follows a Star Schema data model to improve report performance and maintainability.

#### Fact Table
- Job_Postings_Fact

#### Dimension Tables
- Company_Dim
- Date_Dim (Created in Power BI)
- Skills_Dim
- Schedule_Dim

#### Bridge Table
- Skills_Job_Dim
The bridge table resolves the many-to-many relationship between job postings and required skills.

## Key Insights
- Python and SQL are the two most requested technical skills, appearing in over 240K job postings.
- Data Engineer and Data Analyst roles account for the highest hiring demand.
- Senior Data Scientist positions command the highest average salaries (approximately $156K annually).
- Remote jobs represent approximately 13% of all job opportunities while offering an average salary premium of $14K over on-site roles.
- Hiring demand is concentrated among a relatively small number of companies, with Dice, Listopro, and Capital One leading recruitment activity.
- Cloud technologies and programming skills remain essential across multiple data-related job roles.

## Business Recommendations
- Expand remote hiring strategies to attract skilled professionals.
- Clearly communicate employee benefits such as health insurance.
- Focus recruitment on candidates with strong cloud and programming expertise.

## Tools & Technologies
- Power BI Desktop
- Power Query
- DAX
- Data Modeling
- Microsoft Bing Maps
- CSV Dataset

## Power BI Features Used
- Star Schema Data Modeling
- Bridge Table (Many-to-Many Relationship)
- Interactive Slicers
- KPI Cards
- DAX Measures
- Executive Dashboard Design
- Matrix Visuals
- Bar Charts
- Line Charts
- Donut Charts
- Map Visuals

## Dataset Information
The dataset consists of job postings collected from publicly available sources.

#### Files Included
- Job_Postings_Fact
- Company_Dim
- Skills_Dim
- Skills_Job_Dim
- Schedule_Dim

**Note**: The Date_Dim table was created directly in Power BI.

## Skills Demonstrated
- Business Intelligence
- Dashboard Design
- Data Visualization
- Data Modeling
- DAX
- Power Query
- Data Cleaning
- Analytical Thinking
- Business Storytelling
- Executive Reporting

## Repository Structure
Data-Jobs-Market-Analysis-PowerBI
│
├── README.md
├── Dashboard Screenshots
├── Power BI File
└── Documentation
