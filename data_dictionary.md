# Data Dictionary - Retail Sales Dataset
### Task 1: Data Immersion & Wrangling

| Column Name | Data Type | Description | Business Relevance |
| :--- | :--- | :--- | :--- |
| **Transaction_ID** | Integer | Unique identifier for each sales transaction | Used to track unique orders and detect duplicate entries. |
| **Date** | Date (YYYY-MM-DD) | The day the transaction occurred | Crucial for time-series analysis and seasonal sales tracking. |
| **Customer_ID** | String / Object | Unique identifier for the customer | Helps analyze customer purchase frequencies and retention metrics. |
| **Gender** | Categorical | Customer gender (Male/Female) | Used for demographic analysis and targeted marketing campaigns. |
| **Age** | Numeric (Integer) | Customer age in years | Essential for demographic segmentation and customer lifetime valuation. |
| **Product_Category**| Categorical | Category of the purchased item | Identifies top-performing inventory sectors and product demand. |
| **Quantity** | Numeric (Integer) | Volume of items purchased per order | Used to calculate inventory depletion rates and transaction sizes. |
| **Price_Per_Unit** | Numeric (Float) | Price of a single item unit | Fundamental for pricing strategies and margin optimizations. |
| **Total_Amount** | Numeric (Float) | Total revenue generated (`Quantity * Price`) | Primary financial KPI used to monitor total top-line gross revenue. |