# Customer Churn Analysis

## 1. Business Case

National Bank, a banking provider, has been struggling with an increasing churn rate, losing customers annually. Despite competitive pricing and service offerings, many customers are discontinuing their acounts. The leadership team is concerned about the long-term sustainability of customer retention and seeks data-driven insights to mitigate churn.

By conducting a Customer Churn Analysis, this project aims to:
- Identify key factors influencing churn to understand why customers leave.
- Segment at-risk customers to develop targeted retention strategies.
- Recommend actionable business interventions based on Power BI insights.

This analysis enables National Bank to implement proactive measures that enhance customer satisfaction and loyalty, ultimately reducing churn and increasing revenue.

## 2. Data Structure

To conduct this analysis, I used a dataset containing 9867 unique users. The dataset was structured as follows:

![image alt](https://github.com/GeorgeWLZD/customer_churn_analysis/blob/90506122d7c6938dd2f2349db9ce73ed2a24643a/img/data1.JPG)

Based on this dataset I built this **data model** to make the analysis:
![image alt](https://github.com/GeorgeWLZD/customer_churn_analysis/blob/90506122d7c6938dd2f2349db9ce73ed2a24643a/img/data2.JPG)

## 3. Results

The **Power BI dashboard** visualizes product associations and highlights strategic opportunities:

![image alt](https://github.com/GeorgeWLZD/market_basket_analysis/blob/3245c4a11cd008c2adbbffd1bd59fbf45a766809/img/viz.JPG)

**Association Rules Table**
- Strong product relationships have high Lift values (>2.0) and appear frequently in transactions (high Support).
- Example: Customers who buy Root Vegetables are 3 times more likely to also purchase Herbs.
- Opportunity: Bundle these items together in promotions.

**Scatter Plot** (Lift vs. Support)
- High Lift, Low Support: Hidden opportunities! These product pairs aren't bought together often, but when they are, the association is strong.
- Example: Wine and Cheese have a Lift of 4.2 but appear in only 2% of transactions.
- Opportunity: Increase visibility by placing these items closer together in-store or recommending them online.

**Network Graph Analysis**
- Some products act as key connectors, frequently appearing in multiple strong associations.
- Example: Whipped/sour cream, yogurt and root vegetables appeared wuite frequently.
- Opportunity: Position these “anchor products” in prime store locations or highlight them in digital marketing campaigns.

## 4. Business Recommendation

Based on the insights from the analysis, here are actionable business strategies:

**Increase Revenue with Bundling & Discounts**
- Promote high-lift product pairs with combo deals (e.g., Coffee + Pastries).
- Implement "Frequently Bought Together" sections in e-commerce.

**Optimize Store Layout & Digital UX**
- Place strongly related products closer together in physical stores.
- Use data-driven recommendations in e-commerce to enhance user experience.

**Improve Targeted Marketing & Promotions**
- High-lift, low-support products need awareness-building campaigns.
- Personalize discounts based on past customer purchases.

By leveraging **market basket analysis**,8 FreshMart can drive revenue growth with minimal effort—simply by strategically placing and promoting products. This approach can further be enhanced with machine learning-based recommendation systems for real-time personalized offers. **The next step** is to implement automated product recommendations and use machine learning to refine cross-selling strategies.
