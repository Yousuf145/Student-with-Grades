# Student-with-Grades
Student Performance Analysis with Pandas

## Project Overview
This project demonstrates data analysis and transformation using **Python and Pandas** on a student dataset.  
The goal is to explore student records, compute statistics, generate grades, and export a cleaned dataset for further use.

---

## Dataset
The dataset contains student academic information including:
- Student Name
- Class
- Gender
- Marks / Scores

The data is loaded from a CSV file and processed using the Pandas library.

---

## Tools & Technologies
- Python  
- Google Colab  
- Pandas  
- CSV file handling  

---

## Key Features & Tasks

### Data Loading & Exploration
- Load CSV data from Google Drive
- Inspect dataset structure using `.head()`, `.info()`, and `.describe()`

### Data Filtering & Selection
- Select single and multiple columns
- Filter students based on class and score conditions

### Data Transformation
- Add a `passed` column based on score conditions
- Rename columns for better readability
- Remove unnecessary columns
- Sort student records by marks

### Aggregation & Group Analysis
- Calculate average scores by class and gender
- Count students in each class
- Create pivot tables for performance comparison

### Grade Assignment
- Assign letter grades (`A`, `B`, `C`, `D`) using score ranges with `pd.cut()`

### Export Output
- Save the final processed dataset as:

