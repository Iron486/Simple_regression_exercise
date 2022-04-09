# Simple_regression_exercise-Mid-career-salary-prediction-
The aim of this small project was the prediction of mid-career salary of the students considering data from different universities.

The notebook is the following: [datafrom_collegetuitiondiversityandpay_dataset.ipynb](https://github.com/Iron486/Simple_regression_exercise/blob/main/datafrom_collegetuitiondiversityandpay_dataset.ipynb) and I collected the data from here: https://www.kaggle.com/datasets/jessemostipak/college-tuition-diversity-and-pay.

After downloading the 5 tables and loading them with `pandas`, I merged the 2 tables ([salary_potential](https://github.com/Iron486/Simple_regression_exercise/blob/main/salary_potential.csv),[tuition_cost](https://github.com/Iron486/Simple_regression_exercise/blob/main/tuition_cost.csv)) that were useful to extract the most information to predict the 
mid-career salary.

Once I did that, I extracted the most important features basing on a simple calculation of the correlation coefficients for each extracted feature.

I handled the categorical features, filled the missing values and scaled the input features.

Later, I fit the model on the train dataset and predicted on the test dataset. The algorithm with the lowest `rmse` was the `DecisionTreesRegressor`.

I finally plot some accuracy plots to better interpret the results are also showed below:

**<p align="center"> Accuracy Plots - training </p>**


<p align="center"> <img src="https://user-images.githubusercontent.com/62444785/162548345-fef79534-82cd-4d34-9077-e8d269b1aeca.png" width="620" height="520"/>  </p>

<p align="center"> <img src="https://user-images.githubusercontent.com/62444785/162548348-9407c42b-b6c8-43d7-9ee9-84b5a078b947.png" width="620" height="520"/>  </p>

<p align="center"> <img src="https://user-images.githubusercontent.com/62444785/162548352-5124b04d-5875-46de-ad78-438413ae9680.png" width="620" height="520"/>  </p>
