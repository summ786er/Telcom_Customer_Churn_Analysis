# Telecom Customer Churn Analysis

## Project Overview

Customer churn is one of the most critical challenges for telecom companies. Losing customers directly impacts revenue and long-term growth.

This project performs an **Exploratory Data Analysis (EDA)** on telecom customer data to identify the key factors responsible for customer churn and provide actionable business insights to improve customer retention.

The analysis focuses on customer demographics, internet services, contract types, and revenue contribution to understand **why customers leave the telecom service**.

---

## Dataset

Dataset used: **Telecom Customer Churn Dataset**

The dataset contains customer information such as:

* Customer demographics
* Internet service type
* Contract type
* Monthly charges
* Total charges
* Churn status

Important fields include:

* `customerID`
* `gender`
* `SeniorCitizen`
* `InternetService`
* `Contract`
* `MonthlyCharges`
* `TotalCharges`
* `Churn`

---

## Tools & Technologies

The project was implemented using the following technologies:

* **Python**
* **Pandas** – Data manipulation and preprocessing
* **NumPy** – Numerical operations
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical visualizations
* **Jupyter Notebook**

---

## Project Workflow

### 1. Data Loading

The dataset was imported using Pandas and examined for structure and missing values.

### 2. Data Cleaning

Key preprocessing steps included:

* Handling missing values
* Converting data types
* Replacing blank values in `TotalCharges`
* Converting numeric flags to categorical labels

### 3. Exploratory Data Analysis

EDA was performed to analyze:

* Overall churn rate
* Gender-based churn distribution
* Senior citizen churn patterns
* Internet service churn behavior
* Contract-based customer segmentation
* Revenue and churn relationships

### 4. Visualization

Multiple visualizations were created to understand customer behavior:

* Bar charts
* Pie charts
* Correlation heatmap
* Customer segment comparisons
* Churn percentage analysis

---

## Key Business Insights

### 1. Overall Churn Rate

Approximately **26.5% of customers churned**, indicating a significant retention challenge.

### 2. Gender Analysis

Male and female customers show **almost identical churn patterns**, meaning gender is not a strong churn driver.

### 3. Senior Citizen Risk Segment

Senior citizens show a **much higher churn ratio (~42%)** compared to non-senior customers (~24%).
This group requires targeted customer support and tailored plans.

### 4. Internet Service Impact

Most churn is concentrated among users of:

* **Fiber Optic**
* **DSL**

These services account for **nearly 99% of total churn**, indicating strong competition in high-speed internet services.

### 5. Customer Contract Segmentation

Customers were categorized based on contract type:

| Customer Segment | Contract Type     |
| ---------------- | ----------------- |
| Platinum         | Two-Year Contract |
| Golden           | One-Year Contract |
| Silver           | Month-to-Month    |

Key findings:

* **Platinum customers** generate the highest revenue and show very low churn.
* **Silver customers** have the highest churn rate (~42%), making them the most critical segment for retention.
* **Golden customers** show moderate churn risk.

### 6. Revenue Risk

Silver customers contribute a large portion of churn-related revenue loss, making them the **highest priority segment for retention strategies**.

---

## Visualizations Included

The project includes multiple visualizations such as:

* Customer churn distribution
* Gender vs churn analysis
* Senior citizen churn comparison
* Internet service churn analysis
* Correlation heatmap
* Customer category revenue vs churn dashboard
* Charges-based churn segmentation

These visualizations help telecom companies better understand **customer behavior and churn drivers**.

---

## Business Recommendations

Based on the analysis, telecom companies should focus on the following strategies:

1. Improve service quality for **Fiber and DSL users**.
2. Introduce **senior-friendly plans and support services**.
3. Implement **customer retention programs for month-to-month customers**.
4. Provide loyalty incentives for long-term customers.
5. Improve service reliability to reduce churn caused by competition.

---

## Project Structure

```
Telecom_Customer_Churn_Analysis
│
├── Telecom_Customer_Churn_Analysis.ipynb
├── Teleco_Customer_Churn.csv
├── README.md
└── Visualizations
```

---

## Future Improvements

Possible future enhancements for this project include:

* Building a **Machine Learning churn prediction model**
* Applying classification algorithms such as:

  * Logistic Regression
  * Random Forest
  * XGBoost
* Creating an **interactive Power BI / Tableau dashboard**
* Deploying a churn prediction API

---

## Author

**Mahamad Irfan Hussen**

Data Analyst | Python | SQL | Data Visualization | Machine Learning

---

## Conclusion

This project demonstrates how **data analysis and visualization can identify churn patterns and support strategic decision-making** in the telecom industry. By focusing on high-risk customer segments, telecom companies can significantly improve customer retention and reduce revenue loss.
