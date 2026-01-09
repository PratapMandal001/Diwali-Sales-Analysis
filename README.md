# Diwali Sales Exploratory Data Analysis (EDA) 🛍️

## 📌 Project Overview
This project performs a comprehensive **Exploratory Data Analysis (EDA)** on Diwali sales data using **Python**.  
The objective is to analyze customer purchasing behavior and identify meaningful trends that can help retail businesses improve marketing strategies and enhance customer experience.

The analysis focuses on customer demographics, purchasing patterns, and product performance during the Diwali festival.

---

## 🛠️ Technologies Used
- **Python**
- **NumPy** – Numerical computations
- **Pandas** – Data cleaning and manipulation
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualizations
- **Jupyter Notebook**

---

## 📊 Business Questions Answered
- Who are the primary buyers (Gender & Age)?
- Which states contribute the most to total revenue?
- Which product categories generate the highest sales?
- How does marital status affect customer spending?
- Which occupations dominate customer purchases?

---

## 📈 Key Insights from Analysis
- **Gender**: Women are the primary buyers and have higher purchasing power than men.
- **Age Group**: The most active shoppers belong to the **26–35 age group**, especially females.
- **Geography**: The top three states contributing to sales are **Uttar Pradesh, Maharashtra, and Karnataka**.
- **Occupation**: Majority of buyers work in **IT, Healthcare, and Aviation** sectors.
- **Product Categories**:
  - Clothing has the highest number of orders.
  - Food category generates the **highest total revenue**.

---

## 🚀 Step-by-Step Implementation

### 1️⃣ Data Cleaning
- Removed null values from the **Amount** column
- Dropped unnecessary columns such as `Status` and `Unnamed1`

### 2️⃣ Data Type Conversion
- Converted **Amount** column from float to integer for better analysis

### 3️⃣ Exploratory Data Analysis
- Used **Countplots** and **Barplots** to visualize trends
- Applied **GroupBy operations** to analyze sales by:
  - Gender
  - Age Group
  - State
  - Occupation
  - Product Category

### 4️⃣ Final Conclusion
- Identified the **ideal customer profile**:
  - Married women
  - Age group: 26–35
  - Location: UP, Maharashtra, Karnataka
  - Occupation: IT / Healthcare / Aviation

---

## 📂 Project Structure
Diwali-Sales-EDA/
│── Diwali_Sales_Analysis.ipynb # Jupyter Notebook (Full Analysis)
│── Diwali_Sales_Data.csv # Dataset
│── README.md # Project Documentation


---

## ▶️ How to Run the Project

### 1️⃣ Install Required Libraries
```bash
pip install numpy pandas matplotlib seaborn

Run All Cells

Execute all cells to view analysis and visualizations
