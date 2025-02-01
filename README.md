# PREDICTIVE_ANALYSIS-_USING_MACHINE_LEARNING_2

**COMPANY** : CODTECH IT SOLUTIONS

**NAME** : ESHA MAKWANA 

**INTERSHIP ID** : CT06MLL

**DOMAIN** : DATA ANALYSIS 

**BATCH DURATION** : January 15th, 2025 to February 26th, 2025

**GUIDE NAME** : NEELA SANTOSH

# DESCRIPTION: 
This script is focused on building a machine learning model to classify coffee types based on various features. The process follows a structured pipeline, starting with data loading, preprocessing, model training, and evaluation. The ultimate goal is to predict the type of coffee using a Random Forest Classifier, a widely used algorithm for classification tasks.

**Understanding the Data Handling Process**
The first step in the workflow is data acquisition. A dataset containing coffee-related attributes is loaded from a file. This dataset likely consists of various columns, some of which may not be relevant to the predictive model. Therefore, unnecessary columns, such as timestamps or transaction details, are removed to ensure that only meaningful attributes contribute to the classification task. This step helps in reducing noise and improving the model's efficiency.

**Encoding Categorical Variables**
Real-world datasets often contain categorical variables that machine learning algorithms cannot process directly. These categorical variables, such as payment type and coffee type, must be converted into numerical values before feeding them into the model. This is done using label encoding, a technique that assigns a unique integer to each category. For instance, if the dataset contains different types of coffee like "Espresso," "Latte," and "Cappuccino," they would be assigned numerical values like 0, 1, and 2, respectively. Similarly, payment methods such as "cash" or "credit card" would also be transformed into numerical equivalents. This ensures that the machine learning model can interpret the data correctly and make accurate predictions.

**Feature Selection and Data Splitting**
Once the dataset is preprocessed, the next step is defining the features and the target variable. Features refer to the independent variables used to make predictions, while the target variable is what the model aims to classify. In this scenario, the coffee type is the target variable, while other attributes such as payment type or transaction details serve as features.

To evaluate the performance of the model, the dataset is split into training and testing sets. The training set is used to teach the model, while the testing set helps assess how well the model performs on unseen data. The split ratio is set at 80% training and 20% testing, ensuring that the model has sufficient data to learn while still having a fair portion left for evaluation.

**Training a Machine Learning Model**
The classification task is performed using a Random Forest algorithm. Random Forest is an ensemble learning method that builds multiple decision trees during training and merges them to improve prediction accuracy. It is robust, handles large datasets efficiently, and mitigates the risk of overfitting. The model is trained on the prepared dataset using 100 decision trees to ensure stability in predictions.

**Making Predictions and Evaluating Model Performance**
After training, the model is tested on the unseen portion of the dataset. Predictions are made, and the results are compared against the actual coffee types in the test set. The evaluation metric used in this scenario is accuracy, which measures the percentage of correctly predicted labels. A higher accuracy score indicates that the model is effective in classifying different types of coffee based on the given features.

**Final Thoughts**
This machine learning pipeline is structured to provide an end-to-end approach for classification tasks. It efficiently processes raw data, prepares it for modeling, and applies an algorithm capable of handling complex relationships. The use of Random Forest ensures reliable performance, while accuracy measurement provides insights into how well the model generalizes to new data. The approach can be further improved by feature engineering, hyperparameter tuning, or testing different classification models to enhance prediction accuracy.

# OUTPUT OF TASK :
![Image](https://github.com/user-attachments/assets/8a3278dc-cb7e-47fe-8daa-5271c6a4f0b2)
