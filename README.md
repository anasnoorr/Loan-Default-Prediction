Loan Default Prediction
This project builds a model to predict if a loan applicant might not pay back (default). It helps lenders find high-risk borrowers to reduce losses.

What This Project Does
Loads loan data from a CSV file

Cleans and prepares the data (fills missing values, changes text to numbers)

Balances the data using SMOTE to handle fewer default cases

Trains two models: LightGBM and SVM to predict loan defaults

Checks how well the models work using precision, recall, and F1 score

Gives simple advice for lenders based on the model results

How to Use
Upload your loan data CSV file with a loan_status column (0 = no default, 1 = default).

Run the notebook or script in your Python environment.

See model results and recommendations.


Summary of Results
The models help identify borrowers likely to default.

Data balancing improved model accuracy.

LightGBM and SVM gave good performance on test data.

Precision, Recall, and F1 scores show models predict defaults well.

Recommendations for Lenders
Review high-risk applicants carefully.

Use model predictions to help approve or deny loans.

Support borrowers flagged as risky with better terms or advice.
