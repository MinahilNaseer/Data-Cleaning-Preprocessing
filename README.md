📌 Assignment 5 – Data Cleaning & Preprocessing

🎯 Objective

Ensure data accuracy and consistency by cleaning and transforming raw internship/job posting datasets into a structured format ready for analysis and visualization.

📊 Dataset Overview

The dataset consisted of internship/job postings with the following details:

Job Title

Job Type

Company Name

Location (City, State)

Stipend

Duration

Number of Openings

Dates (Posted Date, Start Date, Last Date to Apply)

Issues Identified:

Missing values across multiple columns

Inconsistent formats in date and stipend fields

Duplicate records

Text fields mixed with numerical data (e.g., "10000 /month")

🔧 Data Cleaning & Preprocessing Steps

🗑️ Dropped unnecessary index column and removed duplicates

🔄 Handled missing values:

"Unknown" or "No Info" for categorical/text fields

Median values for numerical fields

📅 Converted date columns into proper datetime format

💰 Extracted numeric stipend values from text (e.g., "10000 /month" → 10000)

⏳ Standardized internship duration and openings into numeric form

🚀 Created a flag for Immediate Start internships

💾 Saved the final dataset as final_cleaned_internships.csv

🛠️ Tools & Technologies

Python – Data preprocessing

Pandas, NumPy – Data cleaning & transformation

Google Colab – Development environment

Power BI – For visualization (next step after cleaning)

✅ Outcome

A cleaned and structured dataset ready for analysis

Removed noise and inconsistencies → more accurate insights

Prepared for use in Power BI dashboards and Machine Learning models

📂 Files

AICK_internship_data.csv → Original dataset

final_cleaned_internships.csv → Cleaned dataset (processed)

notebooks/assignment5_cleaning.ipynb → Code used for preprocessing
