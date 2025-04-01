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

![image alt](https://github.com/GeorgeWLZD/customer_churn_analysis/blob/4caaea90157cd79fa9201dd6deb460a91e8a58cc/img/viz.JPG)

**Churn Rate Analysis**\
- The overall churn rate is 20.45%, exceeding the company’s target of 12%.
- 2,018 customers were lost, leading to significant revenue losses.
- Opportunity: Immediate intervention is needed to improve retention strategies.

**Customer Segmentation Insights**\
- Age Group: Customers aged 51-60 exhibit the highest churn rate.
- Credit Score: Customers with a credit score ≤ 400 are at significantly higher risk.
- Gender: 56% of churned customers are female, compared to 44% male.
- 64% of churned customers were inactive, aligning with disengagement patterns.
- 35% of churned customers were still active, suggesting dissatisfaction or competitor influence.
- Geographic Trends: Orlando and Miami have the highest churn rates, indicating possible service gaps or strong competitor presence.

**Product Performance & Red Flags**\
- 70% of churned customers subscribed to Product 1, highlighting a potential issue.
- Opportunity: Further investigation is required to assess product-market fit, pricing, or service quality.

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
