# Telco Customer Churn Prediction Using Machine Learning
 
## Project Overview
 
This project develops an end-to-end machine-learning classification workflow for predicting telecommunications customer churn.
 
## Dataset Location
 
Place the dataset at:
 
data/WA_Fn-UseC_-Telco-Customer-Churn.csv
 
## Project Structure
 
Telco_Customer_Churn_Project/

    data/

    notebooks/

    figures/

    results/

    README.md

    requirements.txt
 
## Models
 
- Dummy Classifier (Baseline)

- Logistic Regression

- K-Nearest Neighbours

- Random Forest
 
## Workflow
 
1. Problem formulation

2. Data loading

3. Data audit and cleaning

4. Exploratory data analysis

5. Stratified train-test split

6. Leakage-safe preprocessing

7. Baseline evaluation

8. Candidate-model training

9. Cross-validation and hyperparameter tuning

10. Final model selection

11. Test-set evaluation

12. Error analysis

13. Model interpretation

14. Reproducibility documentation
 
## Reproducibility
 
Random State: 42

Test Size: 20%

Cross-validation: 5-fold Stratified Cross-Validation
 
## Running the Project
 
1. Install the required packages:
 
   pip install -r requirements.txt
 
2. Open:
 
   notebooks/Telco_Customer_Churn_Prediction.ipynb
 
3. Restart the Jupyter kernel.
 
4. Run all cells from top to bottom.
 
The notebook automatically generates figures and result files.

