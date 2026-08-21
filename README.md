# Supermarket Sales Analysis

## 📌 Project Description

This project uses **Python and Pandas** to clean, prepare, and analyze supermarket sales data.

The dataset used in this project is:

`SuperMarket.csv`

The goal is to clean the data and answer business questions using the available sales and transaction information.

---

## 🛠️ Tools Used

* Python
* Pandas
* Matplotlib & Seaborn (Custom Dashboard UI)
---

## 🧹 Data Cleaning

The following data-cleaning steps were performed:

* Checked data types
* Checked missing values
* Checked duplicate records
* Renamed columns
* Removed unnecessary columns
* Corrected data types
* Sorted the data
* Create 3 columns (Day, Month, Year )
* Created the `Satisfaction` column based on the rating
**Intelligently handled missing values by mathematically deriving missing `Unit_Price` and `Sales` data from the `Tax` and `Quantity` columns.**
**Standardized string formatting across all text columns (stripped whitespace, applied Title Case).**




**Satisfaction Rule:**

`Rating >= 7 → Satisfied Else  → Not Satisfied`

---

## 📊 Business Analysis

### 1. Total Revenue

**Result:**

325,895.23 EGP

---

### 2. Revenue by City

**Highest Revenue City:**

Best selling city is : Naypyitaw with revenue of 111745.7945 EGP

**Result / Screenshot:**

city revenue 
City
Mandalay     106602.3390
Naypyitaw    111745.7945
Yangon       107547.0965

---

### 3. Profit by Branch

**Most Profitable Branch:**

Best selling Branch is : Giza with profit of 5265.1765 EGP

**Result / Screenshot:**
Branch profit 
Branch
Alex     5057.1605
Cairo    5057.0320
Giza     5265.1765

---

### 4. Revenue and Profit by Product Category

**Top-Performing Category:**

Best profit Product Line is : Food And Beverages with profit of 2673.564 EGP
Best revenue Product Line is : Food And Beverages with profit of 56562.06 EGP

**Result / Screenshot:**

Product          |          revenue
Product_Line
Electronic Accessories    54738.0555
Fashion Accessories       54731.8500
Food And Beverages        56562.0600
Health And Beauty         49564.8250
Home And Lifestyle        54544.3290
Sports And Travel         55754.1105
==============
Product profit
Product_Line
Electronic Accessories    2587.5015
Fashion Accessories       2585.9950
Food And Beverages        2673.5640
Health And Beauty         2342.5590
Home And Lifestyle        2564.8530
Sports And Travel         2624.8965


---

### 5. Spending by Customer Type

**Customer Type That Spends More:**
Member
**Total Spend:** 
192,623.25 EGP *(Compared to Normal customers at 133,271.99 EGP)*

---

### 6. Payment Method

**Most Popular Payment Method:**
E-Wallet (345 transactions)
Followed closely by Cash (344) and Credit Card (311)

---

### 7. Average Transaction Value

**Average Transaction Value:**

325.90 EGP

---

### 8. Customer Satisfaction by Branch

**Branch with the Highest Satisfaction:**

Alex (52.65% of customers satisfied)

---

### 9. Sales by Day and Month

**Highest Sales Day:**

Saturday (56,127.53 EGP)

**Highest Sales Month:**

January (117,123.21 EGP)

---

### 10. Overall Customer Satisfaction

**Overall Satisfaction Percentage:**
50.1%

---
