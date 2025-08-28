Student Exam Score

I reviewed your notebook Student_Exam_Score.ipynb.
Here’s a summary of what it contains:

Libraries used: pandas, numpy, matplotlib, seaborn

Data loading: Reads Expanded_data_with_more_features.csv

Initial exploration:

Displays first rows (df.head())

Checks summary statistics (df.describe())

Info about dataset (df.info())

Missing values (df.isnull().sum())

Data cleaning: Drops an unnecessary column Unnamed: 0

Analysis & Visualizations:

Gender distribution → Count plot shows more females than males.

Parental education vs student performance → Higher parental education correlates with better scores in Math, Reading, and Writing.

Parental marital status vs student performance → Negligible effect on scores.

Boxplots of Math, Reading, and Writing scores → To detect outliers and spread of marks.

Ethnic group exploration → Extracts unique values for ethnic groups (further analysis likely follows).
