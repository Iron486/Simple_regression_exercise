# Simple_regression_exercise-Mid-career-salary-prediction-
The aim of this small project was the prediction of mid-career salary of the students considering data from different universities.

The notebook is the following: [datafrom_collegetuitiondiversityandpay_dataset.ipynb](https://github.com/Iron486/Simple_regression_exercise/blob/main/datafrom_collegetuitiondiversityandpay_dataset.ipynb)

I collected the data from here: https://www.kaggle.com/datasets/jessemostipak/college-tuition-diversity-and-pay.

After downloading the 5 tables and loading them with pandas, I merged the 2 tables (salary_potential,tuition_cost) that were useful to extract the most information to predict the mid-career salary.

Once I did that, I extracted the most important features basing on a simple calculation of the correlation coefficients for each extracted feature.

I handled the categorical features, filled the missing values and scaled the input features.

Later, I fit the model on the train dataset and predicted on the test dataset. The algorithm with the lowest rmse was the DecisionTreesRegressor.

I finally plot some accuracy plots to better interpret the results.


