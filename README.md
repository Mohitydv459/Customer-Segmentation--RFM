# Customer-Segmentation--RFM
End-to-end Customer Segmentation project using SQL, Python, and Power BI. Implements RFM Analysis (Recency, Frequency, Monetary) to classify customers into actionable tiers like Platinum, Gold, and At-Risk to improve marketing ROI.

# 📊 Customer Segmentation & Behavioral Analysis (RFM)

## 🛠️ 1. The Business Context
"online_retail_II" is a mid-sized e-commerce retailer with a customer base of over 5,000 individuals. While the company has gathered significant transaction data, they currently treat all customers the same. Their marketing team sends the same generic email offers to everyone, resulting in:
-	Wasted Budget: High marketing spend on inactive customers who are unlikely to buy.
-	Missed Revenue: No special treatment for high-value VIPs, leading to lower retention rates.
-	Churn Blindness: Inability to identify loyal customers who have recently stopped purchasing.
  
## 🚀 2. The Business Problem 
The marketing team lacks a data-driven method to segment customers based on their purchasing behavior. They cannot answer key questions such as:
-	Who are our most profitable customers?
-	Who are our loyal customers that are at risk of churning?
-	Which inactive customers have the potential to be reactivated?

Without these insights, the company is experiencing a low Return on Ad Spend (ROAS) and a high customer churn rate.

## 💡 3. The Goal & Solution
The goal of this project is to implement an RFM Analysis (Recency, Frequency, Monetary) system to segment the customer base into actionable groups.
By building an automated pipeline using SQL (Extraction), Python (Statistical Scoring), and Power BI (Visualization), we aim to provide the marketing team with:
- 1.	Customer Tiers: Distinct segments like "Platinum Elite," "Loyal," and "At Risk."
- 2.	Targeting Strategy: A clear roadmap for which customers should receive discounts vs. exclusive offers.
- 3.	Churn Prevention: Early identification of "At Risk" customers to trigger win-back campaigns.


## 4. Key Insights & Findings
Based on the RFM segmentation analysis of 5878 customers, we have identified distinct behavioral patterns that directly impact revenue and growth.
**1. The "Pareto Principle" in Action (Revenue Concentration)**
-	Finding: The "Platinum Elite" and "Gold Member" segments make up only 30% of the total customer base, yet they contribute 78% of the total revenue.
-	Implication: The business is highly dependent on a small group of VIPs. Losing even a few of these customers would have a disproportionate impact on monthly sales.
**2. The "At Risk" Churn Alert**
-	Finding: There are 85 customers identified as "At Risk".
-	Behavior: These customers previously had high purchase frequency (Loyal) but have not made a purchase in the last 90+ days.
-	Implication: These are not "cold leads"; they are former loyalists who are likely switching to a competitor. This represents a potential revenue loss of approximately $58.94K.
**3. The "One-Timer" Problem**
-	Finding: The "Silver - New" and "Bronze" segments constitute the largest volume of users [67%].
-	Behavior: Most of these users purchased once and never returned.
-	Implication: The current customer acquisition strategy works, but the retention strategy is failing to convert new users into repeat buyers.
