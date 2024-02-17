# CA03
Overview

We built a Decision Tree Classifier model to predict income categories based on demographic data provided by the Census Bureau. The dataset contains salaries along with seven demographic variables, with the objective to classify individuals into two salary categories: > 50K and <=50K

**Data Source**

The dataset is sources from the following URL: https://raw.githubusercontent.com/ArinB/MSBA-CA-03-Decision-Trees/master/census_data.csv

**Features**

-	Target range: < 50K and <=50K
-	Number Instances (Rows) : 48842
-	Number of attributes (Columns): 7
-	Data Split: The dataset includes a column indicating rows for “Training Data” and “Testing Data”

**Library Imports:**
- numpy
- pandas
- matplotlib
- seaborn
- sklearn
- scipy
- IPython
- graphviz
- ssl
- time
-	Graphviz ( for tree visualization )

**Installation:**

Before running codes, make sure Python is installed, then use pip to install the requires libraries:
pip install pandas NumPy scikit-learn graphviz

**Usage and Results:**

Data Preprocessing: We start by performing a thorough data quality analysis, addressing missing values, outliers and executing necessary data transformations.

Model Building: We utilize “DecisionTreeClassifier from scikit-learn to construct our model.

Evaluation: We use the model’s performance through many metrics including accuracy, precision, recall, and the F1 score

Visualization: We visualize the most effective decision tree to understand the decision-making process.

Prediction: We used the trained model to make predications on new data

## Dataset features and bin values:
1. **hours_per_week_bin:** This column represents the number of hours worked per week, categorized into different bins:
* 0-30: Individuals who work 0-30 hours per week.
* 31-40: Individuals who work 31-40 hours per week.
* 41-50: Individuals who work 41-50 hours per week.
* 51-60: Individuals who work 51-60 hours per week.
* 61-70: Individuals who work 61-70 hours per week.
* 71-100: Individuals who work 71-100 hours per week.

2. **occupation_bin:** This column represents individuals' occupations, grouped into different categories:
* Low: Occupations with low-level responsibilities or earnings.
* Mid - Low: Occupations with moderate-low-level responsibilities or earnings.
* Mid: Occupations with moderate-level responsibilities or earnings.
* Mid - High: Occupations with moderate-high-level responsibilities or earnings.
* High: Occupations with high-level responsibilities or earnings.
  
3. **msr_bin:** This column represents median socioeconomic ranking, categorized into different groups:
* Low: Individuals with median socioeconomic ranking.
* Mid: Individuals with moderate median socioeconomic ranking.
* High: Individuals with high median socioeconomic ranking.
  
4. **capital_gl_bin:** This column represents information related to capital gains/losses, categorized into different groups:
* '= 0' : Individuals with zero capital gains.
* '< 0' : Individuals with capital losses.
* '> 0' : Individuals with capital gains.
  
6. **race_sex_bin:** This column represents race and gender-related information, grouped into different categories:
* Low: Individuals from demographic groups with low significance.
* Mid: Individuals from demographic groups with moderate significance.
* High: Individuals from demographic groups with high significance.
  
8. **education_num_bin:** This column represents the number of years of education completed, categorized into different bins:
* 0-8: Individuals with 0-8 years of education.
* 9-12: Individuals with 9-12 years of education.
* 13: Individuals with 13 years of education.
* 14: Individuals with 14 years of education.
* 15+: Individuals with 15 or more years of education.
  
9. **education_bin:** This column represents the highest level of education attained, grouped into different categories:
* Low: Individuals with low-level education.
* Mid: Individuals with moderate-level education below Bachelors degree.
* Bachelors: Individuals with a bachelor's degree.
* Masters: Individuals with a master's degree.
* High: Individuals with high-level education above Masters.
  
10. **workclass_bin:** This column represents individuals' work class or employment status, categorized into different groups:
* no income: Individuals with no income.
* income: Individuals with income.
  
11. **age_bin:** This column represents individuals' age groups, categorized into different bins:
* 0-25: Individuals aged 0-25 years.
* 26-30 : Individuals aged 26-30 years.
* 31-35 : Individuals aged 31-35 years.
* 36-40 : Individuals aged 36-40 years.
* 40-55: Individuals aged 40-55 years.
* 56-60: Individuals aged 56-60 years.
* 61-70: Individuals aged 61-70 years.
* 71-100: Individuals aged 71-100 years.
