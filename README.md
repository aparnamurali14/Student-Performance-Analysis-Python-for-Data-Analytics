# Student-Performance-Analysis-Python-for-Data-Analytics

---

## 📌 Project Overview  

This project analyzes student academic performance using **Python, Pandas, and NumPy**.  

The dataset contains anonymized exam results collected by a State Education Board to understand how demographic, socio-economic, and academic preparation factors influence performance in:

- 📘 Mathematics  
- 📖 Reading  
- ✍️ Writing  

The goal is to generate **data-driven insights** that help improve teaching strategies, identify students who need support, and evaluate preparation programs.

---

## 📂 Dataset Information  

**Dataset Source:**  
🔗 Kaggle – *Students Performance in Exams*  

Dataset Characteristics:
- 1000 Rows  
- 8 Columns  

### Column Description

| Column Name | Description |
|-------------|------------|
| gender | Student gender (male / female) |
| race/ethnicity | Group classification (Group A–E) |
| parental level of education | Highest education level of parent(s) |
| lunch | Standard or free/reduced |
| test preparation course | Completed or none |
| math score | Mathematics score |
| reading score | Reading score |
| writing score | Writing score |

---

## 🎯 Project Objectives  

- Perform Exploratory Data Analysis (EDA)  
- Clean and validate data  
- Analyze performance trends  
- Measure impact of background factors  
- Categorize student achievement levels  
- Identify top and bottom performers  
- Provide actionable recommendations  

---

## 🛠 Technologies Used  

- Python  
- Pandas  
- NumPy  

---

## 📊 Analysis Tasks Performed  

### ✅ Task 1: Data Ingestion & Exploration  
- Loaded dataset using Pandas  
- Checked shape, columns, and data types  
- Generated statistical summary  

### ✅ Task 2: Data Cleaning  
- Checked for missing values  
- Confirmed dataset is clean  

### ✅ Task 3: Overall Performance  
- Calculated average scores  
- Identified highest and lowest scores  
- Created `Total score` column  

### ✅ Task 4: Gender-Based Analysis  
- Compared subject-wise performance by gender  
- Identified subject strengths  

### ✅ Task 5: Test Preparation Impact  
- Compared students who completed the course vs those who didn’t  
- Evaluated performance improvement  

### ✅ Task 6: Parental Education Influence  
- Grouped by parental education level  
- Identified highest & lowest performing groups  

### ✅ Task 7: Lunch Program Analysis  
- Compared performance by lunch type  
- Studied socio-economic impact  

### ✅ Task 8: Performance Categorization  
Created a new column:

| Total Score | Category |
|-------------|----------|
| ≥ 250 | Excellent |
| 200–249 | Good |
| < 200 | Needs Improvement |

### ✅ Task 9: Top & Bottom Performers  
- Identified Top 10 students  
- Identified Bottom 10 students  

### ✅ Task 10: Insights & Recommendations  
- Determined strongest influencing factors  
- Evaluated effectiveness of test preparation  
- Provided data-driven recommendations  

---

## 🔍 Key Insights  

- 📈 Students who completed the **test preparation course** scored significantly higher.  
- 🎓 Higher **parental education levels** correlate with better student performance.  
- 📖 Reading and Writing generally show higher averages compared to Math.  
- 🥗 Students with standard lunch performed better than free/reduced lunch students.  

---

## 💡 Recommendations  

1. Expand access to test preparation programs.  
2. Provide additional math support initiatives.  
3. Develop parental engagement programs to improve academic outcomes.  
4. Offer targeted support to students in the "Needs Improvement" category.  

---

## 📌 Conclusion

This project demonstrates how data analytics can transform educational decision-making.
Using Python-based EDA techniques, we extracted meaningful insights that can help improve academic performance at scale.

---

## 👩‍💻 Author

Aparna Murali

Python for Data Analytics – Week 18 Case Study

