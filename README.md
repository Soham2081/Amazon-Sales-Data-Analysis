# Amazon Sales Data Analysis | Python (Pandas, NumPy, Matplotlib, Seaborn)

## 📌 Project Overview
This project performs an in-depth **exploratory data analysis (EDA)** on Amazon product sales data to uncover pricing patterns, customer rating behavior, category distribution, and data quality insights.

The objective is to demonstrate how Python-based data analytics can be used to transform raw e-commerce data into **actionable business insights** that support pricing strategy, category planning, and customer experience optimization.

---

## 🧰 Tools & Technologies
- **Python**
- **Pandas** – Data manipulation & cleaning  
- **NumPy** – Numerical computations  
- **Matplotlib** – Data visualization  
- **Seaborn** – Statistical data visualization  
- **Jupyter Notebook**

---

## 📂 Dataset Information
- **Source:** Amazon Sales Dataset (Kaggle)
- **Data Type:** E-commerce product-level data
- **Key Attributes:**
  - Product category
  - Actual price & discounted price
  - Discount percentage
  - Customer ratings
  - Review metadata

The dataset was assessed for missing values, inconsistencies, and data type issues before analysis.

---

## 🔄 Data Cleaning & Preparation
- Handled missing and invalid values
- Converted price columns from currency strings to numeric format
- Transformed rating fields into numerical values
- Filtered and standardized categorical variables
- Verified dataset integrity before analysis

---

## 📊 Exploratory Data Analysis
The following analyses were performed:

### 🔹 Price Analysis
- Distribution of product prices
- Identification of low, mid, and premium price segments
- Impact of discounting on pricing spread

### 🔹 Rating Analysis
- Distribution of customer ratings
- Comparison of ratings across price ranges
- Relationship between pricing and customer satisfaction

### 🔹 Category-Level Insights
- Top product categories by volume
- Category dominance and concentration analysis
- Category-wise price and rating behavior

### 🔹 Correlation Analysis
- Correlation heatmap for numerical variables
- Identification of weak and strong relationships between key metrics

---

## 📈 Key Business Insights
- Most products are priced in the **low-to-mid range**, with fewer premium-priced items.
- Customer ratings are **consistently high**, typically between **3.5 and 4.5**, across categories.
- Product price shows a **weak correlation** with customer ratings, indicating that higher prices do not necessarily result in better customer satisfaction.
- Certain categories dominate the platform, highlighting key areas for inventory and marketing focus.
- The dataset exhibits strong data quality with minimal critical missing values.

---

## 💼 Business Impact
This analysis can help stakeholders:
- Optimize **pricing strategies** without compromising customer satisfaction
- Identify **high-performing product categories**
- Improve **category-level decision-making**
- Support data-driven planning for promotions and product positioning

---

## ⚠️ Limitations
- No time-series data available for trend or seasonality analysis
- Revenue and quantity sold are not explicitly provided
- Customer demographic data is unavailable

---

## 🚀 Future Enhancements
- Incorporate time-based sales data for trend analysis
- Perform sentiment analysis on customer reviews using NLP
- Build an interactive **Power BI dashboard** for executive reporting
- Apply predictive modeling to understand drivers of customer ratings
- Combine with external competitor or market datasets

---

## 📁 Repository Structure
