# Internship_Case_Study_Day19

the final model for the fraud detection system was selected based on performance comparison and hyperparameter tuning results. The models evaluated include Logistic Regression, Random Forest, and XGBoost.
The goal of this stage was to identify the most effective model for detecting fraudulent transactions in real-world scenarios.

Objectives
The objectives of this phase were:
- Compare all trained models
- Analyze performance after hyperparameter tuning
- Select the best-performing model
- Perform final evaluation on test data


Models Evaluated
The following models were analyzed:
1. Logistic Regression (Baseline Model)
2. Random Forest (Ensemble Model)
3. XGBoost (Boosting Model)
Each model was evaluated using the same dataset and performance metrics.


Evaluation Criteria
The final model selection was based on:
- Accuracy
- Precision
- Recall (most important)
- F1 Score
- Model stability
For fraud detection, **Recall is the most critical metric**, as it measures the ability to correctly identify fraudulent transactions.

Final Model Selection
After comparing all models:
- Logistic Regression showed basic performance but struggled with complex patterns
- Random Forest performed well and handled non-linear data effectively
- XGBoost achieved the highest overall performance and best recall

Final Selected Model: XGBoost

Final Evaluation
The selected model was evaluated on the test dataset to confirm its performance.
Key observations:
- High fraud detection rate
- Balanced precision and recall
- Reduced false negatives

This makes the model suitable for real-world deployment.
