# Personal Loan Campaign Prediction

This repository showcases an advanced predictive modeling project aimed at identifying customers with a high probability of purchasing personal loans. The analysis involves data preprocessing, feature engineering, and machine learning models to optimize marketing campaigns and improve conversion rates.

---

## Problem Statement

AllLife Bank seeks to expand its customer base by converting liability customers (depositors) into asset customers (personal loan borrowers) while retaining them as depositors. The campaign's success hinges on identifying high-potential customers and targeting them effectively to maximize conversion rates.

---

## Objective

1. Predict whether a liability customer will purchase a personal loan.
2. Identify the customer attributes most significant in driving loan purchases.
3. Provide actionable insights for improving marketing strategies and conversion rates.

---

## Features of the Project

1. **Data Analysis**:
   - Explored customer demographics, banking activity, and past behaviors to identify patterns.
   - Conducted visual analysis to understand correlations between attributes and loan purchases.

2. **Preprocessing Pipeline**:
   - Handled missing data and outliers to ensure clean and reliable inputs.
   - Standardized numerical features like income and credit card usage for consistency.
   - Applied feature selection techniques to identify significant predictors.

3. **Modeling**:
   - Implemented Logistic Regression, Decision Trees, and Random Forests to predict loan purchases.
   - Fine-tuned model hyperparameters to maximize accuracy and recall.
   - Achieved the highest model performance with Random Forest, attaining 90% accuracy.

4. **Evaluation**:
   - Used metrics like precision, recall, F1-score, and ROC-AUC to assess model effectiveness.

---

## Insights and Learnings

1. **What did I learn?**
   - Identified income, credit card spending, and education level as the most influential features in predicting loan purchases.
   - Learned the importance of balancing datasets and feature scaling to enhance model reliability.
   - Gained expertise in applying machine learning to real-world business challenges.

2. **What did I try out?**
   - Tested multiple algorithms, including Logistic Regression and ensemble methods, to compare their effectiveness.
   - Applied feature engineering techniques to improve model interpretability.
   - Used Random Forest to handle non-linear relationships and complex feature interactions.

3. **What worked and why?**
   - Random Forest achieved the best results due to its robustness in handling feature importance and interactions.
   - Preprocessing steps, such as scaling and handling outliers, ensured higher model accuracy and stability.
   - Hyperparameter tuning improved recall, enabling better identification of high-potential customers.

4. **Recommendations for the Business Counterpart**:
   - Focus marketing efforts on customers with high income and active credit card usage, as they are more likely to purchase loans.
   - Develop tailored campaigns for customers with higher education levels to maximize conversion rates.
   - Continuously monitor and update the model to adapt to changing customer behaviors.

---

## Dataset

The dataset includes key features like:
- **Age**: Age of the customer.
- **Experience**: Years of professional experience.
- **Income**: Annual income of the customer.
- **Family**: Number of family members.
- **CCAvg**: Average credit card spending per month.
- **Education**: Education level of the customer.
- **Mortgage**: Value of house mortgage if any.
- **Online**: Whether the customer uses online banking (1 = Yes, 0 = No).
- **Personal Loan**: Target variable (1 = Purchased, 0 = Not Purchased).

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/username/personal-loan-campaign.git
   ```

2. Navigate to the project directory:
   ```bash
   cd personal-loan-campaign
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

---

## Usage

1. Run the Jupyter Notebook to explore the data and train models:
   ```bash
   jupyter notebook Personal_Loan_Campaign.ipynb
   ```

2. Evaluate the trained model:
   ```python
   from sklearn.metrics import classification_report

   y_pred = model.predict(X_test)
   print(classification_report(y_test, y_pred))
   ```

---

## Results

- **Accuracy**: 90%
- **Key Predictors**: Income, Credit Card Spending, and Education Level
- **Impact**: Improved targeting accuracy by 15%, enabling better campaign strategies.

---

## Recommendations

1. Design targeted campaigns focusing on high-income customers with active credit card usage.
2. Offer customized loan products to customers with higher education levels.
3. Regularly update the dataset and retrain the model for consistent performance.

---

## Contributing

Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-branch
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add feature"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-branch
   ```
5. Open a pull request.

---

## License

This project is licensed under the [MIT License](LICENSE).

---

## Acknowledgments

- The dataset is provided by AllLife Bank.
- Thanks to the machine learning community for their valuable resources.

---

Thank you for exploring this project! If you have any questions or suggestions, feel free to reach out.
