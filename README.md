# 🎓 School Application Data Visualization (Python Project, UT Dallas)

A Python-based data analysis and visualization project that models school applications using Object-Oriented Programming (OOP) and generates insights with Pandas and Matplotlib. This project demonstrates clean class design, data processing, visualization techniques, and handling of real-world issues like missing data.

---

## 📘 Project Overview

This project builds a modular school application framework to simulate university admissions, followed by data processing and visualization using Pandas, Matplotlib, and Seaborn. The dataset consists of 10,000 application records across three universities: Wharton, Caltech, and Yale.

---

## 🛠️ Key Features

- ✅ OOP design with inheritance for school applications  
- ✅ Data serialization/deserialization using `pickle`  
- ✅ CSV export and manipulation using `pandas`  
- ✅ Visualization using `matplotlib` and `seaborn`  
- ✅ Missing value treatment using mode/mean imputation  
- ✅ Analytical charts: bar, line, histogram, scatter, boxplot, pie, and heatmap  

---

## 🧱 Object-Oriented Structure

- **Base Class**: `SchoolApplication`
- **Subclasses**: `StemSchoolApplication`, `NonStemSchoolApplication`
- **School Specific Classes**: `Caltech`, `Wharton`, `Yale`

Each class instance contains attributes like date, rating, tuition_fee, and acceptance_rate.

---

## 🧹 Data Cleaning

- Filled missing **categorical values** (e.g., rating, date) using **mode**
- Filled missing **numerical values** (e.g., tuition_fee, acceptance_rate) using **mean**
- Ensured complete data integrity before visualization

---

## 📊 Visualizations

1. **Bar Charts**:  
   - Course distribution  
   - STEM vs non-STEM applications  

2. **Box Plots**:  
   - Acceptance rates across Wharton, Caltech, Yale  
   - Tuition fee distribution  

3. **Line Graphs**:  
   - Student count per course  
   - Student ratings per school  

4. **Scatter Plot**:  
   - Acceptance rate vs Rating  

5. **Histograms**:  
   - Tuition fee ranges  
   - Rating distribution by school  

6. **Pie Chart**:  
   - Application distribution across Caltech, Wharton, Yale  

7. **Heatmap**:  
   - Acceptance rate by course and rating using `seaborn`  
