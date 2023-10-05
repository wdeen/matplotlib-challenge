# matplotlib-challenge
Module 5 Challenge (Matplotlib / Pandas / Jupyter Notebook) - Wassim Deen

# Summary of Challenge
- Create a Jupyter script solution to do the following:
    1. Prepare the Data
        - Merge datasets from separate csv files into one 'Complete' DataFrame
        - Display No. mice shown from the merged DataFrame
        - Find all duplicate mice based on the Mouse ID and Timepoint
        - Clean the DataFrame by dropping The mice with duplicates
        - Display No. mice shown from the cleaned DataFrame

    2. Generate Summary Statistics (using Groupby())
        - Calculate the mean of the tumor volume for each Drug Regimen
        - Calculate the median of the tumor volume for each Drug Regimen
        - Calculate the variance of the tumor volume for each Drug Regimen
        - Calculate the standard deviation of the tumor volume for each Drug Regimen
        - Calculate the standard error of mean (SEM) of the tumor volume for each Drug Regimen
        - Store all summary statistics in a new DataFrame

    3. Create Bar Charts and Pie Charts
        - Generate a bar plot showing total no. of timepoints for all mice tested per drug regimen (using Pandas)
        - Generate a bar plot showing total no. of timepoints for all mice tested per drug regimen (using Pyplot)
        - Generate a pie plot showing the distribution of female vs. male mice using Pandas (using Pandas) 
        - Generate a pie plot showing the distribution of female vs. male mice using Pandas (using Pyplot)

    4. Calculate Quartiles, Identify Outliers, and Create Box Plot
        - Using Groupby(), create a new DataFrame that has the last (max) Timepoint for each mouse ID; index in DataFrame is also reset
        - Retrieve the maximum Timepoint value for each Mouse ID
        - Create a list to store four treatment groups: Capomulin, Ramicane, Infubinol, and Ceftamin
        - Use 'for' loop to display the quartiles (Q1, Q2, Q3), interquartile range (IQR) and the outliers for each treatment group 
        - Generate a box plot showing the distribution of the final tumor volume for all the mice in each treatment group. (using Pyplot)         

    5. Create Line Plot and Scatter Plot
        - Generate a line plot that shows tumor volume vs. time point for a selected mouse ID treated with Capomulin (using Pyplot)
        - Generate a scatter plot that shows average tumor volume vs. mouse weight for the Capomulin regimen (using Pyplot)

    6. Calculate Correlation and Regression
        - Calculate Pearson Correlation Coefficient and Linear Regression model for mouse weight and average tumor volume for the Capomulin regimen (using SciPy)
        - Plot the Regression line on the same scatter plot generated from Part #5 (using Pyplot)        


# Contents
1. 'Resources' Folder
    - 'mouse_metadata.csv' (reference dataset)
    - 'study_results.csv' (reference dataset)

2. 'main.ipynb' Jupyter Solution Script

3. README File