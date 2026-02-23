# Ames Housing Dataset Regression Diagnostic Analysis

Housing prices depend on a combination of a home structure, size, and overall quality. Understanding how these factors influence sale prices is important not only for homeowners 
and real estate professionals, but also for typical home buyers who want to know what features add the most value before making a purchase. The Ames Housing dataset provides a 
detailed, real-world example of residential properties, making it well suited for regression analysis. This report aims to develop, interpret, and assess multiple linear regression
models for predicting home sale prices. The analysis starts with exploratory data analysis and descriptive statistics to get a solid grasp of what's in the dataset. Then I move 
on to data preparation and correlation analysis to identify the most important predictors. Scatter plots and regression models are then employed to explore the relationships 
between continuous variables and SalePrice.

Diagnostic methods are applied to evaluate essential regression assumptions, including linearity, normality, constant variance, multicollinearity, and the presence of outliers. 
When issues are detected, appropriate transformations are applied to enhance model performance. Finally, an all- subsets regression approach is used to identify the optimal model,
which is then compared with a transformed model to determine which yields superior results.

## Files
- Ames Housing Dataset Regression Diagnostic.Rmd (main analysis file)
- AmesHousing.csv (dataset)
- AmesHousingdatasetDocumentation.txt (Meta Data File)
- Ames-Housing-Dataset-Regression-Diagnostic.pdf (Final rendered report for easy viewing)

## How to Run
Open the Rmd file in RStudio and Install required packages if needed.
Click Knit to PDF.

## Tools and Packages Used
- R
- ggplot2
- dplyr
- scales
- corrplot
- RColorBrewer
- car
- leaps
