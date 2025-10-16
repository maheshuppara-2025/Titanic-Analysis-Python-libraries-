# Titanic Data Analysis Using Python

## Table of Contents
- [Project Overview](#project-overview)
- [Objectives](#objectives)
- [Dataset Information](#dataset-information)
- [Tools and Libraries Used](#tools-and-libraries-used)
- [Data Cleaning and Preparation](#data-cleaning-and-preparation)
- [Data Analysis](#data-analysis)
- [Key Insights](#key-insights)
- [Conclusion](#conclusion)
- [Author](#author)

---

## Project Overview
The purpose of this project is to analyze the **Titanic dataset** and understand the factors that influenced the survival of passengers during the tragic shipwreck.  
Using Python, the dataset was cleaned, structured, and analyzed to identify patterns and insights related to passenger demographics, travel class, and survival outcomes.

---

## Objectives
- Clean and preprocess the Titanic dataset for accurate analysis.  
- Identify and handle missing, duplicate, and invalid data.  
- Explore relationships between passenger features such as gender, class, fare, and survival rate.  
- Perform data visualization to understand survival patterns.  
- Derive key insights about the survival trends based on passenger categories.

---

## Dataset Information
The dataset (`titanic.csv`) contains details of passengers including:
- Passenger ID  
- Name  
- Gender  
- Age  
- Passenger Class (Pclass)  
- Ticket Number  
- Fare  
- Cabin  
- Embarked (Port of Embarkation)  
- Survival Status  

Each record represents one passenger, with various attributes describing their travel and survival information.

---

## Tools and Libraries Used
- **Python**
- **Pandas** – data manipulation and cleaning  
- **NumPy** – numerical operations  
- **Matplotlib / Seaborn** – data visualization  
- **Jupyter Notebook** – code execution and analysis  

---

## Data Cleaning and Preparation
The following steps were performed to clean and prepare the Titanic dataset:

1. **Removed duplicate entries** using the `drop_duplicates()` method.  
2. **Handled missing values** in columns such as `Age`, `Fare`, and `Embarked` using mean or mode imputation.  
3. **Dropped irrelevant columns** like `Cabin` due to excessive missing data.  
4. **Checked data types** and converted incorrect ones (e.g., ensuring `Age` and `Fare` are numeric).  
5. **Created new feature** `Age_Category` to group passengers as *Child*, *Teen*, *Adult*, or *Senior*.  
6. **Sorted data** based on ticket numbers to maintain consistency.  

---

## Data Analysis
After data cleaning and transformation, several analyses were performed:

- **Survival Rate by Gender:**  
  Compared male and female survival percentages using visualizations.  

- **Survival Rate by Class:**  
  Analyzed how passenger class (1st, 2nd, 3rd) impacted chances of survival.  

- **Age and Fare Distribution:**  
  Visualized the spread of age and fare among survivors and non-survivors.  

- **Embarkation Port Analysis:**  
  Explored how the port of embarkation influenced survival outcomes.  

- **Feature Relationships:**  
  Used heatmaps and bar charts to study correlations among important attributes.  

---

## Key Insights
- **Women and children** had higher survival rates compared to men.  
- **First-class passengers** had better survival chances than those in second or third class.  
- **Fare price** was positively correlated with survival, indicating that wealthier passengers had higher chances.  
- **Embarked port 'C' (Cherbourg)** had a slightly higher proportion of survivors.  
- Missing and inconsistent data were successfully cleaned to improve analysis accuracy.

---

## Conclusion
This project provided a clear understanding of how data cleaning, preprocessing, and visualization can help uncover meaningful insights from real-world data.  
The analysis highlights important survival factors such as gender, class, and age, demonstrating how Python tools can be applied effectively in exploratory data analysis.

---

## Author
**Uppara Mahesh**  
Data Analyst | Python | Pandas | Matplotlib | Seaborn | Excel | Power BI
