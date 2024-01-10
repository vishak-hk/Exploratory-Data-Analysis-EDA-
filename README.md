# Titanic Dataset Exploratory Data Analysis (EDA)

## Overview:
This repository contains exploratory data analysis (EDA) on the Titanic dataset, focusing on understanding and visualizing various aspects of the passengers' information. The analysis is performed using Python and popular data analysis libraries.

## Dataset Information:
The dataset includes information about Titanic passengers, such as their Pclass (class), Age, Sex, Fare, and Survival status.

## Analysis Steps:

1. Identifying Missing Values:

2. The dataset is examined to identify and handle missing values.
describe() Method:

3. A summary of the dataset is generated using the describe() method, providing insights into numerical features.
Numeric Column Exploration:

4. The range of values for each numeric column is analyzed, with a focus on detecting outliers.
Grouping by Class and Calculating Mean Fare:

5. Utilizing the groupby() method, the mean fare for each passenger class (Pclass) is calculated.
Frequency Count using value_counts():

6. The value_counts() method is applied to obtain the frequency count of specific features in the dataset.
Creating AgeRange Column:

7. A new column, "AgeRange," is added to categorize passengers into "Child," "Teen," "Adult," and "Senior" age groups.
Pivot Table for Survival Rate:

8. A pivot table is created using the pivot_table() method, displaying the survival rate based on Sex, Pclass, and AgeRange.
Bar Chart for Age Ranges:

9. A bar chart illustrates the total number of passengers in each age range.
Scatter Plot for Age and Fare:

10. A scatter plot is generated to visualize the relationship between age and fare, with points colored based on the passengers' survival status.


## Usage:

- Clone the repository.
- Install required Python libraries using pip install -r requirements.txt.
- Run the Jupyter notebook (Titanic_Exploratory_Data_Analysis.ipynb) for detailed analysis and visualizations.
