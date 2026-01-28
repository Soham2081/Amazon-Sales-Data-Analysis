# Amazon Sales Data Analysis  
### Python (NumPy, Pandas, Matplotlib, Seaborn)

---

## 📌 Project Overview
This project performs **Exploratory Data Analysis (EDA)** on Amazon product sales data to uncover insights related to **pricing trends, customer ratings, category dominance, and data quality**.  
The goal is to demonstrate how Python-based data analysis can support **data-driven decision-making in e-commerce**.

---

## 🛠 Tools & Technologies
- Python  
- NumPy  
- Pandas  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## 📂 Dataset
- **Source:** Amazon Sales Dataset (Kaggle)  
- **Description:** Contains product-level information including prices, discounts, ratings, and categories.

---

## 🔍 Analysis Performed
- Data loading and preprocessing  
- Handling missing values and data cleaning  
- Price distribution analysis  
- Customer rating analysis  
- Category-level product analysis  
- Correlation analysis between numerical variables  

---

## 📊 Visualizations & Insights

The following visualizations were created to explore **data quality, relationships between variables, and key distribution patterns** in the dataset.

### 1️⃣ Correlation Matrix (Pearson)
This heatmap shows the **linear relationship** between numerical variables such as actual price, discounted price, and rating.  
It helps identify whether price directly influences customer ratings.

<img width="658" height="564" alt="Correlation Matrix (Pearson)" src="https://github.com/user-attachments/assets/33334cd3-a68f-4a61-9031-71bc3e9c51bb" />


---

### 2️⃣ Correlation Matrix (Spearman)
Spearman correlation captures **monotonic relationships**, making it more robust for non-linear trends and ranked data such as ratings.

<img width="658" height="564" alt="Correlation Matrix (Spearman)" src="https://github.com/user-attachments/assets/0b50f5f0-7f09-423f-9fe1-25c24c9a2893" />


---

### 3️⃣ Missing Values Heatmap
This visualization highlights the **presence and distribution of missing values** across all columns, helping assess data quality before analysis.

<img width="1725" height="944" alt="Missing Values Heatmap" src="https://github.com/user-attachments/assets/3afafee6-3f82-4a17-8390-a04935d341e7" />


---

### 4️⃣ Price Distribution Histogram
The histogram illustrates the **distribution of product prices**, revealing right-skewness and the dominance of low-to-mid priced products.

<img width="587" height="437" alt="Histogram" src="https://github.com/user-attachments/assets/38d7be27-6e70-4534-9705-8454a8f8d356" />


---

### 5️⃣ Percentage of Null Values
This bar plot shows the **percentage of missing values per column**, assisting in data cleaning and feature selection decisions.

<img width="1788" height="985" alt="Percentage Null Value Plot" src="https://github.com/user-attachments/assets/e0788f4e-ec48-457e-8db5-4ed9e1b70afb" />


---

### 6️⃣ Price vs Rating Scatter Plot
This scatter plot explores the relationship between **product price and customer rating**.  
The weak correlation indicates that higher-priced products do not necessarily receive better ratings.

<img width="574" height="437" alt="Scatter Plot" src="https://github.com/user-attachments/assets/25402857-ff2a-47d9-9520-2392053b431d" />


7️⃣ Discount, Price & Rating Correlation Heatmap

This heatmap visualizes the relationships between **discounted price, actual price, discount percentage, ratings, and rating count**, helping understand how pricing strategies relate to customer feedback.

<img width="658" height="550" alt="Heatmap" src="https://github.com/user-attachments/assets/ff48fa06-af0c-4ffa-a48f-db49c3dc8c4b" />



> These visual insights help e-commerce teams understand pricing behavior, customer sentiment, and data quality issues for better decision-making.

---

## 💡 Key Business Insights
- Product price has a **weak correlation** with customer ratings  
- Certain categories dominate the product listings  
- Ratings are influenced more by product experience than pricing  
- Data quality assessment is essential before advanced analytics  

---

## 📈 Conclusion
This project demonstrates how **Python-based EDA** can extract meaningful insights from raw e-commerce data.  
Such analysis helps businesses optimize pricing strategies, improve product offerings, and understand customer behavior.

---

## 🚀 Future Enhancements
- Category-wise revenue analysis  
- Sentiment analysis using product reviews  
- Time-series analysis of pricing trends  
- Predictive modeling for rating or price estimation  

---

## 👤 Author
**Soham Desai**  
Aspiring Data Analyst | Python | SQL | Power BI
