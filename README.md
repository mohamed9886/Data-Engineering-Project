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
* **Intelligently handled missing values by mathematically deriving missing `Unit_Price` and `Sales` data from the `Tax` and `Quantity` columns.**
* **Standardized string formatting across all text columns (stripped whitespace, applied Title Case).**




**Satisfaction Rule:**

`Rating >= 7 → Satisfied Else  → Not Satisfied`

---

## 📊 Business Analysis

### 1. Total Revenue

**Result:**

Total Revenue is : 325,895.23 EGP

---

### 2. Revenue by City

**Highest Revenue City:**

Best selling city is : **Naypyitaw** with revenue of 111745.7945 EGP

**Result:**

| City | Revenue (EGP) |
| :--- | :--- |
| **Naypyitaw** | **111,745.79**|
| Mandalay| 106,602.33 |
| Yangon    | 107,547.09 |

---

### 3. Profit by Branch

**Most Profitable Branch:**

Best selling Branch is : **Giza** with profit of 5265.1765 EGP

**Result:**
Branch profit 
Branch
Alex     5057.1605
Cairo    5057.0320
Giza     5265.1765

| Branch | Profit (EGP) |
| :--- | :--- |
| **Giza** | **5,265.1765**|
| Alex| 5,057.16 |
| Cairo | 5,057.03 |

---

### 4. Revenue and Profit by Product Category

**Top-Performing Category:**

Best profit Product Line is : **Food And Beverages** with profit of 2673.564 EGP

Best revenue Product Line is : **Food And Beverages** with profit of 56562.06 EGP

**Result:**
| Product Category | Total Revenue (EGP) | Total Profit (EGP) |
| :--- | :--- | :--- |
| **Food and Beverages** | **56,562.06** | **2,673.56** |
| Sports and Travel | 55,754.11 | 2,624.90 |
| Electronic Accessories | 54,738.06 | 2,587.50 |
| Fashion Accessories | 54,731.85 | 2,586.00 |
| Home and Lifestyle | 54,544.33 | 2,564.85 |
| Health and Beauty | 49,564.83 | 2,342.56 |

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
![alt text](image.png)
