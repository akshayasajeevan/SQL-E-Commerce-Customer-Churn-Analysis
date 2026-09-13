# E-Commerce Customer Churn Analysis

### SQL Data Cleaning, Transformation & Business Analysis

An end-to-end SQL data analysis project using **MySQL** to analyze e-commerce customer churn, customer behavior, satisfaction, purchasing patterns, payment preferences, complaints, and returns.

---

## 📌 Project Overview

Customer churn is a key challenge for e-commerce businesses. Understanding customer behavior and identifying patterns associated with churn can help businesses improve customer retention and customer experience.

This project uses SQL to **clean, transform, explore, and analyze** historical e-commerce customer data.

The analysis focuses on customer churn status, tenure, satisfaction, complaints, payment methods, order categories, coupon usage, purchasing behavior, warehouse-to-home distance, and customer returns.

---

## 💼 Business Problem

An e-commerce business wants to better understand its customer churn patterns and identify customer characteristics associated with churn.

The analysis aims to answer questions such as:

- How many customers have churned?
- What are the characteristics of churned customers?
- How are complaints related to churn?
- Which payment and order preferences are common among customers?
- How does customer satisfaction vary among customers who complained?
- How does warehouse-to-home distance relate to churn?
- Which customer groups show notable purchasing behavior?
- Which churned customers also have return and complaint activity?

---

## 🎯 Project Objectives

- Analyze churned and active customers.
- Identify customer behavior patterns.
- Analyze customer tenure and cashback.
- Examine the relationship between complaints and churn.
- Analyze payment and order preferences.
- Explore customer satisfaction patterns.
- Analyze coupon usage and order behavior.
- Segment customers based on warehouse-to-home distance.
- Analyze customer return and refund information.
- Generate insights that can support customer retention strategies.

---

## 🛠️ Tools & Technologies

- **MySQL**
- **MySQL Workbench**
- **SQL**

---

## 📊 Dataset Overview

The dataset contains customer-level e-commerce information, including:

| Category | Fields |
|---|---|
| Customer | Customer ID, Tenure, Gender, Marital Status |
| Location | City Tier, Warehouse-to-Home Distance |
| Engagement | Hours Spent on App, Number of Devices Registered |
| Purchasing | Order Count, Preferred Order Category, Order Amount Hike |
| Payments | Preferred Payment Mode |
| Customer Experience | Satisfaction Score, Complaints |
| Offers | Coupon Used |
| Returns | Return Date, Refund Amount |
| Value | Cashback Amount |

---

## 🧹 Data Cleaning

SQL was used to prepare the dataset for analysis.

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

👩‍💻 Author

Akshaya S

⭐ Thank you for visiting this project!
