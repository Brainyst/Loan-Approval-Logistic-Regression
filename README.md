# Loan Approval Prediction Project

This project predicts the loan approval status of applicants using a logistic regression model. The dataset contains various features about applicants, such as gender, marital status, education level, employment status, and credit history. The objective is to classify loan approvals based on these applicant characteristics.

## Project Workflow

The analysis and modeling workflow includes the following steps:

1. **Data Loading**: The dataset is imported and loaded for analysis.
2. **Exploratory Data Analysis (EDA)**:
   - Previewing the dataset structure, column types, and summary statistics.
   - Handling missing values in categorical and numerical columns using the mode and median/mean values, respectively.
3. **Data Transformation and Encoding**:
   - Encoding categorical features with one-hot encoding and dropping unnecessary columns.
   - Scaling numerical features for better performance in logistic regression.
4. **Feature Selection and Data Splitting**:
   - Defining features (`X`) and target variable (`Y`).
   - Splitting the dataset into training and test sets with an 80-20 ratio.
5. **Modeling**:
   - Training a logistic regression model on the training data.
   - Making predictions on the test data.
6. **Model Evaluation**:
   - Calculating the model accuracy and creating a confusion matrix to evaluate performance.
7. **Conclusion**:
   - The model achieved an accuracy of 84%, successfully predicting loan approvals. The confusion matrix shows instances of true positives, false positives, true negatives, and false negatives.
   
## Requirements

The project requires Python 3.x and the following libraries (specified in requirements.txt):

- pandas
- seaborn
- matplotlib
- scikit-learn
  
## Usage

1. Place your dataset file loan_data_set.csv in the project folder.
2. Run the script to perform the analysis and prediction:

➤ python loan_approval_prediction.py

## Output

• Model Accuracy: Displays the accuracy score of the model.<br>
• Confusion Matrix: Visualizes the confusion matrix for a detailed view of the model’s performance.
   
