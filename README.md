# Business Insights 360

## Project Overview

AtliQ Hardware is growing rapidly in recent years, and they have decided to implement data analytics using PowerBI in their company for the first time to surpass their competitors in the market and to make data-driven decisions. This project aims to provide answers to stakeholders' questions across all aspects, including finance, sales, marketing, and supply chain.

[Live Report Link](https://app.powerbi.com/view?r=eyJrIjoiYzc0MjNlNGEtMzU2Mi00YjM1LWIwMzMtZWRlYWE3ZjQ1MzlhIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)

I worked on this project by following the Codebasics PowerBi Course, Link to the course is [here](https://codebasics.io/courses/power-bi-data-analysis-with-end-to-end-project)

## Tech Stacks

- SQL
- PowerBI Desktop
- Excel
- DAX language
- DAX Studio (for optimizing the report)
- Project charter file

## PowerBI Techniques Learned

- Identifying the questions to ask before starting the project
- Creating calculated columns
- Creating measures using DAX language
- Data modeling
- Using bookmarks to switch between two visuals
- Page navigation with buttons
- Using divide function to prevent zero division errors
- Creating a date table using M language
- Dynamic titles based on applied filters
- Using KPI indicators
- Conditional formatting of values in visuals using icons or background color
- Data validation techniques
- PowerBI services
- Publishing reports to PowerBI services
- Setting up a personal gateway for auto-refresh of data
- PowerBI App creation
- Collaboration, workspace, and access permissions in PowerBI services
- And more 😅

## GitHub

- Uploading large size files using GitHub LFS
- Tracking specific file extensions for LFS

## Business-Related Terms

- Gross price
- Pre-invoice deductions
- Post-invoice deductions
- Net invoice sale
- Gross margin
- Net sales
- Net profit
- COGS - cost of goods sold
- YTD - Year to Date
- YTG - Year to Go
- Direct
- Retailer
- Distributors
- Consumer

## Company Background

AtliQ Hardware is a company that has grown significantly in recent years, opening businesses globally. It sells computers and computer accessories through three channels:

- Retailers
- Direct
- Distributors

Recently, the company faced an unforeseen loss by opening a store in America based on surveys, intuition, and some Excel analysis. Additionally, the company's competitors have analytics teams to perform analysis and make data-driven decisions. Thus, AtliQ Hardware has no other option but to build their analytics team for data-driven insights and decisions in the future to survive better in the industry.

## Project Kickoff Session

Before starting the dashboard, it's essential to get clarity on the following questions:

- What is the objective of building this PowerBI dashboard?
- How will the success of this project be measured?
- What is the project deadline?
- Do the stakeholders expect a preview before the actual release?
- What are the stakeholders' hopes for this project?
- What are the stakeholders' fears regarding building this dashboard?
- Who will be using this dashboard and for what purpose?
- What are the stakeholders' expectations by the project's completion?
- What can go wrong while building this project?
- What resources/data are needed to build this dashboard?
- Are there any design and view inputs from stakeholders?

After the project kickoff meetings, the data engineering team provided the necessary data for the data analytics team. Let's explore them.

### Dataset Understanding

Understanding the available data is crucial before analysis. Get a good grasp of what data is available.

- **Dimension Table**: Static data like customer and product details
- **Fact Table**: Data about transactions

#### gdb041:

- **dim_customer**:
  - 27 distinct markets (e.g., India, USA, Spain)
  - 75 distinct customers throughout the market
  - 2 types of platforms: Brick & Mortar (Physical/offline store) and E-commerce (Online Store like Amazon, Flipkart)
  - Three channels: Retailer, Direct, Distributors

- **dim_market**:
  - 27 distinct markets (e.g., India, USA, Spain)
  - 7 sub-zones
  - 4 regions: APAC, EU, NAN, LATAM

- **dim_product**:
  - Divisions: P&A (Peripherals, Accessories), PC (Notebook, Desktop), N&S (Networking, Storage)
  - 14 different categories, e.g., Internal HDD, keyboard
  - Different variants available for the same product

- **fact_forecast_monthly**:
  - Used to forecast customer needs in advance, leading to higher customer satisfaction and reduced storage costs
  - Denormalized for analytical work
  - All dates of the month replaced by the start date of the month
  - Contains forecast quantity needs

- **fact_sales_monthly**:
  - Similar to fact_forecast_monthly but with sold quantity instead of forecast value

#### gdb056:

- **freight_cost**:
  - Details of travel and other costs for each market with fiscal year

- **gross_price**:
  - Details of gross prices with product code

- **manufacturing_cost**:
  - Details of manufacturing costs with product code and year

- **pre_invoice_deductions**:
  - Details of pre-invoice deductions percentage for each customer with year

- **post_invoice_deductions**:
  - Post-invoice deductions and other deduction details

## Importing Data into PowerBI

- As the database is MySQL in this project, import the datasets from the MySQL database to PowerBI by providing the database access credentials.

### Dashboard designing

Based on the mock ups received as requirement, the team will start designing the visuals and create measure as and when required

## Home view

In Home view, all the views button will be available. User will land on specific view page by clicking the button 

- Info
- Finance View
- Sales View
- Marketing View
- Supply chain View
- Executive View
- Support

## Project Learnings and Reflections

- [ ] How to identify project objectives and success criteria
- [ ] Techniques for effective data modeling and DAX calculations
- [ ] Best practices for creating interactive and insightful PowerBI dashboards
- [ ] Strategies for data validation and optimization
- [ ] Insights into business terminologies and their implications on data analysis

This project has not only enhanced my technical skills but also provided real-world exposure to project management and business analysis.
