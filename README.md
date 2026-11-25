# EDA-TASK8-
# Student Performance Analysis – Exploratory Data Analysis (EDA)

## Project Overview
This project performs Exploratory Data Analysis (EDA) on the Students Performance dataset using Python. The main objective is to analyze students' academic performance in Mathematics, Reading, and Writing and understand the factors that influence their scores.

## Tools and Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Dataset Description
The dataset contains students' performance information, including:
- Gender
- Race/Ethnicity
- Parental Level of Education
- Lunch Type
- Test Preparation Course
- Math Score
- Reading Score
- Writing Score

## Steps Performed

### 1. Data Loading
Imported the required Python libraries and loaded the Students Performance dataset using Pandas.

### 2. Data Inspection
- Displayed the first five records.
- Checked dataset shape and information.
- Generated descriptive statistics.
- Checked column names and missing values.

### 3. Data Cleaning
- Converted categorical values into lowercase.
- Removed unnecessary spaces.
- Checked unique values in categorical columns.
- Checked for duplicate records.

### 4. Statistical Analysis
Calculated:
- Mean
- Median
- Standard Deviation
- First Quartile (Q1)
- Second Quartile (Q2)
- Third Quartile (Q3)

### 5. Feature Engineering
Created two new columns:
- **Total Marks:** Sum of Mathematics, Reading, and Writing scores.
- **Percentage:** Calculated students' overall percentage out of 300 marks.

### 6. Outlier Detection
Used the Interquartile Range (IQR) method to identify outliers in Mathematics, Reading, and Writing scores.

### 7. Data Visualization
Created the following visualizations:
- Bar Chart – Average Scores by Parental Education.
- Bar Chart – Average Scores by Lunch Type.
- Box Plot – Test Preparation Course vs Subject Scores.
- Scatter Plot – Mathematics vs Reading Scores.
- Scatter Plot – Mathematics vs Writing Scores.
- Scatter Plot – Reading vs Writing Scores.
- Heatmap – Correlation Between Subject Scores.

<img width="938" height="627" alt="Screenshot 2026-11-25 105132" src="https://github.com/user-attachments/assets/02bd6580-f3c5-4102-92f9-884d50b30f69" />
<img width="1086" height="635" alt="Screenshot 2026-11-25 105103" src="https://github.com/user-attachments/assets/b0579fed-9f28-41dc-be79-8db50a59f631" />
<img width="1320" height="632" alt="Screenshot 2026-11-25 105046" src="https://github.com/user-attachments/assets/8701b88d-caf0-49e2-8e6e-a4da955e94be" />
<img width="780" height="602" alt="Screenshot 2026-11-25 105319" src="https://github.com/user-attachments/assets/18e7a81f-be10-4220-b279-9872584b5c38" />
<img width="721" height="562" alt="Screenshot 2026-11-25 105230" src="https://github.com/user-attachments/assets/da19b66e-ff52-4934-8257-88ee2f4978d2" />
<img width="707" height="576" alt="Screenshot 2026-11-25 105250" src="https://github.com/user-attachments/assets/52aca81f-9a75-4b28-9212-2a2a251bccc0" />
<img width="712" height="577" alt="Screenshot 2026-11-25 105306" src="https://github.com/user-attachments/assets/cd5c1198-8a7c-42b1-90b7-5c2c0b1a10a2" />
<img width="862" height="638" alt="Screenshot 2026-11-25 105207" src="https://github.com/user-attachments/assets/10638ad4-17e3-4ff0-a8ae-46cd45c7c978" />
<img width="982" height="628" alt="Screenshot 2026-11-25 105147" src="https://github.com/user-attachments/assets/bb3712ae-ebed-4053-8700-73a3b1248af2" />


### 8. Data Export
Saved the processed dataset as:

`Student_Performance_Cleaned.csv`

## Project Outcome
This project helps understand students' academic performance through statistical analysis and visualization. It explores the relationship between parental education, lunch type, test preparation, and students' subject scores.

## Conclusion
Exploratory Data Analysis provides useful insights into student performance. By using Python libraries, the dataset can be cleaned, analyzed, and visualized effectively.

---
