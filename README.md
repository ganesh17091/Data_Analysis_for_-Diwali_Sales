# 🪔 Diwali Sales Data Analysis

## 📖 Overview
This project analyzes **Diwali sales data** to understand customer purchasing behavior, identify top-selling product categories, and uncover insights that can help improve marketing strategies and boost sales during the festive season.

## 🎯 Objective
The main goal of this project is to:
- Analyze customer demographics and their spending patterns.
- Identify the states, occupations, and age groups contributing most to sales.
- Find top-performing product categories and products.
- Provide business insights to improve customer targeting and maximize revenue during Diwali.

## 📊 Dataset
The dataset contains sales transaction data of customers during Diwali.  
**Key columns include:**
- `User_ID` — Unique customer ID  
- `Gender` — Customer gender  
- `Age Group` — Age range of customers  
- `State` — Location of the customer  
- `Occupation` — Profession of the customer  
- `Product_Category` — Type of product purchased  
- `Orders` — Number of orders placed  
- `Amount` — Total amount spent  

## 🧹 Data Cleaning
- Removed unnecessary and duplicate columns.  
- Handled **missing or null values**.  
- Converted data types where necessary (e.g., `Amount` to numeric).  
- Verified dataset integrity and consistency.

## 🔍 Exploratory Data Analysis (EDA)
Performed a detailed analysis to understand:
- Gender-wise spending behavior.  
- Age group analysis and total spending per segment.  
- State-wise and occupation-wise contribution to total sales.  
- Most popular product categories and products.  
- Relationship between `Orders` and `Amount`.

## 📈 Visualization
Data visualization was done using:
- **Matplotlib**  
- **Seaborn**

These helped in generating clear bar plots, count plots, and distribution graphs to identify trends such as:
- Women customers, particularly those who are married, spend more during Diwali.  
- The **26–35 age group** contributes the most to total sales.  
- States like **Uttar Pradesh, Maharashtra, and Karnataka** lead in purchase volume.  
- **Electronics and Clothing** are among the most popular product categories.

## 💡 Conclusion
- **Married women aged 26–35 years** from **Uttar Pradesh, Maharashtra, and Karnataka** are the top spenders during Diwali.  
- **Electronics and clothing** dominate product sales.  
- Businesses can increase revenue by targeting this demographic segment through focused advertisements and discount offers during the Diwali season.

## 🛠️ Tools & Libraries Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

## 📁 Project Structure
```
📂 Diwali_Sales_Analysis/
│-- 📘 Diwali_Sales_Analysis.ipynb
│-- 📄 README.md
│-- 📊 data.csv  (optional, if dataset is included)
```

## ▶️ How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/Diwali_Sales_Analysis.git
   ```
2. Open the project folder:
   ```bash
   cd Diwali_Sales_Analysis
   ```
3. Install the required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
4. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
5. Open **`Diwali_Sales_Analysis.ipynb`** and run all cells.

---

⭐ **If you find this project helpful, consider giving it a star on GitHub!**
