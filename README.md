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

Based on the findings, the following strategies are proposed to reduce churn:

**Investigate Product 1 Issues**
- Conduct customer feedback surveys to identify pain points.
- Perform a pricing and feature analysis to ensure competitiveness.
- Enhance customer support for users of this product.

**Target High-Risk Customer Segments**
- Deploy personalized retention campaigns for 51-60-year-olds and customers with low credit scores.
- Offer loyalty incentives to reduce attrition within vulnerable segments.

**Implement a Churn Prediction Model**
- Use machine learning algorithms (e.g., Logistic Regression, Random Forest) to predict high-risk customers.
- Enable proactive retention strategies, reaching out to flagged customers before they churn.

By leveraging Customer Churn Analysis, National Bank can make data-driven decisions to improve customer retention and sustain long-term business growth.
