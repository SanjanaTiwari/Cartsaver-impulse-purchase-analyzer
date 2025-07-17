#  CartSaver – Impulse Purchase Pattern Analyzer

Data analytics project that uncovers impulse buying behavior in online grocery shopping! This project analyzes how factors like age, gender, product category, and purchase time influence spontaneous purchases.

---

##  Objective

To explore and visualize impulse purchase trends among customers using real data analysis tools and build an interactive dashboard.

---

##  Tools & Technologies

- **Excel** – Data storing
-  **Python (Pandas, Seaborn)** – Data cleaning and EDA  
- **MySQL** – Data querying  
- **Power BI** – Dashboard and visualization  

---

##  Dashboard Overview

Power BI dashboard visualizes impulse buying behavior from multiple perspectives:

###  Key Visuals:

- **CustomerID vs Impulse Purchase**  
  - 71% (710) customers didn’t make impulse purchases  
  - 29% (290) customers made impulse purchases  

- **Gender vs Impulse Purchase**  
  - Impulse rate by gender:  
    - Male: 28.48%  
    - Female: 24.34%  
    - Other: 34.11%

- **Age Group vs Impulse Purchase**  
  - Highest impulse purchases seen in **26–35** and **36–45** groups  

- **Hour vs Impulse Purchase**  
  - Consistent purchases throughout the day  
  - Evening hours (6–9 PM) show higher impulse activity

- **Product vs Impulse Purchase**  
  - Top impulse products:  
    - Ice Cream (23.5%), Milk (21.86%), Bread (20.22%)

- **Category vs Impulse Purchase**  
  - Highest impulse rates in:  
    - Bakery (36.69%), Personal Care (31.01%), Dairy (29.93%)

---

##  Key Insights

- Nearly **1 in 3** customers made at least one impulse purchase.
- **Bakery and Personal Care** categories triggered the most impulsive buying.
- **Males and 'Other' gender** showed slightly higher impulse tendencies.
- **Evening hours** saw more impulse activity, indicating time-based buying behavior.

---

## Files in Repository

| File Name                          | Description                                         |
|-----------------------------------|-----------------------------------------------------|
| `CartSaver_ImpulsePurchaseData.csv` | Raw dataset with customer purchase records         |
| `CartSaver_Cleaned.csv`           | Cleaned and processed dataset used for analysis     |
| `cartsaverEDA.ipynb`              | Python Jupyter Notebook for data cleaning and EDA   |
| `CartSaver_ImpulseDashboard.pbix` | Final Power BI dashboard file                       |
| `dashboard.png`                   | Screenshot of the Power BI dashboard                |

---

##  How to Use

1. Clone this repository.
2. Open `cartsaverEDA.ipynb` in Jupyter Notebook for cleaning + EDA.
3. Open `CartSaver_ImpulseDashboard.pbix` in Power BI Desktop to view the dashboard.
4. Explore the visuals using filters like gender, age group, and category.

---

##  What I Learned

- Performing real-world EDA using **Python**
- Querying datasets with **MySQL**
- Building insightful dashboards using **Power BI**
- Understanding and interpreting consumer behavior trends

---


