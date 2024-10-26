# Prodigy_DS_03
# Customer Purchase Prediction Using Decision Tree Classifier

## Overview
This project is designed to predict whether a customer will purchase a product or service based on demographic and behavioral data. Using the **Bank Marketing dataset** from the UCI Machine Learning Repository, a decision tree classifier was trained to understand customer purchasing patterns.

### Dataset
- **Source**: [Bank Marketing Dataset - UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing)
- **Features**: Includes customer attributes such as age, job type, marital status, education, balance, and other behavioral factors.
- **Target**: Binary variable indicating whether a customer subscribed to the product (Yes/No).

## Project Highlights
- **Data Preprocessing**: Encoded categorical variables using label encoding for model compatibility.
- **Model Training**: Used a decision tree classifier with a controlled depth for better interpretability.
- **Evaluation**: Assessed the model with accuracy, precision, recall, and F1-score.
- **Visualization**: Plotted the decision tree to visualize the decision-making process.

To install the necessary packages, run:
```bash
pip install pandas scikit-learn matplotlib
```

## Usage
1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/customer-purchase-prediction.git
    cd customer-purchase-prediction
    ```

2. **Run the code**:
   - Open the Python script in your preferred IDE, or
   - Run the code directly from the command line:
     ```bash
     python customer_purchase_prediction.py
     ```

3. **Model Training and Evaluation**:
   - The model will train on 80% of the data and evaluate on 20%.
   - The output will display the accuracy, classification report, and a visualization of the decision tree.

## Project Structure
```
├── customer_purchase_prediction.py  # Main script with data processing, model training, and visualization
├── bank.csv                         # Dataset (add or link to download if required)
└── README.md                         # Project overview and instructions
```

## Results
- **Model Accuracy**: Achieved an accuracy of 90%.
- **Key Insights**:
  - The decision tree visualization highlights the most influential factors in predicting customer purchases.
  - By limiting tree depth, we balanced interpretability and predictive performance.

## Future Improvements
- **Cross-Validation**: Implement k-fold cross-validation for more robust performance metrics.
- **Hyperparameter Tuning**: Use `GridSearchCV` or `RandomizedSearchCV` to find the optimal parameters for the decision tree.
- **Feature Importance**: Analyze and plot feature importance to understand the primary factors influencing predictions.

## Contributing
Feel free to fork this project, open issues, and submit pull requests. Any contributions to improve model accuracy, interpretability, or visualization are welcome!
