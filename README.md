# Customer Churn Analysis

## Project Overview
In today’s competitive banking environment, understanding customer behavior is crucial for reducing attrition and improving satisfaction.  
This project performs an **Exploratory Data Analysis (EDA)** on a real-world banking dataset to uncover factors influencing **customer churn**.  
The analysis includes data cleaning, visualization, and trend identification to reveal what differentiates churned customers from retained ones.

---

## Objectives
1. Analyze customer churn distribution across demographic and behavioral segments.  
2. Identify the factors contributing to churn, such as transaction activity, income, and utilization ratio.  
3. Examine how product type, marital status, and customer service interactions impact attrition.  
4. Provide actionable insights to improve retention and reduce churn.

---

## Dataset Overview
The dataset contains structured information on banking customers, including demographics, account details, and usage behavior.

| Feature Category | Example Columns | Description |
| ---------------- | ---------------- | ------------ |
| **Demographics** | Gender, Age, Marital Status | Customer profile attributes |
| **Account Info** | Credit Limit, Avg Utilization Ratio | Banking account features |
| **Transaction Behavior** | Total Transaction Count, Total Transaction Amount | Customer activity metrics |
| **Customer Interaction** | Contact Count (12 months) | Frequency of contact with bank service |
| **Churn Indicator** | Attrition Flag | 1 = Churned, 0 = Active |

---

## Key Insights

### 1. Churn Distribution
- Out of **10,127 customers**, **1,627 (16%)** are churned.  
- Indicates a **moderate attrition rate**, suggesting potential retention issues.

### 2. Age Distribution
- Highest churn occurs among customers aged **38–53**.  
- Most frequent churn ages: **43** and **48 years old**.  
- Suggests mid-career customers may be switching to competitors for better offers.

### 3. Card Category and Churn
| Card Type | Churn Rate |
| ---------- | ----------- |
| Platinum   | 25% |
| Silver     | 14.8% |

- Platinum card holders churn more often — possibly due to higher fees or unmet premium expectations.

### 4. Gender-Wise Churn
- **Female:** 930 churned customers  
- **Male:** 697 churned customers  
- Indicates slightly higher attrition among female customers.

### 5. Transaction Behavior
- Among churned customers:  
  - **Total Transaction Count:** 10 to 94  
  - **Total Transaction Amount:** 510 to 10,583  
- Clear positive relationship: higher transaction count correlates with higher transaction amount.  
- Highest transaction amount: **10,583** with **75 transactions**.  
- Suggests transactional engagement strongly impacts retention.

### 6. Utilization Ratio and Churn
- Churned customers have **higher utilization ratios**.  
- **194 customers** exceeded the average utilization ratio, suggesting overspending may cause account closure or risk-based termination.

### 7. Income and Churn
| Income Category | Number of Churned Customers |
| ---------------- | --------------------------- |
| Less than $40K   | 612 |
| $40K – $60K      | 404 |
| $60K – $80K      | 283 |

- Lower-income customers have the **highest churn rate**, possibly due to limited spending capacity or credit risk management.

### 8. Marital Status and Churn
- **Married and Single** customers have similar churn levels.  
- Suggests marital status has minimal impact on churn behavior.

### 9. Credit Limit and Utilization
- Customers with **higher credit limits** tend to use a smaller proportion of their available credit.  
- However, some customers with both **high and low limits** churned without using their cards — indicating disengagement or poor onboarding.

### 10. Inactivity and Churn
- Most churned customers were **inactive for 3 months** before leaving.  
- Highlights inactivity as a strong churn predictor.

### 11. Customer Service Interaction
- Churned customers contacted customer service **more frequently** than retained ones.  
- Implies dissatisfaction or unresolved issues before churn.

---

## Behavioral Insights: Why Customers Churn

### Personal Reasons
1. Financial constraints or loss of income.  
2. Lifestyle changes (job relocation, new family responsibilities).  
3. Health issues or time constraints.  
4. Loss of interest, motivation, or lack of product relevance.  
5. Family influence or switching due to personal recommendations.  
6. Lack of customization or perceived value.

**Action:**  
Conduct **exit surveys**, allow **account pauses** instead of full cancellations, and offer **re-engagement campaigns** (e.g., limited-time offers).

---

## Service-Related Reasons for Churn

### 1. Poor Customer Service
- Long wait times, unhelpful staff, unresolved queries.  
**Strategy:** Improve customer support through training, chatbots, and priority help for loyal customers.

### 2. High Fees or Hidden Charges
- Unexpected maintenance or transaction fees.  
**Strategy:** Provide transparent statements and simplify fee structures.

### 3. Outdated Digital Experience
- Slow or buggy mobile apps and web platforms.  
**Strategy:** Invest in user experience design and mobile optimization.

### 4. Uncompetitive Interest Rates
- Better savings or loan rates offered by competitors.  
**Strategy:** Adjust rates or offer alternative benefits (cashback, rewards).

### 5. Complex Processes
- Tedious onboarding or loan applications.  
**Strategy:** Simplify with automation and e-KYC.

### 6. Lack of Retention Programs
- No follow-up for inactive customers.  
**Strategy:** Use churn prediction models to trigger targeted offers or feedback calls.

---

## Recommendations

1. **Early Churn Detection:**  
   Use predictive analytics to flag at-risk customers based on inactivity and transaction patterns.  

2. **Personalized Retention Campaigns:**  
   Offer tailored discounts or upgrades for mid-age and platinum customers with high churn probability.  

3. **Improve Customer Experience:**  
   Strengthen service quality and digital usability across channels.  

4. **Engagement Tracking:**  
   Monitor inactivity beyond 2 months as a key churn signal.  

5. **Simplify Banking Processes:**  
   Reduce complexity in online services and onboarding steps.  

6. **Transparent Pricing:**  
   Clarify fees, interest rates, and hidden charges proactively.  

7. **Customer Feedback Loop:**  
   Implement post-churn surveys to capture real-time insights into customer dissatisfaction.  

---

## Tools and Technologies
- **Python / Pandas / NumPy** – Data processing and cleaning  
- **Matplotlib / Seaborn** – Visualization and trend analysis  
- **Jupyter Notebook** – EDA and documentation environment  

---

## Conclusion
The analysis reveals that customer churn is primarily influenced by **transaction behavior, income, inactivity, and service dissatisfaction**.  
Customers in the **mid-age group (38–53)** and those with **higher utilization ratios** are more prone to churn.  
Service quality, digital engagement, and transparent communication are key to improving retention.  
Implementing proactive retention strategies and predictive churn models can significantly reduce attrition and improve customer loyalty.

