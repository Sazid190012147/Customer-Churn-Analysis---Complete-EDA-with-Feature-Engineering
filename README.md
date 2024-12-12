# 🛠️ Customer Churn Analysis Project
## 📖 Overview
Customer churn is one of the biggest challenges for subscription-based businesses, directly impacting revenue and profitability. This project analyzes a dataset of subscription customers to uncover patterns and factors that contribute to churn. The goal is to provide actionable insights to improve customer retention and optimize business strategies.
By performing Exploratory Data Analysis (EDA), this project identifies key factors influencing churn and presents data-driven recommendations to reduce customer attrition.

## 📊 Dataset Description
The dataset contains 64,374 customer records and provides comprehensive details about customer demographics, usage behavior, subscription details, and engagement levels.
Columns in the Dataset:
- Age: Age of the customer.
- Gender: Gender of the customer (e.g., Male, Female).
- Usage Frequency: How frequently the customer uses the service.
- Support Calls: Number of support calls made by the customer.
- Payment Delay: Number of days the customer delayed payment.
- Subscription Type: The type of subscription plan (e.g., Basic, Standard, Premium).
- Contract Length: Duration of the subscription contract (e.g., Monthly, Quarterly, Annual).
- Total Spend: Total amount spent by the customer.
- Last Interaction: Days since the customer's last interaction with the service.
- Churn: Binary variable indicating churn status (1 for churn, 0 for retention).
- Tenure Group: Categorized customer tenure (e.g., 1–12 months, 25–36 months).

## 🔍 Key Findings
**Dataset Quality:**
- No missing data or outliers.
- Balanced dataset with a churn ratio of 53:47.
**Customer Behavior Insights:**
- Older customers (54–65 years) are more likely to churn, while younger males show lower churn rates.
- Low usage frequency (≤5) and higher payment delays (≥15 days) significantly contribute to churn.
- Customers with high spending and longer tenure have lower churn rates.
**Gender Trends:**
- Females are more likely to churn than males (54% vs. 37%).
- Older females (above 50) have the highest churn tendency.
**Contract and Support Patterns:**
- Monthly contracts exhibit a higher churn rate compared to quarterly and annual contracts.
- High churn is observed when support calls exceed 5, indicating dissatisfaction.
**Key Correlated Factors:**
- Payment delays, support calls, and female gender strongly influence churn.

## 🚀 Recommendations
- **Retention Strategies:** Focus on retaining older customers (especially females above 50) by offering personalized plans or loyalty rewards.
- **Improve Customer Support:** Address issues proactively when support calls increase.
- **Incentivize Longer Contracts:** Encourage customers to switch from monthly contracts to quarterly or annual contracts.
- **Encourage Usage:** Provide usage incentives or engagement campaigns for low-frequency users.
- **Address Payment Delays:** Introduce reminders or discounts for early payments to reduce delays.

## 📂 Project Workflow
**STEP 01 - Data cleaning & Preprocessing:** 
- Checked for missing values and outliers.
- Performed data cleaning and Preprocessing.

**STEP 02 - Exploratory Data Analysis (EDA):**
- Performed Numerical Analysis
- Performed Univariate Analysis 
- Performed Bivariate Analysis
- Performed Feature Encoding

**STEP 03 - Key Insights Extraction:**
- Correlation analysis to determine factors influencing churn.

**STEP 04 - Recommendations:**
- Presented actionable insights to reduce churn and improve retention.

## 💡Tools and Technologies
- **Python:** The main programming language used for analysis and data manipulation.
- **Pandas:** Used for data manipulation and cleaning.
- **Matplotlib/Seaborn:** For data visualization and plotting.
- **Jupyter Notebook:** Used for organizing and presenting the analysis in an interactive environment.

## 👩‍💻 Author
This project was completed by **Tawhidul Islam Sazid**, a passionate data analyst and machine learning enthusiast.
Feel free to reach out for collaboration or feedback:  
📧 Email: [tawhidulislam2590@gmail.com.com]  
🌐 LinkedIn: [Tawhidul Islam Sazid](https://www.linkedin.com/in/sazid147/)  
🐙 GitHub: [@Sazid](https://github.com/Sazid190012147)
