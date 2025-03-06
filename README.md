# Customer Personality Analysis Dashboard

## Overview
This project presents a comprehensive analysis of customer data using Tableau. The aim is to segment customers for targeted marketing, understand their responses to promotions, and analyze their shopping behaviors and demographic profiles. The insights derived help the firm optimize marketing strategies and resource allocation.

## Project Description
The analysis utilizes customer records from the firm's database (Patel, 2021). The dataset comprises 30 columns and 2240 rows covering various customer attributes such as demographics, income, spending patterns, purchase channels, and responses to promotional campaigns. Three interactive Tableau dashboards have been developed to provide insights into:

1. **Customer Clusters Analysis and Promotions Insights**
2. **Customer Clusters and Purchase Channel Analysis**
3. **Profile Analysis of Customers**

## Business Problem
The primary goal is to perform a **Customer Personality Analysis** that helps to:
- **Segment Customers:** Use clustering techniques (K-means and elbow method) to identify unique customer segments.
- **Assess Promotional Impact:** Determine how different customer segments respond to discount offers and bundled deals.
- **Examine Shopping Channels:** Identify the primary shopping platforms (catalog, web, and store) and evaluate shopping frequency differences.
- **Analyze Demographics:** Understand the key demographic characteristics that influence shopping behaviors.

Key questions addressed include:
- How do customers respond to various promotions?
- Which promotional strategies drive the highest spending?
- What shopping platforms do customers prefer?
- What are the demographic profiles of our customer segments?

## Analysis & Methodology
The analysis is structured into three main dashboards:

### 1. Customer Clusters Analysis and Promotions Insights
- **Clustering:** Customers are segmented into three clusters using K-means clustering:
  - **Cluster 1:** Low income and low spending (largest segment at 54.4%)
  - **Cluster 2:** Average income and average spending
  - **Cluster 3:** High income and high spending (most valuable, 17.3%)
- **Promotional Response:**
  - Cluster 3 is most responsive to discount campaigns (49.1% of responses).
  - Cluster 1 tends to purchase bundled deals more frequently (55.1% of deal purchases).

### 2. Customer Clusters and Purchase Channel Analysis
- **Shopping Channels:** Analysis of shopping platforms reveals:
  - **Store shopping** is the most popular channel, particularly among Cluster 2 (41.4%).
  - **Web and catalog** purchases are also analyzed, with Cluster 2 leading web purchases (42%) and contributing significantly to catalog purchases.

### 3. Profile Analysis of Customers
- **Generational Groups:** Millennials and Generation X constitute the largest segments.
- **Relationship Status:** 64.4% of customers are in a relationship.
- **Parental Status:** Cluster 3 is predominantly composed of non-parents, which correlates with their high spending.
- **Education:** The majority of customers hold at least a bachelor's degree, with a significant number having postgraduate qualifications.

## Key Findings & Recommendations
- **Targeted Promotions:**
  - **Discount Campaigns:** Focus on Cluster 3 to leverage their high spending and responsiveness.
  - **Bundled Deals:** Target Cluster 1 to increase purchase frequency among the largest segment.
- **Optimizing Shopping Platforms:**
  - Enhance the store and web shopping experiences, as these channels show the highest activity.
- **Marketing Strategy:**
  - Use demographic insights (e.g., generational groups, relationship status, education) to refine marketing messages and campaigns.

## Dataset Details
- **Source:** Customer records from the firm's database (Patel, 2021)
- **Structure:** 30 columns and 2240 rows covering demographics, spending habits, promotional responses, and more.

### Sample Data (Excerpt)
| ID   | Education    | Living Arrangement | Generation Group | Age | Income | Children | Parent Status | Reg.Date   | Recency | Spending | Wines | Fruits | Meat | Fish | Sweet | Gold | Deals Purchases | Web Purchases | Catalog Purchases | Store Purchases | Web Visits in Month | Camp Accepted | Complaint | Cost Contact | Revenue |
|------|--------------|--------------------|------------------|-----|--------|----------|---------------|------------|---------|----------|-------|--------|------|------|-------|------|-----------------|---------------|-------------------|-----------------|----------------------|---------------|-----------|--------------|---------|
| 5524 | Graduate     | Alone              | Generation X     | 58  | 58138  | 0        | Not Parent    | 2012/09/04 | 58      | 1617     | 635   | 88     | 546  | 172  | 88    | 88   | 3               | 8             | 10                | 4               | 7                    | 1             | 0         | 3            | 11      |
| 2174 | Graduate     | Alone              | Baby Boomers     | 61  | 46344  | 2        | Parent        | 2014/03/08 | 38      | 27       | 11    | 1      | 6    | 2    | 1     | 6    | 2               | 1             | 1                 | 2               | 5                    | 0             | 0         | 3            | 11      |

## Tools & Technologies
- **Tableau:** For creating interactive dashboards.
  
## Snapshot of *Profile Analysis of Customers Dashboard
![iamge 2](https://github.com/user-attachments/assets/7a0f220e-aedd-487d-953c-171cc0c75f32)

## Repository Structure
```bash
├── README.md                                # Project overview and documentation
├── Marketing_Campaign.xlsx                  # Dataset files 
├── Customer_Behavior_Analysis.twbx          # Tableau workbook 
