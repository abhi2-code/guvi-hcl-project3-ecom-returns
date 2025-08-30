# 📊 GUVI-HCL: Project 3 – E-Commerce Orders & Returns Analytics

## 🛠️ Tools Used

* Google Colab (Python: Pandas, Matplotlib, NumPy)
* Tableau Public (Desktop Edition)
* Microsoft Excel / CSV

---

## 📂 Project Description

**E-Commerce Orders & Returns Analytics** is a data analytics and visualization project designed to help businesses understand customer orders, seller performance, and product return behavior.

Built as part of the **GUVI-HCL Data Analytics Program**, this project focuses on:

* Tracking overall order and return trends
* Monitoring seller and state-level performance
* Identifying categories with high return rates
* Measuring on-time delivery against SLA targets

The project combines **Python-based data preprocessing** with **Tableau dashboards** to deliver interactive insights.

---

## 📁 Repository Structure

```
/guvi-hcl-project3-ecom-returns
│── E-Commerce Orders & Returns Dashboard.twbx   # Tableau packaged workbook
│── guvi_hcl_project3-20250830T070525Z-1-001.zip # Contains raw data, processed data, notebooks, and figures
│── README.md                                    # Project documentation
```

---

## ⚙️ How to Run the Project

### 1. Data Preprocessing (inside ZIP)

* Open `/notebooks/01_prep_ecom.ipynb` in Google Colab
* Generates processed dataset (`fact_orders.csv`)

### 2. Exploratory Data Analysis (inside ZIP)

* Open `/notebooks/02_eda.ipynb`
* Produces plots saved in `/figures/`

### 3. Tableau Dashboard

* Open `E-Commerce Orders & Returns Dashboard.twbx` in Tableau Public
* Explore KPIs, weekly trends, state and seller performance, and category return insights

---

## ✅ Features Implemented

* 📊 **KPI Cards** – Orders, GMV, Return Rate, On-time %, AOV
* 📈 **Trend Analysis** – Weekly Orders vs Returns
* 🛍️ **Category Insights** – Return Rate by Category
* 🌍 **State Performance** – Orders, On-time %, Return Rates
* 🏪 **Seller Analysis** – Top 10 Sellers by Return Rate
* 🧩 **Filters** – Interactive filters (Week, Category, State)

---

## 🧠 Insights & Interpretation

* Clothing has the highest return rate (\~12.3%)
* Uttar Pradesh & Delhi lead in total orders
* Seller\_20 shows the highest return % → needs monitoring
* On-time delivery is \~50%, showing logistics inefficiency
* AOV \~ ₹5,019 → mid-range products dominate sales

---

## ⚖️ Ethical & Bias Considerations

* Dataset is **synthetic** for learning, not real customer data
* Assumes static SLA (5 days) → real SLA may differ
* Returns assumed fully logged → real-world returns may be under-reported

---

## 📸 Dashboard Preview

* KPI Overview
* Weekly Orders vs Returns
* Category Return Rates
* State Performance
* Seller Performance

---

## 👨‍💻 Author

**Abhinav Tiwari**

---

## 📬 Contact

For queries, feedback, or collaboration, please connect via GitHub.

---

