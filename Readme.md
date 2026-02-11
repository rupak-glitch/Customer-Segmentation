-- Customer Segmentation using KMeans
- Overview

This project segments customers based on demographics, spending behavior, and purchasing patterns using KMeans Clustering.
The objective is to identify distinct customer groups to support targeted marketing and business decision-making.

- Dataset

2240 customers

29 features

Removed missing values in Income

Features include income, spending, purchases, campaign responses, and demographics.

- Data Preprocessing

Handled missing values

Standardized categorical values (Education)

Converted date column to datetime

Feature engineering:

Age

Total_Kids

Total_Spent

Customer_Since_Days

AcceptedAnyOffer (binary)

- Exploratory Data Analysis

Distribution plots (Age, Income, Spending, Kids)

Boxplots (Education vs Income, Marital Status vs Spending)

Correlation heatmap

Campaign acceptance vs spending analysis

- Clustering Approach
Features Used

Age

Income

Total Spent

Total Kids

Purchase behavior features

Recency

Education

- Steps

Applied StandardScaler

Used Elbow Method

Selected k = 6

Applied KMeans Clustering

Used PCA (2D) for visualization

- Key Customer Segments

Premium High-Value Customers (Highest income & spending)

Affluent Active Buyers

Consistent High Spenders

Budget Family Customers

Low-Income Low-Spenders

Educated but Low-Spending Customers

- Business Insights

High-income clusters generate most revenue.

Customers who accept campaigns spend more.

Families tend to be price-sensitive.

Premium customers prefer catalog/store purchases.

- Tech Stack

Python • Pandas • NumPy • Matplotlib • Seaborn • Scikit-learn • PCA • KMeans

- Conclusion

Successfully segmented customers into 6 meaningful groups, providing actionable insights for targeted marketing and strategic decision-making.
