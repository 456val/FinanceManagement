#  Personal Finance Insights Dashboard  

A complete end-to-end pipeline that transforms raw financial transactions into a structured database and an interactive Power BI dashboard for real-time personal finance analytics.

##  Table of Contents  
- [Background](#-background)  
- [Objectives](#-objectives)  
- [Scope](#-scope)  
- [Data](#-data)  
- [Methodology](#-methodology)  
- [Deliverables](#-deliverables)  
- [Visuals / Screenshots](#-visuals--screenshots)  
- [Insights](#-insights)  
- [Recommendations](#-recommendations)  
- [Expected Impact](#-expected-impact)  
- [Usage / How to Run](#-usage--how-to-run)  
- [Future Work](#-future-work)  
- [License](#-license)  

## Background  
Managing personal finances often requires visibility into spending habits, income trends, and cash flow behavior. This project was created to build an automated, reliable, and interactive system that processes raw transaction data and converts it into actionable financial insights.

Through a pipeline involving **Excel → Python → SQL → Power BI**, the project delivers a dynamic dashboard that empowers individuals to understand and improve their financial management.

## Objectives  
- Clean and prepare raw transactional data for financial analysis.  
- Describe and categorize each transaction accurately.  
- Load structured data into a SQL database for querying and modeling.  
- Build an interactive Power BI dashboard showing inflow, outflow, balances, and spending patterns.  
- Demonstrate a seamless workflow from **data collection to visualization**.

##  Scope  

| Component | Description |
|----------|-------------|
| **Location / Context** | Personal finance tracking & analytics |
| **Data Category** | Income, expenses, categories, daily balances |
| **Focus / Challenge** | Converting unstructured transaction logs into an automated analytics ecosystem |

## Data  

**Dataset:** Personal finance transaction records  
**Source:** Excel file containing raw daily transactions  

### Data Fields  
- Date  
- Description  
- Amount (Positive = Income, Negative = Expense)  
- Category (Food, Transport, Bills, Savings, etc.)  
- Running Balance  

##  Methodology  

1. **Excel — Data Cleaning**  
   - Removed duplicates  
   - Handled missing values  
   - Standardized transaction descriptions  

2. **Python (Pandas) — Data Transformation**  
   - Categorized transactions  
   - Formatted dates and amounts  
   - Computed running balances  
   - Ingested processed data into SQL  

3. **Power BI — Analytics**  
   - Connected to SQL database  
   - Built interactive visuals showing:  
     - Inflow vs. Outflow  
     - Daily/Monthly balance  
     - Expense segmentation  
     - Trend analysis  

## Deliverables  
- Cleaned dataset (Excel → Python processed)  
- SQL database with transaction tables  
- Power BI dashboard  
- Data ingestion Python script  

##  Insights  

| Challenge (Before) | Insight (After) | Measurable Impact |
|--------------------|----------------|-------------------|
| Raw, inconsistent transaction logs | Structured and categorized data | Higher accuracy & clarity |
| Lack of financial visibility | Clear monthly trends | Better budgeting decisions |
| No category-level insights | Identified top spending categories | Improved spending discipline |
| Manual financial tracking | Automated pipeline | Saves time and reduces errors |

## Recommendations  
- Review high-expense categories weekly.  
- Create monthly budgets based on category insights.  
- Automate refresh schedule for SQL → Power BI.  
- Add alerts for overspending patterns.  

##  Expected Impact  
- Enhanced awareness of financial behaviors  
- Improved spending control and budgeting accuracy  
- Real-time insights for smarter money management  
- Fully automated personal finance analytics pipeline  
