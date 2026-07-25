# Student Marks Analyzer using Pandas and NumPy

## Overview

This project is a simple Student Marks Analyzer developed using **Python**, **Pandas**, and **NumPy**. It demonstrates how to create, clean, analyze, and summarize a dataset containing students' marks in different subjects.

The dataset intentionally includes missing values, duplicate records, and invalid marks to simulate real-world data cleaning and preprocessing.

---

## Objectives

- Create a student dataset
- Save the dataset as a CSV file
- Load the CSV file using Pandas
- Check missing values
- Remove duplicate rows
- Detect and fix invalid marks
- Handle missing values
- Calculate each student's average marks
- Find the highest and lowest scoring students
- Calculate subject-wise mean, median, and standard deviation using NumPy
- Assign Pass/Fail status
- Generate a summary report
- Sort students by average marks

---

## Technologies Used

- Python
- Pandas
- NumPy

---

## Dataset

The dataset contains **30 students** with marks in the following subjects:

- Computer
- English
- Maths
- Programming
- Discrete

The dataset intentionally contains:

- Missing values (`NaN`)
- Duplicate rows
- Invalid marks (greater than 100 and less than 0)

---

## Project Features

### 1. Create Dataset
- Creates a Pandas DataFrame containing student records.
- Saves the dataset as **Student Marks.csv**.

### 2. Load Dataset
- Reads the CSV file using Pandas.

### 3. Check Missing Values
- Counts missing values in each subject using `isnull().sum()`.

### 4. Remove Duplicate Records
- Detects duplicate rows.
- Removes duplicate records using `drop_duplicates()`.

### 5. Fix Invalid Marks
- Detects marks below **0** or above **100**.
- Replaces invalid marks with the average of valid marks for that subject.

### 6. Handle Missing Values
- Replaces missing values (`NaN`) with the subject average after invalid marks have been corrected.

### 7. Convert Marks to Integer
- Converts all subject marks from float to integer using `astype(int)`.

### 8. Calculate Average Marks
- Calculates the average marks of each student.
- Stores the result in a new **Average** column.

### 9. Find Topper and Lowest Scorer
- Finds the student(s) with the highest average.
- Finds the student with the lowest average.

### 10. Statistical Analysis
Calculates the following for each subject using NumPy:

- Mean
- Median
- Standard Deviation

### 11. Pass/Fail Status
- Students with an average of **40 or above** are marked as **Pass**.
- Students with an average below **40** are marked as **Fail**.

### 12. Summary Report
Displays:

- Total number of students
- Number of passed students
- Number of failed students
- Subject-wise class average

### 13. Sort Students
- Sorts students by average marks in descending order.

---

## Libraries Used

```python
import pandas as pd
import numpy as np
```

---

## Project Structure

```
Internship_Task-03/
│── Student Marks.csv
│── Task 3.py
│── README.md
```

---

## Getting Started

### Clone the repository

```bash
git clone https://github.com/MaheenShahid78/Internship_Task-03.git
```

### Navigate to the project directory

```bash
cd Internship_Task-03
```

### Install the required libraries

```bash
pip install pandas numpy
```

### Run the project

```bash
python "Task 3.py"
```

---

## Program Output

The program displays:

- Original dataset
- Missing values count
- Duplicate rows
- Cleaned dataset
- Student averages
- Highest scoring student(s)
- Lowest scoring student
- Subject-wise mean, median, and standard deviation
- Pass/Fail status
- Summary report
- Students sorted by average marks

---

## Concepts Used

- Python
- Pandas DataFrame
- NumPy
- CSV File Handling
- Data Cleaning
- Missing Value Handling
- Duplicate Removal
- Conditional Statements
- For Loops
- Statistical Analysis
- Data Sorting

---

## Author

**Maheen Shahid**

---

## Contact

If you have any questions or suggestions, feel free to reach out.

**Email:** maheenshahid0302@gmail.com
