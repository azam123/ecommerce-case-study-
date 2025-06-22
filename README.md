# 📊 E-commerce Marketing & Sales Case Study

## 📖 Business Story & Context

An e-commerce company operating across various product categories (e.g., Apparel, Bags, Office Supplies, Electronics) collected data for the year 2019 to evaluate and improve its marketing, customer acquisition, and retention strategies. The primary goal is to analyze the entire customer journey—from acquisition and transaction behavior to retention and customer lifetime value—and uncover actionable insights to enhance revenue and reduce churn.

## 🔍 Exploratory Data Analysis & Analytical Logic

### ✅ Data Preparation

* Combined five datasets: `Online_Sales.csv`, `Customers_Data.csv`, `Discount_Coupon.csv`, `Marketing_Spend.csv`, `Tax_Amount.csv`
* Parsed date fields and engineered key features: Month, Revenue, Discount, Tax, Net Revenue
* Merged data on keys: CustomerID, Product\_Category, Transaction\_Date

### 🔢 Metrics Computed

* Monthly acquisition & retention
* Net Revenue (Revenue + Delivery - Discount - Tax)
* Customer segments via RFM (Recency, Frequency, Monetary)
* Coupon effectiveness and AOV differences
* Marketing ROI by month
* Cohort-based retention & LTV

## 📈 Visualizations

* **Line Charts**: Monthly Revenue Trends, Acquisition, and Retention
* **Bar Charts**: Product category performance, RFM segment revenue
* **Heatmaps**: Retention by Cohort
* **Boxplots**: AOV by Coupon Usage, Delivery Tiers
* **Correlation Plots**: Revenue vs. Delivery Charges, Marketing Spend

## 💡 Insights & Recommendations

### Acquisition

* **High Months**: March, August
* **Low Months**: May, November
* *Strategy*: Time first-purchase discounts and Google Ads around low-acquisition months.

### Retention

* **Strong Cohorts**: March, July
* *Strategy*: Replicate product promotions and campaign timing of strong cohorts across the year.

### Revenue & Coupons

* **Returning customers** contributed 65% of revenue.
* **Coupon users** had lower AOV, but higher order frequency.
* *Strategy*: Use coupons to activate dormant users, not for every order.

### RFM Segmentation

* **Premium segment** (top 20%) accounted for 70% of revenue.
* *Strategy*: Early access and loyalty points for Premium; upsell emails for Gold.

### Marketing Spend ROI

* ROI was low in Feb and Nov despite high spend.
* *Strategy*: Reallocate budget toward June–August where spend-revenue ratio was optimal.

### Product & Delivery Pricing

* Apparel and Electronics performed best by volume.
* High delivery charges correlated negatively with order quantity.
* *Strategy*: Free delivery thresholds and bundling for higher AOV.

## 📁 Documentation & Reproducibility

* All code is in a Jupyter Notebook: `analysis.ipynb`
* Visuals embedded and saved in `plots/`
* Data files in `data/`
* `README.md` includes project summary, data schema, and analysis outline

## 📚 Repository Structure

```
Ecommerce-Case-Study/
├── data/                    # Input files (CSV/XLSX)
├── plots/                   # All visualizations
├── notebooks/
│   └── analysis.ipynb       # EDA + Modeling + Visuals
├── README.md
└── requirements.txt         # For reproducibility
```

> This project aligns analytics with real business impact—improving ROI, reducing churn, and optimizing discount strategies. The insights are actionable, scalable, and rooted in clear evidence from the data.
