# 📊 *Customer Churn Analysis Report*

### *Prepared by:* Prosenjit Majumder

### *Tools Used:* Python (Pandas, Seaborn, Matplotlib), Jupyter Notebook

### *Objective:*

To analyze customer churn data, identify key factors influencing churn, and provide actionable insights to reduce customer attrition.

---

## 🔍 *1. Project Background*

Customer churn is one of the critical metrics that directly impacts the revenue of subscription-based businesses. This project aims to uncover patterns in customer behavior that indicate churn risk and suggest strategies to retain customers.

---

## 🧾 *2. Dataset Overview*

The dataset consists of *5,283* customer records with the following key attributes:

* *Demographics:* Gender, SeniorCitizen, Partner, Dependents
* *Service Information:* PhoneService, InternetService, StreamingTV, StreamingMovies, etc.
* *Account Info:* Tenure, Contract Type, MonthlyCharges, TotalCharges
* *Target Variable:* Churn (Yes/No)

---

## 🧪 *3. Data Cleaning & Preprocessing*

* Removed rows with missing values in TotalCharges.
* Converted TotalCharges to numeric.
* Encoded categorical variables for modeling.
* Created new features like Tenure Groups for better segmentation.

---

## 📈 *4. Exploratory Data Analysis (EDA)*

### A. *Churn Rate*

* Overall churn rate: *\~26.5%*
* Indicates a considerable portion of customers leaving.

### B. *Demographics & Churn*

* *Senior Citizens:* Higher churn rate (\~42%) compared to non-seniors.
* *Customers without partners or dependents* are more likely to churn.

### C. *Service-Based Insights*

* *Fiber optic* internet users churn more than DSL users.
* Customers using *multiple streaming services* have slightly higher churn rates.
* Lack of online security or tech support increases churn probability.

### D. *Contract & Payment Analysis*

* *Month-to-month contract customers* churn the most (\~43%).
* Long-term contracts (1-year, 2-year) significantly reduce churn.
* *Electronic check payments* have higher churn than other payment methods.

### E. *Tenure and Charges*

* Customers with *tenure < 1 year* are most likely to churn.
* High *MonthlyCharges* customers also show high churn, particularly if tenure is low.

---

## 🧠 *5. Key Insights & Correlations*

| Feature                          | Churn Rate | Insight                                     |
| -------------------------------- | ---------- | ------------------------------------------- |
| Contract: Month-to-month         | High       | More prone to churn                         |
| Internet Service: Fiber          | High       | Fast but less loyal                         |
| Tech Support: No                 | High       | Support may be a retention factor           |
| Tenure < 1 year                  | Very High  | Onboarding experience critical              |
| Payment Method: Electronic Check | High       | Possibly linked to less committed customers |

---

## 🧩 *6. Recommendations*

1. *Incentivize long-term contracts* to reduce churn from month-to-month subscribers.
2. *Improve onboarding and support* in the first year of customer lifecycle.
3. *Targeted retention campaigns* for high-risk groups (e.g., fiber optic users, seniors).
4. *Introduce bundling options* to encourage multi-service usage in a controlled way.
5. *Offer payment flexibility or rewards* to convert electronic check users to auto-pay cards.

---



## 📁 *7. Project Files & Artifacts*

* Dataset: Customer Churn.csv [👁️ View | 📥 Download](https://github.com/prosenjit500/Customer_Churn_Analysis/blob/main/Customer%20Churn.csv)
* Jupyter Notebook: EDA, Visualization, Preprocessing [👁️ View | 📥 Download](https://github.com/prosenjit500/Customer_Churn_Analysis/blob/main/Customer_Churn_Analysis.ipynb)
* PDF Report: Provide actionable insights to reduce customer attrition [👁️ View | 📥 Download](https://github.com/prosenjit500/Customer_Churn_Analysis/blob/main/Customer%20Churn%20Analysis%20Report.pdf)

---

## ✅ *Conclusion*

Understanding customer churn is essential for proactive business decision-making. This analysis provides a data-driven foundation to reduce attrition and improve customer satisfaction. With further modeling, the business can move towards predictive retention and smarter lifecycle management.

---

## 📬 Contact & Contributions  
If you find these projects useful or have suggestions for improvements, feel free to contribute or reach out!

🔗 LinkedIn: *Prosenjit Majumder* [LinkedIn Profile](https://www.linkedin.com/in/prosenjitmajumder) 

📧 Email: prosenjitmajumder500@gmail.com
