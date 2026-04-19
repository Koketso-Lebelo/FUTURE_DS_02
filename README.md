# Customer Churn & Retention Analysis Dashboard | Power BI


An interactive **Power BI dashboard** analyzing customer churn for a subscription-based Telecom company. This project identifies churn patterns, key risk factors, and provides actionable insights to improve customer retention and increase Lifetime Value (LTV).

Designed to simulate real-world analytics work in SaaS, Telecom, and subscription-based businesses.

##  Project Objectives

- Calculate overall churn rate and retention trends
- Identify high-risk customer segments
- Uncover the main drivers of customer churn
- Analyze customer lifetime behavior
- Deliver data-driven recommendations to reduce churn

## Files included
1. Future Interns task 2.pbix 
2. Customer Churn analysis.mp4 – Screen recording / video walkthrough showing the report’s functionality and interactions

##  Dataset

**Dataset:** Telco Customer Churn Dataset  
**Source:** [Kaggle - Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

The dataset contains **~7,000 customers** with information on demographics, subscription details, services used, billing, and churn status.

##  Tools & Technologies

- **Power BI Desktop** – Dashboard development & visualization
- **Power Query** – Data cleaning and transformation
- **DAX** – Custom measures and KPIs
- Interactive filtering and slicing

##  Data Preparation & Feature Engineering

- Cleaned and standardized the dataset
- Handled missing values and data type conversions
- Created new calculated columns:
  - **Tenure Group** (Customer lifecycle segmentation)
  - **Monthly Charge Band** (Pricing segmentation)
  - **Customer Status** (Churned vs Retained)
- Built DAX measures for Churn Rate, Retention Rate, and Average Customer Lifetime

##  Key Metrics (KPIs)

- **Total Customers**: ~7,000
- **Churn Rate**: ~27%
- **Average Customer Lifetime**: ~32 months
- **Average Monthly Charges**
- **Customers Churned**

##  Dashboard Structure

### Page 1: Executive Overview
- KPI Cards (Total Customers, Churn Rate, Avg. Lifetime, etc.)
- Churn Rate by Contract Type
- Churn Rate by Tenure Group
- Churn Rate by Payment Method
- Churn Rate by Internet Service
- Churn Rate by Monthly Charges

### Page 2: Retention Drivers Analysis
- Churn Rate by Tech Support, Online Security & Device Protection
- Average Customer Lifetime by Churn Status
- Deep dive into factors influencing retention

### Page 3: Insights & Recommendations
- Summary of key findings
- Actionable business recommendations

**Interactive Filters:** Gender, Contract Type, Internet Service, Tenure Group, Payment Method

##  Key Insights

- Month-to-month contracts have significantly higher churn rates
- Highest churn occurs within the **first 12–24 months** of tenure
- Customers paying via **electronic check** show elevated churn
- Higher monthly charges strongly correlate with increased churn
- Customers **without** Tech Support, Online Security, or Device Protection are far more likely to churn
- Retained customers have a much longer average lifetime than churned ones

##  Business Recommendations

- Strengthen onboarding experience to reduce early-stage churn
- Offer incentives and discounts to encourage longer-term contracts
- Bundle value-added services (Tech Support, Online Security, Device Protection) to increase stickiness
- Proactively engage high-risk segments (month-to-month + high monthly charge + low tenure)
- Review pricing strategy to ensure charges align with delivered value


##  How to Use

1. Clone or download the repository
2. Open `Future Interns Task 2.pbix` in **Power BI Desktop**
3. Use the slicers and filters to explore different customer segments and insights

##  Project Highlights

- Real-world churn analysis using industry-standard techniques
- Professional dashboard design with clear storytelling
- Strong focus on **actionable business recommendations**
- Feature engineering and DAX implementation for deeper insights

---

**Author:** Koketso Lebelo  


