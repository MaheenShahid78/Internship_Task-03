# 📊 Student Marks Analyzer (Using Pandas & NumPy)

## 📌 Task Description

This task is a simple **Student Marks Analyzer** developed using **Python, Pandas, and NumPy**. It demonstrates how to create, clean, analyze, and summarize a dataset containing students' marks in different subjects.

The dataset intentionally includes **missing values, duplicate rows, and invalid marks** to simulate real-world data cleaning and preprocessing tasks.

---

## 🎯 Objectives

- Create a student dataset
- Save the dataset as a CSV file
- Load the CSV file using Pandas
- Check missing values
- Remove duplicate rows
- Detect and fix invalid marks
- Handle missing values
- Calculate each student's average marks
- Find the highest and lowest scoring students
- Calculate class statistics using NumPy
- Assign Pass/Fail status
- Generate a summary report
- Sort students by average marks

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy

---

## 📂 Dataset

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

## 📋 Features

### 1. Create Dataset
- Creates a Pandas DataFrame containing student records.
- Saves the dataset as **Student Marks.csv**.

### 2. Load Dataset
- Reads the CSV file using Pandas.

### 3. Check Missing Values
- Counts the missing values present in each subject using `isnull().sum()`.

### 4. Remove Duplicate Records
- Detects duplicate rows.
- Removes duplicate records using `drop_duplicates()`.

### 5. Fix Invalid Marks
- Detects marks less than **0** or greater than **100**.
- Replaces invalid marks with the average of the valid marks for that subject.

### 6. Handle Missing Values
- Replaces missing values (`NaN`) with the average marks of each subject after the invalid marks have been corrected.

### 7. Convert Marks to Integer
- Converts all subject marks from float to integer using `astype(int)`.

### 8. Calculate Average Marks
- Calculates the average marks of every student.
- Stores the result in a new **Average** column.

### 9. Find Topper and Lowest Scorer
- Finds the student(s) with the highest average marks.
- Finds the student with the lowest average marks.

### 10. Statistical Analysis
Calculates the following statistics for every subject using NumPy:

- Mean
- Median
- Standard Deviation

### 11. Pass/Fail Result
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

## 📚 Libraries Used

```python
import pandas as pd
import numpy as np
```

---

## 📁 Project Structure

```
Internship_Task-03/
│── Student Marks.csv
│── Task 3.py
│── README.md
```

---

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/MaheenShahid78/Internship_Task-03.git
```

### 2. Navigate to the project folder

```bash
cd Internship_Task-03
```

### 3. Install the required libraries

```bash
pip install pandas numpy
```

### 4. Run the Python file

```bash
python "Task 3.py"
```

---

## 📊 Output

The program displays:

- Original dataset
- Missing values count
- Duplicate rows
- Cleaned dataset
- Student averages
- Highest scoring student(s)
- Lowest scoring student
- Mean, Median, and Standard Deviation
- Pass/Fail status
- Summary report
- Students sorted by average marks

---

## 💡 Concepts Used

- Python
- Pandas DataFrame
- NumPy
- CSV File Handling
- Missing Value Handling (`fillna()`)
- Duplicate Removal (`drop_duplicates()`)
- Data Cleaning
- Conditional Statements
- For Loops
- Statistical Analysis
- Sorting DataFrames (`sort_values()`)

---

## 👩‍💻 Author

**Maheen Shahid**

---

## 📧 Contact

Feel free to reach out if you have any questions or suggestions.

**Email:** maheenshahid0302@gmail.com
