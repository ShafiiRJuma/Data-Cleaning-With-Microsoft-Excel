# Data Cleaning with Microsoft Excel
#### Dataset Source: 
Kaggle - Ask a Manager Salary Survey 2021
#### Project Objective: 
Practice data cleaning techniques in Microsoft Excel to prepare a dataset for analysis.

## Introduction
In my journey as a data analysis student, I’m focusing on developing strong data cleaning skills, as this is often one of the most challenging and crucial steps in the analysis process. While it may seem tedious, mastering data cleaning builds resilience and attention to detail, qualities that are essential for any data analyst. This project uses a dataset obtained from Kaggle, containing responses from various professionals regarding their annual salaries across industries. By cleaning and organizing this data, I aim to prepare it for effective analysis and ensure reliable results.

## About the Data
The dataset consists of 17 columns, covering key details such as age, industry, job title, annual salary, country, state (if in the U.S.), city, race, and gender. Each column provides important information that could influence analysis outcomes depending on the project's objectives.
![Raw Columns on The Ask a Manager Salary Survey 2021](https://github.com/ShafiiRJuma/Data-Cleaning-With-Microsoft-Excel/blob/main/DataCleaningColumn.jpg)
## Data Cleaning Process
To approach data cleaning systematically, I first established my objectives and identified the columns that would be most critical in my analysis. This helped to ensure that any changes to the data would align with my analytical goals.

## Project Objectives
1. Analyze Salary Trends Across Professions and Demographics: This objective required a focus on columns such as profession, annual salary, location (country, state, city), age, and race.
2. Assess the Impact of Experience on Salary: To explore this, I focused on the “Years of Experience” and “Annual Salary” columns.
3. Evaluate the Influence of Educational Level on Salary: Here, I prioritized the “Highest Level of Education” and “Annual Salary” columns.
With these objectives in place, I knew which columns required careful handling to avoid compromising the accuracy of the insights.

## Steps Taken
Backup Creation: I began by making a copy of the original dataset to ensure I had a backup in case of any errors. This step is crucial, especially in professional settings where datasets may not be easily replaceable.

Dataset Overview: With 28,088 rows, this dataset is substantial, and I carefully reviewed it to identify potential issues and areas that required cleaning.

### Duplicate Removal: 
I used Excel’s Remove Duplicates tool to check for any repeated data. Fortunately, no duplicates were present.

### Unnecessary Columns Removal: 
Based on my objectives, I identified and removed columns that were not relevant, including additional job context details and income descriptors that wouldn’t impact the main objectives. This decision ensured a cleaner dataset, focused on general job titles rather than specific sub-roles.

### Handling Blank Fields: 
I examined key columns for missing data and addressed them as follows:

#### Industry Column: 
For blank cells in the industry column, I matched job titles with likely industries based on common responses. For example, if a job title was “Software Developer” and the industry field was blank, I filled it with “Tech.”
#### Salary Column: 
Due to the complexity of estimating salaries accurately, I decided to remove rows with missing salary values.
#### Job Title Column: 
I left blank cells in the job title column as they didn’t significantly impact the analysis.
#### Age Column: 
No blank cells were found, and no further cleaning was needed here.
#### Standardizing Formats: 
I unified inconsistent entries, such as multiple abbreviations and spellings for "United States" (e.g., US, USA, United States of America) using the Find and Replace tool. I applied similar standardization to currency labels.

### Outlier Detection: 
I reviewed the salary column for unrealistic values that could skew results, such as very low annual incomes (e.g., $17). Outliers like these were either corrected if a clear pattern existed or removed if they appeared inaccurate.

### Filtering Unwanted Rows: 
Rows containing “Student” as a job title were removed since the project focused on professional income trends, not those of students.

### Currency Conversion: 
Some salaries were listed in various currencies. I converted all non-USD currencies to USD to maintain consistency. This step involved applying exchange rates and ensured comparability across rows.

## Final Remarks
Through these data cleaning steps, I was able to prepare a structured, reliable dataset ready for analysis. This project has underscored the importance of data cleaning in ensuring accuracy and insight, which are essential in any data analysis project. With a clean dataset, I can now confidently move forward to explore trends, conduct analysis, and generate visualizations that will provide meaningful insights.
