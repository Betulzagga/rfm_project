# Customer Segmentation using RFM Analysis

This project performs customer segmentation using the RFM (Recency, Frequency, Monetary) model based on transactional e-commerce data.  
The aim is to identify different types of customers and support data-driven marketing strategies.

Customer segmentation is widely used in marketing analytics to better understand customer behavior and design personalized marketing campaigns.

---

# Project Objective

The goal of this project is to analyze customer purchase behavior and segment customers into meaningful groups based on their purchasing patterns.

Using the RFM framework, customers are evaluated based on three key metrics:

Recency → How recently a customer made a purchase  
Frequency → How often a customer makes purchases  
Monetary → How much money a customer spends

These metrics are converted into RFM scores and then mapped to predefined customer segments.

---

# Methodology

The project follows these steps:

1. Data preprocessing and cleaning
2. Calculation of Recency, Frequency and Monetary metrics
3. Conversion of RFM metrics into RFM scores
4. Creation of combined RFM score
5. Mapping RFM scores to customer segments
6. Analysis of customer segments

Customers are grouped into segments using rule-based segmentation.

---

# Customer Segmentation Logic

The following rule-based mapping is used to assign customers to segments:


Each customer receives an RFM score and is assigned to a specific segment.

---

# Customer Segments

| Segment | Description |
|-------|-------------|
| Champions | Best customers with high recency, frequency and monetary value |
| Loyal Customers | Customers who frequently purchase and have strong engagement |
| Potential Loyalists | Customers with potential to become loyal |
| New Customers | Recently acquired customers |
| Promising | Recently active customers |
| Need Attention | Customers who require engagement |
| About To Sleep | Customers who are becoming inactive |
| At Risk | Previously active customers who are declining |
| Can't Lose | High value customers that are close to churning |
| Hibernating | Customers with low engagement and inactivity |

---

# Business Value

RFM segmentation helps businesses:

• Identify high-value customers  
• Design personalized marketing campaigns  
• Improve customer retention  
• Increase customer lifetime value  
• Optimize marketing resources  

By understanding customer segments, companies can develop targeted strategies for each group.

---

# Technologies Used

Python  
Pandas  
NumPy  

---

# Output

The final dataset includes:

CustomerID  
Recency  
Frequency  
Monetary  
RFM Score  
Customer Segment  

This structured output enables companies to easily analyze customer behavior and apply targeted marketing strategies.

---

# Author

Betul Zagga
