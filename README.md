Overview

This project analyzes customer behavior using a combination of Cohort Analysis and RFM (Recency, Frequency, Monetary) Segmentation, enhanced with machine learning (KMeans clustering).

The goal is to understand customer behavior over time, identify high-value segments, and uncover retention patterns to support data-driven decisions.

---
---

Objectives

Analyze customer retention using cohort analysis

Segment customers based on purchasing behavior

Identify high-value (VIP) and low-engagement customers

Support marketing and customer lifecycle strategies

---

Dataset

Transactional dataset containing:

CustomerID

Last_order_date

Recency, Frequency, Monetary

Revenue-related metrics

---

Methodology

1. Data Preprocessing

Data cleaning and preparation

Feature engineering (RFM metrics)

Log transformation to reduce skewness

2. Cohort Analysis

Grouped customers by first purchase date

Built retention matrix

Evaluated retention trends over time

Cohort Retention Heatmap

3. RFM Analysis

Recency: how recently a customer purchased

Frequency: how often they purchase

Monetary: how much they spend

4. Feature Scaling

Applied StandardScaler to normalize features

5. Customer Segmentation (KMeans)

Clustering performed on scaled RFM features

Optimal clusters selected using the Elbow Method

---

Results & Insights

🔹 Customer Segments

VIP Customers → High frequency, high spending, recent activity

Loyal Customers → Consistent buyers

At-Risk Customers → Declining engagement

Inactive Customers → Low activity and value

🔹 Key Insights

A small group of customers generates most of the revenue

Retention drops significantly after initial periods

Identifying at-risk customers enables proactive retention strategies

Example Output

Cluster	Recency	Frequency	Monetary	Segment
2	Low	High	High	VIP
1	Medium	Medium	Medium	Regular
0	High	Low	Low	Inactive

---

Technologies Used

Python

Pandas

NumPy

Scikit-learn

Matplotlib / Seaborn

---

Business Value

Customer segmentation for targeted campaigns

Retention analysis using cohorts

Identification of high-value customers

Data-driven decision making

---

👤 Author

Alan Giraldo
