# E-COMMERCE-GROUP-PROJECT
project for predicting whether a customer made a purchase or not.

# OBJECTIVES
- To analyze the distribution of purchase and non-purchase sessions in the dataset.
- To examine how bounce rates and exit rates influence purchasing behavior.
- To examine relationship between product-related page visits, PageValues, and purchasing behavior.
- To analyze the impact of visitor type on purchasing.


# DATA UNDERSTANDING
Dataset was sourced from kaggle.

Variables include revenue,page values,exit rates,bounce rates etc.

Target variable is revenue where:

          false-no purchase
          
          true-purchase occurred

# DATA CLEANING
Checked for missing values

Removed duplicate records

Prepared data for machine learning

# EXPLORATORY DATA ANALYSIS(EDA)
Purchase Distribution
<Figure size 640x480 with 1 Axes>

Bounce Rates Analysis
<Figure size 640x480 with 1 Axes>

PageValues Analysis
<Figure size 640x480 with 1 Axes>

## Tools Used for Visualization
- Matplotlib
- Seaborn
- Tableau 

# FINAL INSIGHTS
- Bounce Rates and Exit Rates are higher among non-buyers, showing that early exit reduce purchasing chances.
-  Returning visitors buy more often than new visitors, which shows that trust and familiarity increase purchases. 
- PageValues is very important because higher values usually mean the user is more likely to buy.  
- Buyers tend to visit more product-related pages, showing that deeper browsing increases purchase chances.

# MACHINE LEARNING
## MODEL USED
### * Random Forest
A Random Forest model was used because:
- It handles non-linear relationships well
- Works effectively with mixed feature types
- Reduces overfitting using ensemble learning

## Evaluation metrics
- Precision
- Recall
- F1-score

## Tools used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
