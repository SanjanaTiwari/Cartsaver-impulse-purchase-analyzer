#  CartSaver – Impulse Purchase Pattern Analyzer

This project explores and visualizes **impulse purchase behavior** in online grocery stores. Using **Python (for EDA)** and **Power BI (for dashboarding)**, we uncover trends behind impulsive shopping based on time, category, gender, discounts, and more.

---

##  Project Structure

| File Name                          | Description                                                  |
|-----------------------------------|--------------------------------------------------------------|
| `CartSaver_ImpulsePurchaseData.csv` | Raw dataset with customer purchase records                  |
| `CartSaver_Cleaned.csv`           | Cleaned and processed dataset used for analysis              |
| `cartsaverEDA.ipynb`             | Python Jupyter Notebook for data cleaning and EDA            |
| `CartSaver_ImpulseDashboard.pbix`        | Final Power BI dashboard file                                |
| `dashboard.png`           | Screenshot of the Power BI dashboard                         |

---

##  Objective

To identify **patterns and trends in impulse purchases** and help online grocery businesses understand:
- Who makes impulse purchases?
- What products are frequently bought impulsively?
- When do most impulse purchases occur?
- How do discounts influence impulse buying?

---

##  Tools & Technologies Used

- **Python** (Pandas, Matplotlib, Seaborn)
- **Jupyter Notebook**
- **Power BI Desktop**
- **Excel** (basic cleaning)
- *(Optional: MySQL for storing & querying data)*

---

##  Exploratory Data Analysis (EDA)

Conducted in `CartSaver_EDA.ipynb`:
- Checked for missing values and duplicates
- Extracted features: `Hour`, `Weekday`, `Is_Impulse`, etc.
- Created visualizations to explore:
  - Impulse purchase ratios
  - Gender and age-wise behavior
  - Category and product frequency
  - Impact of discounts and time of day

---

##  Dashboard Overview

The **Power BI dashboard** presents:
- Pie chart: Impulse vs Non-Impulse purchases
- Bar charts: Top Products, Categories, Gender split
- Line chart: Purchases by Hour
- Cards: KPIs like Total Purchases, Impulse %  
- Slicers: Filter by `Is_Impulse`, `Product`, `Gender`, etc.


##  Key Insights

- Around **29%** of purchases were impulsive.
- **Evening hours (6–9 PM)** showed higher impulse activity.
- **Female shoppers** exhibited slightly more impulse buying.
- **Snacks and Beverages** were leading impulse categories.
- **Discounts** increased the likelihood of an impulse purchase.

---

##  How to Use This Project

### 1️⃣ Python EDA:
- Open `cartsaverEDA.ipynb` in Jupyter Notebook.
- Run cells step-by-step to see cleaning and analysis.

### 2️⃣ Power BI Dashboard:
- Open `CartSaver_ImpulseDashboard.pbix` in Power BI Desktop.
- Interact with filters, slicers, and charts for deeper exploration.

---

##  Possible Improvements

- Use machine learning to predict impulse purchase behavior.
- Deploy the dashboard using Power BI Service or Streamlit.
- Expand dataset to include time-series trends.

---

##  Author

**Sanjana Tiwari**  
Aspiring Data Analyst | Python & BI Enthusiast  

