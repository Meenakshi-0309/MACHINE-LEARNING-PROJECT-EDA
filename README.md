 Exploratory Data Analysis (EDA) on Titanic Dataset
 Objective"
The objective of this task is to perform Exploratory Data Analysis (EDA) on the Titanic dataset to uncover meaningful insights, identify data quality issues, and prepare for further machine learning tasks.

Dataset:
Dataset used: Titanic Dataset on Kaggle
Files used: titanic.csv (or similar)

Tools and Libraries
Python
Jupyter Notebook / Google Colab
Libraries:
pandas
numpy
matplotlib
seaborn
plotly (optional for interactive plots)

Tasks Performed
1. Data Loading and Cleaning
Loaded the dataset using pandas
Checked for missing values
Removed/replaced nulls (e.g., dropped 'Cabin', filled 'Age' with median)
2. Descriptive Statistics
Used .describe() to get mean, median, standard deviation, etc.
Counted unique values in categorical columns
3. Visualizations
Histograms to understand distribution of numerical features
Boxplots to detect outliers
Countplots for categorical features
Heatmap for correlation matrix
Pairplots for visualizing pairwise relationships
4. Feature-level Inferences
Gender and class significantly influenced survival rate
Outliers present in fare and age

 Key Insights:
Females had a higher chance of survival
1st class passengers were more likely to survive
Children (lower age) had slightly higher survival rate
Strong correlation found between Pclass and Fare


Certain features like ‘Pclass’ and ‘Embarked’ show interesting trends

