# 🚗 Bright Motor Company Data Analysis

## 📌 Project Overview  
This project, developed as part of Capstone-1 by Harshit Arora (DS/AI-ML Batch-1), aims to analyze customer demand data for Bright Motor Company. The analysis leverages a dataset to provide insights into customer preferences and pricing trends, helping the company enhance customer experience and optimize its business strategy. The project includes exploratory data analysis (EDA), statistical evaluations, and actionable recommendations.

---

## 🧭 Table of Contents  
- [Problem Statement](#problem-statement)  
- [Dataset](#dataset)  
- [Project Structure](#project-structure)  
- [Methodology](#methodology)  
- [Results](#results)  
- [Conclusion](#conclusion)  
- [Author](#author)

---

## 🧩 Problem Statement  
Bright Motor Company seeks to analyze customer data to understand demand patterns, enabling them to improve customer experience. As a Data Scientist, the goal is to answer key questions through data analysis, such as identifying factors influencing vehicle purchases and optimizing pricing strategies to maintain service efficiency and customer satisfaction.

---

## 📊 Dataset  
The dataset (`bright_automotive_company.csv`) contains the following features:

- Age: Age of the individual in years  
- Gender: Gender of the individual (Male/Female)  
- Profession: Occupation or profession of the individual  
- Marital_status: Marital status (e.g., Married, Single)  
- Education: Educational qualification (Graduate, Post Graduate)  
- No_of_Dependents: Number of financial dependents  
- Personal_loan: Indicates if the individual has a personal loan (Yes/No)  
- House_loan: Indicates if the individual has a housing loan (Yes/No)  
- Partner_working: Indicates if the partner is employed (Yes/No)  
- Salary: Individual's salary or income  
- Partner_salary: Partner's salary or income (if applicable)  
- Total_salary: Combined salary of individual and partner  
- Price: Price of the product or service  
- Make: Type of automobile (e.g., SUV)

> ℹ️ Note: The dataset is loaded with UTF-8 encoding in the notebook.

---

## 🗂 Project Structure  
- 📓 `CAPSTONE_1_Harshit_Arora_Batch_1.ipynb`:  
  Main Jupyter notebook containing data loading, EDA, statistical analysis, and visualizations.

- 📁 `bright_automotive_company.csv`:  
  Dataset used for analysis (not included in the repository; users must provide their own copy).

- 📄 `README.md`:  
  This file, providing an overview of the project.

---

## 🧪 Methodology

### 📥 Data Loading  
- Imported the dataset and verified the working directory

### 🔍 Exploratory Data Analysis (EDA)  
- Performed initial inspection with `.head()` to view top records  
- Explored basic distributions and checked data types  

### 📊 Statistical Analysis  
- Calculated Skewness and Kurtosis to understand the distribution  
- Identified outliers using statistical thresholds  

### 📈 Visualization  
- Used libraries like Matplotlib and Seaborn  
- Created histograms and boxplots for key numeric features  

### 🧠 Observations  
- Derived business insights from pricing trends and anomalies

---

## ✅ Results

- 📈 Skewness = 0.6097 → Indicates moderate positive skew; most sales are lower-priced  
- 📏 Kurtosis = 0.6477 → Slightly leptokurtic; presence of extreme pricing values  
- 🔎 Outliers Detected = 27 → Likely high-value vehicles or special cases  
- 💡 Business Insight: Pricing distribution reflects diverse product line (cars, SUVs, trucks), aligning with Bright Motor Company’s customer-friendly, flexible pricing model  
- 🌟 Customer Rating: 4.7-star rating supports the effectiveness of their product strategy  

---

## 🧾 Conclusion  
The analysis reveals a pricing distribution with moderate skewness and significant outliers, suggesting a need for robust statistical techniques (e.g., log transformation) for future modeling. The findings support Bright Motor Company’s strategy of offering a wide range of vehicles, enhancing customer satisfaction through transparent and efficient transactions.

### 💡 Recommendations  
- Focus on high-value vehicle segments  
- Refine pricing models to handle outlier impact  
- Use findings to tailor promotional offers and target specific customer segments

---

## 👨‍💻 Author  
**Harshit Arora**  
B.Tech CSE Student, Sharda University
