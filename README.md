# Random Forest Software Engineer Salary Prediction

This project explores salary patterns for software engineers using a real world dataset. The goal is to understand how experience, location, and company factors influence salary levels and to build a predictive model based on these variables.

## Overview

The analysis begins with an examination of the salary distribution and the relationships among experience, company score, and location. Several visualizations are used to show how these features vary across the dataset.

A Random Forest Regressor is trained to predict salary. The model captures nonlinear patterns and provides estimates of feature importance, showing which factors contribute most to salary prediction.

All code, figures, and analysis steps are included in the PDF report.

## Repository structure

data  
Contains the dataset software_engineer_salaries.csv.

reports  
Contains the full analytical report Software_Engineer_Salaries_Prediction_Report.pdf.

results  
Contains a placeholder for future model outputs.

## Methods

The dataset is loaded and cleaned before modeling. Categorical variables such as company and location are encoded numerically. The data is split into training and testing portions to evaluate performance.

A Random Forest Regressor is trained to model salary based on experience, location, and company information. Mean squared error and R squared are used to evaluate predictive performance. Feature importance is used to identify the variables with the strongest influence on salary.

## Results

The findings show that experience has the greatest impact on salary. Location contributes to regional differences in compensation. Company score also affects salary but to a lesser degree.

The visualizations in the report show the distribution of salaries, the relationship between experience and salary, and the importance of each feature in the final model.

## Notes

The complete workflow is documented in the PDF report.  
The original code used for training and analysis is embedded within the report.  
This project can be extended by adding additional features or by experimenting with other regression models.

## Author

Hsiang Chen Yeh
