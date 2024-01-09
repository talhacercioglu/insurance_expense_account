# Insurance Cost Prediction

## Introduction
This project involves predicting insurance costs based on various features such as age, gender, body mass index, number of children, smoking status, and region of residence. Different machine learning models are employed to understand and predict insurance costs accurately.

## Dataset
The dataset used in this project is stored in the `insurance.csv` file. It includes the following columns:
- `age`: Age of the individual.
- `sex`: Gender of the individual.
- `bmi`: Body Mass Index of the individual.
- `children`: Number of children covered by health insurance.
- `smoker`: Smoking status of the individual.
- `region`: Region of residence.
- `charges`: Insurance charges.

## Code Structure
- `data_exploration.ipynb`: Jupyter notebook containing code for exploring the dataset and visualizing key features.
- `data_preprocessing.ipynb`: Jupyter notebook with code for handling missing values, encoding categorical variables, and preparing the data for modeling.
- `linear_regression.ipynb`: Jupyter notebook implementing linear regression and polynomial regression models for insurance cost prediction.
- `random_forest.ipynb`: Jupyter notebook implementing a Random Forest Regressor for insurance cost prediction.

## Instructions
1. Clone the repository: `git clone https://github.com/your-username/insurance-cost-prediction.git`
2. Navigate to the project directory: `cd insurance-cost-prediction`
3. Install the required dependencies: `pip install -r requirements.txt`
4. Run the Jupyter notebooks to explore the data, preprocess it, and build and evaluate different regression models.

## Results
- Linear Regression:
  - R2 score on test data: 0.865

- Random Forest Regressor:
  - MSE on train data: 4,364,972.703
  - MSE on test data: 26,530,799.410
  - R2 score on train data: 0.970
  - R2 score on test data: 0.829

## Conclusion
The Random Forest Regressor model shows promising results in predicting insurance costs. Further tuning and optimization can be explored to improve model performance. Feel free to experiment with other regression models or features to enhance the predictions.

## Data Preprocessing
Label encoding was applied to categorical variables such as 'sex', 'smoker', and 'region' to convert them into a format suitable for machine learning models. Polynomial features were also introduced to capture non-linear relationships in the data.

## Model Evaluation
The Random Forest Regressor achieved a high R2 score on the test data, indicating good predictive performance. The MSE values provide insights into the model's accuracy, with lower values indicating better performance.

Feel free to contribute to the project by experimenting with different models, feature engineering techniques, or providing additional insights into the dataset.

