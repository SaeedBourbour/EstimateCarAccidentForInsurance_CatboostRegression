## CatBoost Regression for Insurance Loss Prediction
This project aims to predict insurance losses using the CatBoost regression algorithm. It involves exploratory data analysis (EDA), data preprocessing, model training, and saving the trained model for future use.

# Dataset
The dataset consists of two CSV files:

train.csv: Contains training data with features and corresponding insurance loss values.
test.csv: Contains test data with features for which insurance losses need to be predicted.

# Setup
Ensure you have Python installed on your system.
Install the required libraries:
 pip install requirement.txt

# Usage
## Running the Code:
Clone this repository or download the train.csv and test.csv files into a folder named Dataset.
Open a terminal or command prompt and navigate to the project directory.
Run the Python script InsuranceRegression_CatBoost.ipynb.

## Understanding the Code:
The code begins by importing necessary libraries including Pandas, NumPy, Matplotlib, Seaborn, and CatBoost.
Training and test data are loaded into Pandas dataframes.
Exploratory Data Analysis (EDA) is performed to understand the data including checking basic statistics, data types, and missing values.
Categorical and numerical columns are separated.
Data visualization is performed to visualize the distribution of the target variable (loss) and to remove skewness.
CatBoost regression model is created and trained using the training data.
The trained model is saved using the pickle library for future use.
Interpreting the Results:
EDA helps understand the data distribution and identify any data cleaning or preprocessing steps required.
CatBoost is a gradient boosting algorithm that works well with categorical features without the need for extensive preprocessing.
Training the model involves defining the features and the target variable, splitting the data into training and testing sets, and fitting the model.
The exponential value of the predicted loss needs to be calculated to obtain the actual loss.
The trained model can be saved for future use to avoid retraining.
File Management:
The trained CatBoost regression model is saved into a file named catboost_regression using the pickle library.
The predicted outputs are saved to an Excel file for further analysis.

# Conclusion
This project demonstrates the use of CatBoost regression for predicting insurance losses. By utilizing the CatBoost algorithm, which handles categorical features efficiently, accurate predictions can be made without extensive preprocessing. The trained model can be saved and reused for future predictions.


