<h1>📌 Assignment 5 – Data Cleaning & Preprocessing</h1>

<h2>🎯 Objective</h2>
<p>
Ensure <b>data accuracy and consistency</b> by cleaning and transforming raw internship/job posting datasets into a structured format ready for <b>analysis and visualization</b>.
</p>

<hr>

<h2>📊 Dataset Overview</h2>
<p>The dataset consisted of internship/job postings with the following details:</p>
<ul>
  <li><b>Job Title</b></li>
  <li><b>Job Type</b></li>
  <li><b>Company Name</b></li>
  <li><b>Location</b> (City, State)</li>
  <li><b>Stipend</b></li>
  <li><b>Duration</b></li>
  <li><b>Number of Openings</b></li>
  <li><b>Dates</b> (Posted Date, Start Date, Last Date to Apply)</li>
</ul>

<p><b>Issues Identified:</b></p>
<ul>
  <li>Missing values across multiple columns</li>
  <li>Inconsistent formats in date and stipend fields</li>
  <li>Duplicate records</li>
  <li>Text fields mixed with numerical data (e.g., <code>"10000 /month"</code>)</li>
</ul>

<hr>

<h2>🔧 Data Cleaning & Preprocessing Steps</h2>
<ul>
  <li>🗑️ Dropped unnecessary index column and removed duplicates</li>
  <li>🔄 Handled missing values:
    <ul>
      <li><code>"Unknown"</code> or <code>"No Info"</code> for categorical/text fields</li>
      <li>Median values for numerical fields</li>
    </ul>
  </li>
  <li>📅 Converted date columns into proper datetime format</li>
  <li>💰 Extracted numeric stipend values from text (<code>"10000 /month"</code> → <code>10000</code>)</li>
  <li>⏳ Standardized internship duration and openings into numeric form</li>
  <li>🚀 Created a flag for <b>Immediate Start</b> internships</li>
  <li>💾 Saved the final dataset as <b>final_cleaned_internships.csv</b></li>
</ul>

<hr>

<h2>🛠️ Tools & Technologies</h2>
<ul>
  <li><b>Python</b> – Data preprocessing</li>
  <li><b>Pandas, NumPy</b> – Data cleaning & transformation</li>
  <li><b>Google Colab</b> – Development environment</li>
  <li><b>Power BI</b> – For visualization (next step after cleaning)</li>
</ul>

<hr>

<h2>✅ Outcome</h2>
<ul>
  <li>A <b>cleaned and structured dataset</b> ready for analysis</li>
  <li>Removed noise and inconsistencies → <b>more accurate insights</b></li>
  <li>Prepared for use in <b>Power BI dashboards</b> and <b>Machine Learning models</b></li>
</ul>

<hr>

<h2>📂 Files</h2>
<ul>
  <li><code>AICK_internship_data.csv</code> → Original dataset</li>
  <li><code>final_cleaned_internships.csv</code> → Cleaned dataset (processed)</li>
  <li><code>notebooks/assignment5_cleaning.ipynb</code> → Code used for preprocessing</li>
</ul>

<hr>
