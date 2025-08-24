Employee Data Analysis Project
📌 Overview

This project demonstrates data cleaning, analysis, and visualization in Python using Pandas and Matplotlib.
It starts with a raw dataset (advanced_employee_data.csv) containing employee information such as demographics, salaries, performance, and work patterns.
The dataset is cleaned, analyzed, and saved as cleaned_advanced_employee_data.csv.

📂 Files in this Repository

advanced_employee_data.csv → Raw dataset (messy, with missing/invalid values).

cleaned_advanced_employee_data.csv → Cleaned dataset after preprocessing.

Dataset.py → Main script for:

Data loading & inspection

Data cleaning (handling NaN, Inf, missing values)

Filtering and selection

Grouping & aggregation

Visualization (bar, pie, scatter plots)

Creating a new feature (Salary_per_YearExperience)

Exporting the cleaned dataset

pr.py → Script to read and explore the cleaned dataset.

🚀 How to Run

Clone the repository:

git clone https://github.com/your-username/employee-data-analysis.git
cd employee-data-analysis


Install required libraries:

pip install pandas matplotlib numpy


Run the main script:

python Dataset.py


Open the cleaned dataset:

python pr.py

📊 Key Analysis Performed

Average salary per department

Employee distribution by city

Scatter plot: Age vs. Salary

Pie chart: City-wise employee ratio

Top 3 employees with best salary-to-experience efficiency

🔮 Future Improvements

Add outlier detection and removal

Build interactive dashboards (Plotly / Power BI)

Apply Machine Learning (e.g., salary prediction, attrition risk)
