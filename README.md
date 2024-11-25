# Business Insights 360

## Project Overview

AtliQ Hardware has been growing rapidly in recent years, and they've decided to implement data analytics Reporting using Power BI in their company for the first time. Their goal is to surpass their competitors in the market and make growth using data-driven decisions. This project aims to provide data-driven answers to stakeholder questions across various aspects such as finance, sales, marketing, and supply chain.

I worked on this project by following the Codebasics Power BI Course. [Check out the course here](https://codebasics.io/courses/power-bi-data-analysis-with-end-to-end-project).

[Live Report Link](https://app.powerbi.com/view?r=eyJrIjoiYWIwN2VkNGMtYjVmMC00MjczLWI4ODQtNjE2OTlkMjVmMmI0IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)

## Tech and Softwares used

- SQL
- Power BI Desktop
- Excel
- DAX Language
- DAX Studio (for optimizing the report)
- Project Charter File

## Power BI Techniques Learned

- Asking the right questions before starting the project in format of 5W1H
- Creating calculated columns
- Creating measures using DAX language
- Data Entity modeling
- Using bookmarks to switch between report visuals
- Page navigation with buttons
- Using the divide function to prevent zero-division errors
- Creating a date table using M language
- Dynamic titles based on applied filters
- Using KPI indicators
- Conditional formatting in visuals using icons or background color
- Data validation techniques
- Power BI Services
- Publishing reports to Power BI Services
- Setting up a personal gateway to enable data auto-refresh
- Power BI App creation
- Collaboration, workspace, access permissions in Power BI Services
- And more! 😅

## Business-Related Terms

- Gross Price
- Pre-Invoice Deductions
- Post-Invoice Deductions
- Net Invoice Sale
- Gross Margin
- Net Sales
- Net Profit
- COGS - Cost of Goods Sold
- YTD - Year to Date
- YTG - Year to Go
- Direct
- Retailer
- Distributors
- Consumer

## Company Background

AtliQ Hardware is a company that has grown significantly in recent years, expanding its business globally. It sells computers and computer related accessories through three key channels:

- Retailers
- Direct
- Distributors

Recently, the company faced unforeseen losses by opening a store in America based on surveys, intuition, and some Excel analysis. Meanwhile, the company's competitors have analytics teams performing in-depth analysis and making data-driven decisions. To remain competitive in the market, AtliQ Hardware decided to build its analytics team for data-driven insights and future decisions.

### Questions to Ask Before Starting a Dashboard Project
 #### 5W1H format
- What is the objective of building this Power BI dashboard?
- What are the stakeholders' expectations upon project completion?
- What are the stakeholders' hopes for this project?
- What fears do stakeholders have regarding this dashboard?
- How will the success of this project be measured?
#### Common Questions
- Are stakeholders expecting a preview before the final release?
- Who will use this dashboard and for what purpose?
- What is the project timeline?
- What could go wrong during the project?
- What resources/data are needed to build this dashboard?
- Are there any design or view inputs from stakeholders?

After the project kick-off meetings, the data engineering team provided the required data to the data analytics team. Let's explore it.

### Dataset Understanding

Understanding the available data is crucial for analysis. Before jumping into analysis, get a good grasp of the data available.

- **Dimension Table**: Contains static data like customer and product details.
- **Fact Table**: Contains transaction data.

## Importing Data into Power BI

- As the database is in MySQL, we need to import the datasets from MySQL to Power BI by providing the database access credentials.

## Data Model

- Data modeling is vital and is considered the foundation of the report. All visuals will be built upon the data model.
- Poor data modeling affects the overall performance of the report.
- Following good practices of data modeling is essential. [Learn more about best practices here](https://addendanalytics.com/blog/data-modelling-best-practices/).
- In this project, we followed the Snowflake data modeling method.

![Data Model](https:.png)

### Dashboard Designing

Based on the received mock-ups, the team started designing the visuals and creating measures as needed.

## Home View

The Home view provides buttons for navigating to specific pages:

- Info
- Finance View
- Sales View
- Marketing View
- Supply Chain View
- Executive View
- Products
- Support

## Overall Report

![Overall Report](https:.gif)

## Info Page

![Info Page]([https:.gif](https://github.com/Subhojit45/Business-Insight-360/blob/main/View/Finance%20View.png))

## Finance View

![Finance View.png](https://github.com/Subhojit45/Business-Insight-360/blob/main/View/Finance%20View.png)

## Sales View

![Sales View.png](https://github.com/Subhojit45/Business-Insight-360/blob/main/View/Sales%20View.png)

## Marketing View

![Marketing View.png](https://github.com/Subhojit45/Business-Insight-360/blob/main/View/Marketing%20View.png)

## Supply Chain View

![Supply Chain View.png](https://github.com/Subhojit45/Business-Insight-360/blob/main/View/Supply%20Chain%20View.png)

## Executive View

![Executive View.png](https://github.com/Subhojit45/Business-Insight-360/blob/main/View/Executive%20View.png )

## Products

![Products.png](https://github.com/Subhojit45/Business-Insight-360/blob/main/View/Products.png)

You can find the full report file here: [Report]([https://github.pbix](https://github.com/Subhojit45/Business-Insight-360/blob/main/360.pbix))

## Project Outcome

By using this report, data-driven decisions can be made effectively. It will help answer numerous "why" questions based on various situations.
