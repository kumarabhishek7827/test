# 📊 Power BI Dashboard: Customer Transaction Analytics



## 🧭 Purpose
This dashboard provides a comprehensive analysis of customer transactions, card usage, merchant activity, and financial movement. It is designed to help business teams monitor performance, identify top customers, and explore transaction behavior across time and geography.

---

## 📂 Dataset Overview

| Column Name           | Description |
|-----------------------|-------------|
| `status`              | Transaction status (e.g., success, failed) |
| `card_present_flag`   | Indicates if card was physically present |
| `bpay_biller_code`    | Bill payment code |
| `account`             | Customer account number |
| `currency`            | Currency type |
| `long_lat`            | Customer location coordinates |
| `txn_description`     | Description of transaction type |
| `merchant_id`         | Unique merchant identifier |
| `merchant_code`       | Merchant category code |
| `first_name`          | Customer first name |
| `balance`             | Account balance post-transaction |
| `gender`              | Customer gender |
| `age`                 | Customer age |
| `merchant_suburb`     | Merchant location suburb |
| `merchant_state`      | Merchant state |
| `extraction`          | Date of transaction |
| `amount`              | Transaction amount |
| `transaction_id`      | Unique transaction identifier |
| `country`             | Country of transaction |
| `customer_id`         | Unique customer identifier |
| `merchant_long_lat`   | Merchant location coordinates |
| `movement`            | Type of financial movement (debit/credit) |

---

## 📊 Dashboard Components

### 🔹 KPI Cards
- **💰 Total Transaction Amount** → `SUM(amount)`
- **🏦 Total Account Balance** → `SUM(balance)`
- **🔢 Number of Transactions** → `COUNT(transaction_id)`
- **👤 Average Customer Age** → `AVERAGE(age)`

### 🔹 Filters
- **📅 Month & Day** → Extracted from `extraction` field
- **📍 Status & Movement** → Used for visual segmentation

### 🔹 Visualizations
- **📈 Pie Chart: Status Distribution** → Breakdown of `status`
- **📈 Pie Chart: Movement Distribution** → Breakdown of `movement`
- **🏆 Bar Chart: Top 10 Customers**
  - By `SUM(amount)` and `SUM(balance)`
  - Sorted descending
- **🔍 Drill-through Pages**
  - Click on customer or merchant to view detailed transaction history
  - Includes filters for date, merchant, and transaction type

---

## 🧠 Analytical Features

- **Cross-Verification**: Drill-through enables validation of aggregated metrics with raw transaction data.
- **Dynamic Filtering**: All visuals respond to slicers for month, day, status, and movement.
- **Customer Profiling**: Age, gender, and location data used to segment customer behavior.
- **Merchant Analysis**: Merchant location and category codes help identify high-performing vendors.

---

## 👥 Intended Audience
- Finance & Risk Analysts
- Customer Relationship Managers
- Business Intelligence Teams
- Operations & Compliance Officers

---

## 🚀 How to Use

1. **Open Dashboard** in Power BI Desktop or Service.
2. **Use Filters** to select specific timeframes or transaction types.
3. **Review KPI Cards** for high-level performance metrics.
4. **Explore Visuals** to identify trends and top customers.
5. **Drill Through** on customer or merchant to view detailed data.
6. **Export** visuals or data if needed for reporting.

---

## 🔐 Security & Privacy Notes
- Sensitive fields (`account`, `first_name`, `merchant_code`) should be masked or anonymized before sharing externally.
- Role-level security can be implemented to restrict access to customer-level data.

---

## 📎 Related Resources
- [Power BI Service Link] C:\Users\abhis\OneDrive\Documents\BANK INSIGHT


---

## 📬 Contact
For questions, feedback, or access requests, please contact:
**Dashboard Owner**: Abhishek kumar 
**Email**: abhisheksingh782795@gmail.com  
**Team**: Business Intelligence / Data Analytics

