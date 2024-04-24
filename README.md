This Python script conducts a data analysis project on student scores using the Pandas, NumPy, Matplotlib, and Seaborn libraries. 
Here's a breakdown of what each part does:

 a. Data Loading and Inspection:
        The script starts by importing necessary libraries and loads a dataset named "students_score.csv" into a Pandas DataFrame called df.
        It prints the first few rows of the DataFrame, its statistical summary, and information about its structure, including data types and missing values.

 b.  Data Cleaning:
        It drops the column named "Unnamed: 0", which seems to be an unnecessary index column.

 c.  Data Visualization and Analysis:
       1. Gender Distribution: It visualizes the distribution of genders using a count plot.
       2. Parent's Education vs. Student's Scores: It calculates the mean scores (Math, Reading, Writing) grouped by Parent's Education level and presents them in a heatmap.
       3. Parent's Marital Status vs. Student's Scores: It calculates the mean scores grouped by Parent's Marital Status and presents them in another heatmap.
       4. Outliers Detection: It uses boxplots to identify outliers in Math, Reading, and Writing scores.

 d.  Conclusions:
        The conclusions drawn from the analysis are:
          1. There are more female students than male students.
          2. Parent's education level positively impacts student scores.
          3. Parent's marital status has a negligible impact on student scores.
          4. There are outliers present in all categories of student scores.

Overall, this script provides a comprehensive analysis of student scores, including data loading, cleaning, visualization, analysis, and conclusion drawing.
