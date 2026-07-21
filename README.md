# Medical Insurance Cost Prediction using Multiple Linear Regression

## Objective

The objective of this project is to develop a Multiple Linear Regression model to predict medical insurance charges based on personal and health-related information. The model uses features such as age, sex, BMI, number of children, smoking status, and region to estimate insurance charges.

## Dataset

The project uses the Medical Cost Personal Insurance Dataset.

**Dataset Link:**
https://www.kaggle.com/datasets/mirichoi0218/insurance

The dataset contains information about individuals and their corresponding medical insurance charges.

## Libraries Used

The following Python libraries were used:

* Pandas
* NumPy
* Matplotlib
* Scikit-learn

## Methodology

The following steps were performed:

1. Loaded the dataset using Pandas.
2. Examined the first five records and dataset information.
3. Identified numerical and categorical features.
4. Checked the dataset for missing values.
5. Selected age, sex, BMI, children, smoker, and region as input features.
6. Used One-Hot Encoding to convert categorical variables into numerical form.
7. Divided the dataset into 80% training and 20% testing data.
8. Built a Multiple Linear Regression model using Scikit-learn.
9. Trained the model using the training dataset.
10. Predicted insurance charges for the test dataset.
11. Evaluated the model using MAE, MSE, and R² Score.
12. Created an Actual vs Predicted scatter plot to visualize model performance.

## Results

The model was evaluated using the following metrics:

* Mean Absolute Error (MAE): 4181.194473753643
* Mean Squared Error (MSE): 33596915.85136148
* R² Score: 0.7835929767120722

The model achieved a reasonably good R² score, indicating that the selected features explain a significant portion of the variation in medical insurance charges. However, some predictions showed deviations from actual values, suggesting that additional factors and non-linear relationships may influence insurance costs.

## Conclusion

A Multiple Linear Regression model was successfully developed to predict medical insurance charges. The analysis showed that factors such as age, BMI, and smoking status can significantly affect insurance costs. The model provides reasonable predictions but has limitations because Linear Regression assumes a linear relationship between the input variables and the target variable. More advanced machine learning algorithms could potentially improve prediction accuracy by capturing complex and non-linear relationships in the data.

## Project Files

* `Assignment-1.ipynb` – Jupyter Notebook containing data analysis, preprocessing, model development, evaluation, and visualization.

## Author

**Avishi Tripathi**

