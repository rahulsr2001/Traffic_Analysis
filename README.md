# Traffic Flow Detection Process

## 1.Data Collection
The traffic quality detection dataset includes various attributes related to traffic conditions. Each row represents a traffic observation, and each column corresponds to a feature that influences overall traffic quality.
## 2.Data Preprocessing
Before training the models, the dataset was preprocessed, including handling missing values, converting categorical variables, and splitting the data into training and test sets to ensure robust evaluation.
## 3.Feature Selection
The following features were selected for model training:

- **DateTime**: The timestamp of the traffic observation.
- **Junction**: The identifier for the specific traffic junction.
- **Vehicles**: The count of vehicles passing through the junction during the specified time.
- **ID**: A unique identifier for each traffic observation.
## 4.Model Training
Several machine learning models were trained to predict traffic quality. The models used in this task and their performance (accuracy) are as follows:

- **Linear Regression** (LR): 53%
- **Support Vector Machine** (SVM): 70%
- **Decision Tree** (DT): 93%
- **K-Nearest Neighbors** (KNN): 95%
- **Random Forest** (RF): 96%
- **XGBoost** (XGB): 76%
## 5.Model Evaluation
The performance of each model was evaluated using accuracy scores, which measure the percentage of correct predictions on the test set. The Random Forest model achieved the highest accuracy of 96%, indicating strong performance in classifying traffic quality.

## 6.Best Model Selection
Based on the evaluation results, Random Forest, with an accuracy of 96%, is identified as the best-performing model for this traffic quality detection task.

## Columns in the Dataset
Here is a detailed description of the columns used in the traffic quality detection dataset:

- **DateTime**: The timestamp of the traffic observation, indicating the date and time.
- **Junction**: The identifier for the specific traffic junction where the observation was recorded.
- **Vehicles**: The count of vehicles passing through the junction during the specified time period.
-  **ID**: A unique identifier for each traffic observation.

By analyzing important attributes such as DateTime, Junction, and vehicle counts, machine learning models can classify traffic quality effectively. The Random Forest model is the most effective in this dataset, achieving high classification accuracy.
