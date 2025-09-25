# Banking Analysis Dashboard

A comprehensive Tableau-based banking and loan analysis dashboard that provides insights into loan performance, customer demographics, and financial metrics.

## 📊 Dashboard Overview

This banking analysis dashboard analyzes loan data with multiple financial KPIs and visualizations to help understand:
- Loan performance across different customer segments
- Geographic distribution of loans
- Risk assessment metrics
- Payment behavior patterns

## 🎯 Key Performance Indicators (KPIs)

### Primary KPIs
1. **Year Wise Loan Amount** - Total loan amounts distributed across different years
2. **Grade & Sub-grade wise Revolving Balance** - Risk assessment based on credit grades
3. **Verified Vs Non-Verified Status Payment** - Payment behavior by verification status
4. **State & Month wise Loan Status** - Geographic and temporal loan distribution
5. **Home Ownership Vs Last Payment Date Stats** - Payment patterns by home ownership status

## 📈 Visualizations and Worksheets

### Main Dashboards
- **Detail KPI 1** - Primary dashboard containing key metrics and trends

### Individual Worksheets
1. **Avg Grade & Sub-grade wise Revolving Balance** - Average revolving balances segmented by credit grades
2. **Count of Total Payment by Verification Status** - Payment distribution analysis
3. **Grade wise** - Credit grade analysis
4. **Homeownership wise Loan** - Loan amounts by home ownership status
5. **State wise Loan Count** - Geographic loan distribution
6. **Year/Month/Quarter wise Loan Amount** - Temporal loan analysis
7. **Verification Status** - Customer verification analysis
8. **Loan Purpose** - Analysis by loan purposes

## 📊 Data Structure

### Primary Data Sources
- **Finance_1**: Core loan information including:
  - Loan amounts and funding details
  - Interest rates and installments
  - Customer demographics
  - Employment information
  - Geographic data (zip codes, states)
  
- **Finance_2**: Extended financial metrics including:
  - Credit history and delinquency records
  - Account information
  - Payment history
  - Recovery and collection data

### Key Data Fields
- **Loan Information**: `loan_amnt`, `funded_amnt`, `int_rate`, `installment`
- **Customer Details**: `member_id`, `emp_title`, `home_ownership`, `annual_inc`
- **Geographic**: `addr_state`, `zip_code`
- **Risk Metrics**: `grade`, `sub_grade`, `verification_status`, `loan_status`
- **Temporal**: `issue_d`, `earliest_cr_line`, `last_credit_pull_d`

## 🔍 Business Insights

### Risk Analysis
- **Credit Grading**: Analysis of loans by credit grades (A-G) and sub-grades
- **Verification Impact**: Performance comparison between verified and non-verified customers
- **Delinquency Patterns**: Historical delinquency analysis over 2-year periods

### Geographic Analysis  
- **State-wise Performance**: Loan distribution and performance across US states
- **Regional Trends**: Geographic patterns in loan amounts and statuses

### Temporal Analysis
- **Seasonal Trends**: Year, quarter, and month-wise loan issuance patterns
- **Performance Over Time**: Loan performance trends across different time periods

### Customer Segmentation
- **Home Ownership**: Loan patterns by ownership status (own, rent, mortgage)
- **Employment**: Analysis by employment titles and length
- **Income Levels**: Loan performance by annual income brackets

## 🛠 Technical Details

### Dashboard Features
- **Interactive Parameters**: Top 5, 10, and 20 state filters
- **Dynamic Filtering**: Cross-worksheet filtering capabilities
- **Color Coding**: Visual indicators for different risk levels and statuses
- **Drill-down Capabilities**: Hierarchical navigation from high-level to detailed views

### Data Processing
- **Data Refresh**: Configured for regular data updates
- **Calculated Fields**: Custom metrics for enhanced analysis
- **Data Relationships**: Linked Finance_1 and Finance_2 datasets for comprehensive analysis

## 📋 Usage Instructions

### Prerequisites
- Tableau Desktop 2025.1 or later
- Access to the source banking data (Banking.xlsx)

### Opening the Dashboard
1. Download the `Banking Analysis.twbx` file
2. Open with Tableau Desktop
3. Refresh data connections if needed
4. Navigate through different worksheets and dashboards

### Key Navigation Tips
- Use the parameter controls to adjust the number of states displayed
- Click on charts to filter related visualizations
- Explore different worksheets for specific analysis areas
- Use the dashboard view for comprehensive overview



Ultra

