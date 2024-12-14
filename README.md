# data-descriptive-sahithi
# README: Descriptive Analysis of Vancouver's Capital Budget Data

## Project Description
Descriptive Analysis of the City of Vancouver’s Multi-Year Capital Project Budget Data

## Project Title
Analyzing Customer Purchase Patterns at XYZ Retail

## Objective
The goal of this project is to conduct a descriptive analysis of Vancouver's multi-year capital project data. This analysis aims to summarize key trends and insights in budget allocation and expenditures to inform stakeholders and support decision-making processes.

## Dataset
The data includes:
- Multi-year capital project budgets for 2025
- Historical expenditure data
- Service categories such as "Public Safety," "Streets," and "Parks and Open Spaces"
- Additional metadata detailing project names and budgetary variances

## Methodology
### 1. Data Collection
- The dataset was sourced from the City of Vancouver open data portal.
- Filters were applied to extract relevant service categories and budget-related data.
- The filtered data was staged and stored in AWS S3 buckets (`ceb-raw-sah`).

### 2. Data Profiling and Cleaning
- AWS Glue DataBrew was used for profiling and cleaning.
  - Missing values were identified and imputed appropriately.
  - Outliers were addressed to maintain dataset integrity.
  - Duplicates were removed for streamlined analysis.
- A standardized schema was implemented to align data formats across all fields.

### 3. Data Analysis
#### Descriptive Statistics
- Summary metrics were calculated, including:
  - Total budget allocations per service category
  - Average expenditures over the past years
  - Variances between proposed budgets and historical spending

#### Visualizations
- Bar charts and pie charts were created to visualize:
  - Budget distribution across service categories
  - Year-on-year expenditure trends
  - Percentage share of total budget by service category
 
    ![image](https://github.com/user-attachments/assets/8c08115a-5a82-4de3-8ba7-30f96a866e76)


#### Segmentation
- Projects were grouped by categories to identify high-priority and high-expenditure areas.
- Segments were analyzed for patterns in funding and spending efficiency.

### 4. Reporting
- Findings were compiled into dashboards using Tableau and Power BI for intuitive stakeholder communication.
- Key insights were summarized in a report with actionable recommendations.

## Tools and Technologies
- **AWS Services:** S3, Glue DataBrew, and Athena for storage and cleaning.
- **Data Visualization:** Tableau and Power BI for creating interactive dashboards.
- **Data Analysis Tools:** Excel and SQL for statistical calculations and trend analysis.

## Deliverables
- A cleaned and structured dataset stored in AWS S3.
- Dashboards visualizing key trends and metrics.
- A report summarizing findings and recommendations for budget optimization.

## Conclusion
The descriptive analysis provided valuable insights into Vancouver's multi-year capital project budgets. By leveraging AWS and data visualization tools, the analysis highlighted patterns and trends critical to strategic planning. The structured approach and detailed reporting enable stakeholders to make informed decisions, optimizing budget allocation and improving financial transparency.
