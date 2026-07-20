# Assignment - 1 : Medical Insurance Cost Prediction using Multiple Linear Regression

## Objective
The objective of this project is to predict medical insurance charges using Multiple Linear Regression based on customer information such as age, sex, BMI, number of children, smoking status, and region.

## Dataset
Medical Cost Personal Insurance Dataset

https://www.kaggle.com/datasets/mirichoi0218/insurance

## Libraries Used
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Methodology
1. Loaded the dataset.
2. Checked for missing values.
3. Encoded categorical variables.
4. Split the dataset into training and testing sets.
5. Trained the Multiple Linear Regression model.
6. Predicted insurance charges.
7. Evaluated the model using MAE, MSE, and R² Score.
8. Created an Actual vs Predicted scatter plot.

## Results
- Mean Absolute Error (MAE): 4186.51
- Mean Squared Error (MSE): 33635210.43
- R² Score: 0.7833

## Conclusion
The model performed well in predicting insurance charges and achieved an R² score of about 0.78. The results show that smoking status, age, and BMI are important factors affecting insurance costs. Although the model performs well, it may not accurately predict every case because Linear Regression assumes a linear relationship between the features and the target.
