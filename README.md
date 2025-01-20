# Wine Quality Dataset Project
## 1. Project Overview
####  .Objective: Analyze and model wine quality data to identify factors influencing quality and predict wine ratings.
####  .Dataset: The Wine Quality dataset from the UCI Machine Learning Repository, containing attributes of red and white wines.
####  .Tools Used: Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn), Google colab..
## 2 . Dataset Description
### Features:
#### .Fixed Acidity: Concentration of non-volatile acids.
#### .Volatile Acidity: Amount of acetic acid in wine.
#### .Citric Acid: Levels of citric acid in wine.
#### .Residual Sugar: Sugar left after fermentation.
#### .Chlorides: Salt content.
#### .Free Sulfur Dioxide: Free SO₂ in wine.
#### .Total Sulfur Dioxide: Total SO₂ present.
#### .Density: Density of the wine.
#### .pH: Acidity or alkalinity level.
#### .Alcohol: Alcohol content.
#### .Quality (Target): Wine quality rating (0–10).
## 3. Data Preprocessing
### Steps Taken:
#### .Checked for missing values and handled them.
#### .Scaled numerical features to ensure uniformity.
#### .Explored correlations to identify important features.
#### .Balanced the dataset for target quality distribution.
## 4. Exploratory Data Analysis (EDA)
### Key Findings:
#### .Correlation matrix showed alcohol and volatile acidity strongly affect wine quality.
#### .Visualizations (e.g., box plots, histograms) revealed trends in quality based on chemical composition.
#### .Distribution of wine quality scores skewed towards mid-range values (5–7).

## 5. Model Development
### Modeling Approach:
#### .Split data into training and testing sets (80/20 split).
#### .Applied machine learning models: Random Forest 
### Performance Metrics:
#### .Accuracy score
#### .Random Forest achieved the best accuracy 
## 6. Key Insights
#### .Higher alcohol content generally corresponds to better wine quality.
#### .Wines with balanced acidity (volatile and fixed) tend to be rated higher.
#### .Residual sugar has minimal impact on quality, contrary to expectations.
## 8. Conclusion and Future Work
### Conclusion:
#### .Identified alcohol and acidity as key determinants of wine quality.
#### .Demonstrated machine learning can effectively predict wine quality.
### Future Work:
#### .Incorporate external factors (e.g., vineyard region, climate).
#### .Experiment with deep learning models for prediction.
## 9.Links
#### Dataset:https://github.com/chandana1798/Wine-Quality-Project/blob/main/winequality-red.csv
#### Project:https://github.com/chandana1798/Wine-Quality-Project/blob/main/wine%20quailty%20project.ipynb
