# Credit Card Approval Prediction

This project aims to predict credit card approval decisions using a machine learning model based on historical credit card application data. The project involves data preprocessing, model training, hyperparameter tuning, and performance evaluation.

## Dataset

The dataset used in this project is sourced from datacamp. It contains information about credit card applications, including various attributes such as age, income, employment, and credit history.

## Project Structure

The project repository is organized as follows:

- `datasets/`: Directory containing the credit card approval dataset
- `README.md`: Readme file providing an overview of the project
- `credit_card_approval.ipynb`: Jupyter Notebook file containing the project code and analysis

## Setup and Dependencies

To run the project code, follow these steps:

1. Clone the project repository
2. Install the required dependencies
3. Open the `credit_card_approval.ipynb` Jupyter Notebook and execute the code cells sequentially.

## Results and Evaluation

The project utilizes a logistic regression model to predict credit card approval decisions. The performance of the model is evaluated using various metrics, including accuracy and confusion matrix. Hyperparameter tuning is performed using grid search to improve the model's performance.

The best model achieved an accuracy of 100% on the test data, with the following hyperparameters:
- Tolerance (tol): 0.001
- Maximum Iterations (max_iter): 150

## Conclusion

In this project, we developed a machine learning model to predict credit card approval decisions based on historical application data. The model provides valuable insights into the factors influencing credit card approvals and can assist in automating the decision-making process. Further improvements and feature engineering can be explored to enhance the model's performance.

For more details, please refer to the `credit_card_approval.ipynb` notebook.



