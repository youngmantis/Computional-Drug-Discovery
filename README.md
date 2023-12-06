# Comparison of Regression Models for Predicting Drug-Target Interactions
# Introduction
This project presents a comprehensive analysis that compare various regression models for predicting the biological activity of biological targets inhibitors.

Research questions:
1. Which regression models demonstrate the highest predictive accuracy for biological target inhibitors' activity?
2. How does the performance of traditional regression models (e.g., linear regression) compare to more advanced machine learning techniques (e.g., random forests, support vector machines, deep neural network) in predicting biological activity?
3. Does the choice of molecular descriptors (e.g., structural, physicochemical properties) impact the performance of regression models in predicting biological activity?
4. Can ensemble techniques further enhance the predictive accuracy of regression models for biological activity prediction?
# Data Collection and Pre-Processing
The ChEMBL bioactivity data is collected and pre-processed to ensure data quality and consistency. Any necessary data cleaning steps are performed to prepare the dataset for model training and evaluation.
# Exploratory Data Analysis
The collected data is analyzed to gain insights into its characteristics. Descriptive statistics and data visualizations are employed to understand the distribution of variables and identify potential patterns or outliers.
# Descriptor Dataset Preparation
A descriptor dataset is prepared to train and evaluate the regression models. Relevant features are selected, and the dataset is transformed into a suitable format for model training. Below are some of the descriptor datasets prepared so far:
https://drive.google.com/drive/folders/17K-DZCuZya1gBdl7TFEEhk-L89SO6Jce
# Regression Model Selection
Several regression models are chosen for comparison, including Random Forest Regression and others. Each model is trained using the prepared descriptor dataset.
# Model Evaluation
The performance of each regression model is evaluated using appropriate evaluation metrics, such as mean squared error (MSE), root mean squared error (RMSE), mean absolute error (MAE) and coefficient of determination (R-squared). The results are compared to identify the most effective model for predicting drug-target interactions.
# Disclaimer:
This project builds upon the work of the 'Data Professor' and utilizes the ChEMBL bioactivity data. The author, Alex Oyinola Adedayo, acknowledges the inspiration and resources provided by the 'Data Professor' GitHub repository: https://github.com/dataprofessor/bioinformatics_freecodecamp/ and 'freeCodeCamp' YouTube channel: https://www.youtube.com/watch?v=jBlTQjcKuaY&t=300s&pp=ygUqZGF0YSBwcm9mZXNzb3IgYmlvaW5mb3JtYXRpY3NfZnJlZWNvZGVjYW1w.
# Note
Please refer to the Notebooks in this repository for detailed analysis of the dataset. Below are some of the Notebooks to expedite the process:
  https://github.com/youngmantis/Computional-Drug-Discovery/blob/main/CDD_Arachidonate_5_lipoxygenase.ipynb
  
  https://github.com/youngmantis/Computional-Drug-Discovery/blob/main/CDD_Cytochrome_P450_2B6_Model_Compare.ipynb
  
  https://github.com/youngmantis/Computional-Drug-Discovery/blob/main/Alkaline_phosphatase_tissue_nonspecific_Regression_Models_Comparison.ipynb
# Other Repositories
Check out some of my other repositories. Explore https://github.com/youngmantis/2023-NIgeria-Presidential-Election-Results-Analysis-and-Visualization for the detailed analysis of the 2023 Nigerian election. Also checkout https://github.com/youngmantis/Covid19-Exploratory-Data-Analysis for the exploratory data analysis and XGBOOST model on Covid19-global-forecasting competition on Kaggle. You can also checkout my SQL portfolio https://github.com/youngmantis/SQL-Projects
