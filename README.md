# Customer Behaviour Dashboard

An interactive Power BI dashboard analysing grocery sales, customer purchasing behaviour, repeat orders, and payment preferences using a synthetic Zepto-inspired dataset.

> **Project type:** Data Analytics & Business Intelligence  
> **Author:** Talha Shaikh  
> **Primary tool:** Microsoft Power BI

---

## 📊 Project Overview
This repository contains an interactive Customer Behaviour Dashboard built with Power BI. It analyzes sales, customer purchasing patterns, product categories, and payment preferences using a synthetic, Zepto-inspired grocery dataset.

Business Purpose: Help grocery retailers understand customer buying habits, identify important customer segments, and make better decisions about sales and customer retention.

Understanding how customers shop can help businesses examine purchasing patterns, compare customer segments, and understand how sales are distributed across product categories and payment methods.

**Key Insights:**

- Total sales, orders, average customer rating, and repeat customer rate
- Customer purchase frequency and average orders per customer
- Sales and quantity purchased by age group
- Sales comparison across product categories and age groups
- Sales distribution by payment method
- Customer behaviour analysis by year, gender, age group, and product category

## 🛠️ Tools and Technologies

- **Microsoft Power BI** — dashboard design and interactive data exploration
- **DAX** — [ADD DETAILS OF MEASURES/CALCULATIONS USED, IF NEEDED]
- **Microsoft Excel** — workbook format used for the dataset
- **Kaggle** — dataset source

## 📁 Project Structure

Adjust this structure to match the files actually stored in the repository.

```text
Customer-Behaviour-Dashboard/
├── README.md
├── dashboard/
│   └── [ADD POWER BI FILE NAME].pbix
├── images/
│   ├── dashboard-overview.png
│   └── dashboard-details.png
├── data/
│   └── [ADD DATASET FILE OR SOURCE INSTRUCTIONS]
└── docs/
    └── [ADD DATA DICTIONARY OR PROJECT NOTES, IF AVAILABLE]
```

## 🗃️ Dataset and Data Source

This project uses a **synthetic, Zepto-inspired online grocery dataset sourced from Kaggle**. It is intended for learning and portfolio demonstration, not as a source of official Zepto business results.

The workbook used during development contains these data areas:

- **Customer:** customer information
- **Product:** product information
- **Order:** order records
- **Transaction:** transaction and payment information
- **Rating:** customer rating records
- **Delivery:** delivery records

**Dataset name:** Zepto_Dataset 
**Dataset link:** https://www.kaggle.com/datasets/ashishjangir6494/zepto-inspired-online-grocery-and-delivery-dataset  
**File format:** Excel workbook (`.xlsx`)  
**Date coverage:** January 2023 – December 2024

Refer to the original dataset page for its exact description, attribution requirements, and terms of use. Before uploading the raw workbook, verify that its licence permits redistribution and that any customer information is safe to publish.

## 🖼️ Dashboard Preview

### Dashboard Overview

<img width="883" height="499" alt="image" src="https://github.com/user-attachments/assets/762ce6bf-bdd2-4b0e-911e-0c40de5d3715" />

## ✨ Key Features

### Key Performance Indicators

| KPI | Displayed value | What it represents |
|---|---:|---|
| Total Sales | 36M | Overall sales value shown by the dashboard |
| Total Orders | 20K | Number of distinct orders shown |
| Average Rating | 3.88 | Average customer rating |
| Average Orders per Customer | 2.30 | Average orders per active customer |
| Repeat Customer Rate | 68.52% | Share of active customers who placed more than one order |

Values are rounded as displayed in the dashboard and may change when slicers are applied.

### Interactive Filters

The dashboard includes slicers for:

- **Year:** 2023 and 2024
- **Gender:** Female, Male, and Other
- **Age Group:** Adult, Middle-aged, Senior, and Young
- **Product Category:** Baby Care, Beverages, Dairy & Bakery, Fruits & Vegetables, Grocery & Staples, Household, Personal Care, and Snacks & Branded Foods

### Visualizations

| Visualization | Analytical purpose |
|---|---|
| Quantity Purchased by Age Group | Compares purchasing quantity across age groups |
| Customers by Number of Orders | Shows the number of customers in each order-frequency group |
| Sales by Age Group | Compares sales value across age groups |
| Sales by Category and Age Group | Compares category sales across age groups |
| Sales Distribution by Payment Method | Compares sales value by payment method |

## 🔎 Findings Visible in the Dashboard

The following observations describe the displayed dataset and should not be interpreted as official company results.

### Sales by age group

| Age group | Approximate sales |
|---|---:|
| Middle-aged | 17.4M |
| Adult | 12.1M |
| Young | 5.7M |
| Senior | 0.9M |

Middle-aged customers have the highest displayed sales, followed by adults.

### Sales by payment method

UPI is the largest segment in the payment-method treemap, at approximately 18M. Debit Card and Credit Card each contribute around 5M, Cash on Delivery around 4M, and Net Banking and Wallet around 2M each.

### Customer purchase frequency

The purchase-frequency chart shows the following customer counts in the displayed data:

| Number of orders | Number of customers |
|---:|---:|
| 1 | 2,733 |
| 2 | 2,719 |
| 3 | 1,799 |
| 4 | 924 |
| 5 | 351 |
| 6 | 112 |
| 7 | 36 |
| 8 | 6 |
| 9 | 1 |

Most customers are in the one- or two-order groups, and the customer count decreases at higher order frequencies.

### Repeat purchasing

The dashboard reports a repeat customer rate of **68.52%** and an average of **2.30 orders per active customer**. These metrics summarize observed purchasing patterns; they do not establish why customers return or predict future retention.

## 🚀 How to Explore the Dashboard

1. Open the Power BI report in Microsoft Power BI Desktop.
2. Review the KPI cards for the headline metrics.
3. Select a year, gender, age group, or product category from the slicers.
4. Compare how the displayed charts respond to the selected filters.
5. Use the age-group and category charts to compare sales patterns.
6. Explore the payment-method tree map to compare sales contributions.
7. Use **Order Volume by Customer Purchase-Frequency Group** to inspect the distribution of customers by purchase frequency.
8. Clear the slicers to return to the unfiltered view.

The filter behaviour depends on the report's data model and visual-interaction settings.

## 🔮 Future Improvements

- Add monthly sales and order trends if the required date fields support the analysis.
- Document the data model, relationships, and important DAX measures.
- Add a data-quality section describing limitations in the source data.
- Expand customer segmentation with additional validated analysis.
- Document data-source configuration and refresh steps to improve reproducibility.

These are possible future enhancements, not features currently claimed to be implemented.

## 👨‍💻 Author

**Talha Shaikh**

Data Science student interested in data analytics, business intelligence, and solving practical business problems with data.

* LinkedIn: [Talha Shaikh](https://www.linkedin.com/in/talha-shaikh-3847523b4/)
* GitHub: [Talha-shaikh77](https://github.com/Talha-shaikh77) 
* Email: talhashaikh078696@gmail.com

