# E-Commerce Customer Churn Analysis

### SQL Data Cleaning, Transformation & Business Analysis

An end-to-end **MySQL data analysis project** focused on understanding customer churn, customer behavior, purchasing patterns, payment preferences, satisfaction, complaints, and customer returns in an e-commerce environment.

---

## 📌 Project Overview

Customer churn is an important challenge for e-commerce businesses. Understanding customer behavior and identifying patterns associated with churn can help businesses improve customer retention and customer experience.

This project uses **MySQL and SQL** to clean, transform, explore, and analyze historical e-commerce customer data.

The analysis covers customer tenure, churn status, satisfaction scores, complaints, payment preferences, order categories, coupon usage, purchasing behavior, warehouse-to-home distance, and customer returns.

---

## 💼 Business Problem

The project focuses on understanding customer churn patterns and identifying customer characteristics associated with customer attrition.

The analysis investigates:

- Churned and active customers
- Customer tenure and cashback
- Customer complaints
- Payment preferences
- Preferred order categories
- Customer satisfaction
- Coupon usage
- Purchasing behavior
- Warehouse-to-home distance
- Customer returns and refunds

---

## 🎯 Objectives

- Analyze churned and active customers.
- Identify customer behavior patterns.
- Analyze customer tenure and cashback.
- Examine complaints in relation to churn.
- Analyze payment and order preferences.
- Explore customer satisfaction.
- Analyze coupon usage and order behavior.
- Segment customers based on warehouse-to-home distance.
- Analyze customer return and refund information.
- Generate business insights from customer data.

---

## 🛠️ Tools & Technologies

- **MySQL**
- **MySQL Workbench**
- **SQL**

---

## 📊 Dataset

The project uses the e-commerce customer churn dataset provided with the module-end assignment.

The dataset contains customer information related to:

| Category | Examples |
|---|---|
| Customer | Customer ID, Tenure, Gender, Marital Status |
| Location | City Tier, Warehouse-to-Home Distance |
| Engagement | Hours Spent on App, Number of Devices Registered |
| Purchasing | Order Count, Preferred Order Category |
| Payments | Preferred Payment Mode |
| Customer Experience | Satisfaction Score, Complaints |
| Offers | Coupon Used |
| Churn | Churn Status |
| Value | Cashback Amount |

---

## 🧹 Data Cleaning

SQL was used to prepare the customer data for analysis.

### Missing Value Treatment

Mean imputation was applied to:

- `WarehouseToHome`
- `HourSpendOnApp`
- `OrderAmountHikeFromlastYear`
- `DaySinceLastOrder`

Mode imputation was applied to:

- `Tenure`
- `CouponUsed`
- `OrderCount`

### Outlier Handling

Records where:

```text
WarehouseToHome > 100
```

## 👩‍💻 Author

**Akshaya S**

B.Sc. Computer Science Graduate  
Aspiring Data Analyst

Thank you for visiting this project!
