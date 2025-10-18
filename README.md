# E-Commerce-Sales-Analysis
To analyze e-commerce sales data and uncover key insights that drive better business decisions. This project explores an e-commerce sales dataset to uncover the factors influencing total sales and profitability — focusing on product pricing, review scores, and category performance to reveal customer behavior and sales trends.

---

## 📌 Project Overview
The **E-Commerce Sales Analysis** project focuses on turning raw transactional data into valuable business insights.  
Using a real-world Kaggle dataset, I performed an **exploratory data analysis (EDA)** to understand how factors like **price, review score, review count, and category** affect total sales.  
The goal was to discover actionable insights that can help businesses improve product strategy, pricing, and customer satisfaction.

---

## 🧩 Dataset
**Source:** [E-Commerce Sales Dataset – Kaggle](https://www.kaggle.com/datasets/fahmidachowdhury/e-commerce-sales-analysis)  
**Key Columns:**  
`Product_ID`, `Category`, `Price`, `Review_Score`, `Review_Count`, `Total_Sales`, `Date`.

---

## 📊 Key Steps
1. **Data Cleaning & Preparation**  
   - Handled missing values and removed duplicates.  
   - Converted columns to proper data types.  

2. **Feature Engineering**  
   - Created new columns like `profit_margin`, `order_month`, and `order_year` for better analysis.  

3. **Correlation & Relationship Analysis (Seaborn)**  
   - Analyzed relationships:  
     - **Price vs Total Sales**  
     - **Review Score vs Sales**  
     - **Category-wise Total Sales**  
   - Created a **Correlation Heatmap** to visualize relationships between key features.  

4. **Outlier Detection & Handling**  
   - Used boxplots to detect outliers in `price` and `total_sales`.  
   - Removed the top 5% of extreme values for balanced analysis.  

---

## 💡 Key Insights
- **Moderate pricing leads to higher sales**, as extremely high or low-priced products perform less consistently.  
- **Higher review scores** positively influence total sales — customer trust drives purchase decisions.  
- **Top-performing categories** (e.g., *Electronics*, *Fashion*) contribute the most to overall revenue.  
- **Strong correlation** found between `review_count` and `total_sales`, showing that popular products sell more.  
- Removing extreme outliers improved the clarity of general sales patterns.  

---

## 🛠️ Tools & Libraries
- **Python**  
- **Pandas & NumPy** – data cleaning, manipulation, and computation  
- **Seaborn & Matplotlib** – visualization and trend analysis  
- **Jupyter Notebook / VS Code** – interactive data exploration  

---

## 📈 Results & Visuals
- Price vs Total Sales Scatter Plot  
- Review Score vs Sales Correlation  
- Category-wise Sales Bar Chart  
- Correlation Heatmap of Key Variables  
- Boxplots for Outlier Detection  

---

## 🧠 Conclusion
The analysis revealed that customer trust (reflected by reviews) and balanced pricing are the main drivers of successful product sales.  
E-commerce businesses can enhance profitability by optimizing product pricing and encouraging customer feedback to build credibility and engagement.

---

## 📜 License
This project is created for educational and portfolio purposes.  
You’re welcome to fork, learn, and adapt it with proper attribution.

---

### 💼 Author
**Khawaja Hizbullah**  
📧 khawajahizbullah@gmail.com | 🔗 [LinkedIn](https://www.linkedin.com/in/khawajahizbullah)
