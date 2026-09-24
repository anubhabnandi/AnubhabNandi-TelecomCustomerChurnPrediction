
# Telecom Customer Churn Prediction Using Data Analytics and AI

Project Overview

This project focuses on analyzing telecom customer data and predicting whether a customer is likely to churn or continue using the service.

The project uses Data Analytics, Exploratory Data Analysis, Data Visualization, and Machine Learning techniques to identify patterns associated with customer churn.

A Random Forest Classifier is used to build a machine learning model that predicts customer churn based on historical customer information.

Student Information

Name: Anubhab Nandi
Institution: Guru Nanak Institute of Technology
Program: BCA
Internship: IBM SkillsBuild Data Analytics with AI Internship 2026

Project Objectives

- Analyze a large telecom customer dataset.
- Clean and preprocess customer data.
- Handle missing values and inconsistent data.
- Perform Exploratory Data Analysis.
- Visualize important customer and churn patterns.
- Build a machine learning model for churn prediction.
- Evaluate the performance of the model.
- Identify important features influencing churn prediction.
- Demonstrate the use of AI and machine learning in data analytics.

Dataset

The project uses the Cell2Cell Telecom Customer Churn dataset.

The referenced training dataset contains approximately 51,047 customer records and 58 features, making it suitable for analyzing a large customer population.

Dataset Source

GitHub repository:

https://github.com/leylatulu/Telecom-Churn-Analysis

Dataset file:

"cell2celltrain.csv"

The dataset contains telecom customer information related to customer behavior, services, account information, usage patterns, and churn status.

The notebook loads the dataset directly from the public repository, so a separate dataset file is not required to run the notebook.

Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Random Forest Classifier

Machine Learning Model

The project uses the Random Forest Classifier for binary classification.

The model predicts whether a customer is:

- Stayed
- Churned

Random Forest was selected because it can handle multiple features and capture non-linear relationships in customer data.

Data Analytics Workflow

The project follows these major steps:

1. Load the dataset.
2. Inspect the dataset structure.
3. Check missing values and data types.
4. Identify the churn target column.
5. Clean and preprocess the data.
6. Remove identifier-like columns where appropriate.
7. Handle missing numerical and categorical values.
8. Encode categorical variables.
9. Perform Exploratory Data Analysis.
10. Create visualizations.
11. Split the dataset into training and testing sets.
12. Scale the feature data.
13. Train the Random Forest model.
14. Generate churn predictions.
15. Evaluate the model.
16. Analyze feature importance.
17. Generate a sample customer prediction.
18. Summarize the project results.

Model Evaluation

The machine learning model is evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

These metrics provide different views of the model's classification performance.

Project Structure

Telecom-Customer-Churn-Prediction/
│
├── AnubhabNandi_TelecomCustomerChurn_AI_10K.ipynb
├── requirements.txt
└── README.md

Installation

Make sure Python 3 is installed on your system.

Install the required Python libraries using:

pip install -r requirements.txt

Alternatively, the notebook contains a setup cell that installs the required libraries.

How to Run the Project

Step 1: Clone or download the repository

Download the project from GitHub.

Step 2: Install dependencies

Run:

pip install -r requirements.txt

Step 3: Open Jupyter Notebook

Run:

jupyter notebook

Step 4: Open the notebook

Open:

AnubhabNandi_TelecomCustomerChurn_AI_10K.ipynb

Step 5: Run all cells

Run the notebook cells from top to bottom.

The notebook automatically loads the public dataset from the configured dataset URL.

AI and Machine Learning Component

The project applies machine learning to predict customer churn using historical telecom customer data.

AI-assisted development tools, including IBM Bob where applicable, can support development activities such as:

- Code assistance
- Debugging
- Code explanation
- Data analysis guidance
- Documentation assistance

The final project implements the data analytics and machine learning workflow in Python using a Random Forest Classifier.

Results

The notebook generates the following outputs:

- Dataset information
- Missing-value analysis
- Customer churn distribution
- Exploratory visualizations
- Training and testing dataset information
- Model accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- Feature importance
- Example customer churn prediction

The exact model performance metrics are generated when the notebook is executed because they depend on the processed dataset and train-test split.

Future Improvements

The project can be further improved by:

- Comparing multiple machine learning algorithms.
- Performing hyperparameter tuning.
- Applying cross-validation.
- Using advanced feature engineering.
- Applying explainable AI techniques such as SHAP.
- Building an interactive dashboard.
- Deploying the model as a web application.
- Adding real-time customer churn prediction.

Conclusion

This project demonstrates how Data Analytics and Machine Learning can be applied to a large telecom customer dataset to understand customer behavior and predict potential customer churn.

The analysis provides insights into customer patterns, while the Random Forest model provides a data-driven approach for classifying customers based on their likelihood of churn.

The project demonstrates a complete workflow from data collection and preprocessing to exploratory analysis, visualization, machine learning, evaluation, and prediction.

The model's predictions are analytical estimates based on historical data and should not be considered guaranteed future outcomes.

Author

Anubhab Nandi
Guru Nanak Institute of Technology
BCA