# Management Report – Loan Eligibility Automation Project

## Author

Prepared by Mohammad Bahrami

---

## Project Objective

The main objective of this project is to automate the process of checking loan eligibility for applicants based on their account information.  
By using data-driven methods and machine learning algorithms, the project aims to make the loan approval process more accurate, consistent, and efficient compared to traditional manual checks.

---

## Section 1 – Data Preprocessing

In the first stage, the dataset was prepared to ensure quality and consistency. The following steps were applied:

- Handling missing values to reduce bias in the data
- Encoding categorical (non-numeric) features into numerical format
- Splitting the dataset into training, validation, and test sets for reliable evaluation
- Normalizing numerical features to ensure balanced model performance

---

## Section 2 – Model Training

Three different machine learning models were implemented and trained on the processed dataset:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Artificial Neural Network (ANN)

Each model was trained and validated to measure its effectiveness in predicting loan eligibility.

---

## Section 3 – Model Comparison

To select the best-performing model, a detailed comparison was conducted using multiple evaluation metrics:

- Accuracy
- Precision
- Recall
- F1-Score

After testing and validation, the best model was identified and stored for final deployment.

---

## Section 4 – Exploration and Improvement

Further analysis was performed to better understand the model results.

- Hyperparameter tuning was applied to improve performance
- Limitations of the models were analyzed
- Recommendations were provided for future improvements, including data enrichment and advanced modeling techniques

---

## Tools and Technologies

The project was implemented using the following tools and libraries:

- Python 3.x
- pandas, numpy, scikit-learn
- tensorflow / keras
- matplotlib, seaborn
- joblib

---

## Key Notes

- Each section of the project is organized into a separate Jupyter Notebook inside the notebook/ folder
- Trained models are saved as .pkl files for reuse
- The final and best-performing model is stored as final_model.pkl

---

## Conclusion

This project, conducted by Mohammad Bahrami, demonstrates how machine learning can be applied to automate loan eligibility checking.  
By preparing the data carefully, training multiple models, and comparing their performance, the project provides a scalable solution that can assist financial institutions in making faster and more reliable loan decisions.
