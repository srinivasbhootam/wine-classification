# Wine Dataset Classification

This project demonstrates the classification of wines into three categories using the Wine Dataset from scikit-learn. It utilizes Logistic Regression for predictive modeling, evaluates model performance, and visualizes results.

## Dataset
- **Source**: [scikit-learn](https://scikit-learn.org/stable/datasets/toy_dataset.html#wine-dataset)
- **Features**: 13 chemical properties of wine
- **Target**: Wine class (0, 1, 2)

## Workflow
1. **Data Loading and Exploration**:
   - Loaded the dataset using `sklearn.datasets.load_wine`.
   - Performed data exploration and feature analysis.

2. **Data Preprocessing**:
   - Standardized features using `StandardScaler` for better model performance.

3. **Model Building**:
   - Implemented Logistic Regression for classification.
   - Split the dataset into training (80%) and testing (20%) sets.

4. **Model Evaluation**:
   - Evaluated model performance using metrics such as accuracy, confusion matrix, and classification report.
   - Achieved an accuracy of 1.00 on the test set (replace with your result).

5. **Visualization**:
   - Plotted a confusion matrix heatmap to interpret predictions.

## Requirements
To run the project, install the following dependencies:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
