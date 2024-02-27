# Random Forest Vs. XGBoost: Comparative Analysis

XGBoost and Random Forest are well-known machine learning algorithms that are highly efficient and adaptable. By combining several decision trees, the ensemble learning technique Random Forest performs exceptionally well when managing noisy data. However, the gradient-boosted decision tree implementation known as XGBoost is well known for its outstanding predictive capabilities. In this investigation, we evaluate the performance of these methods in three different scenarios: huge datasets for binary classification tasks, different degrees of dimensionality, and noisy data.

## 1. Noisy data or features (outliers)

### 1.1. Objectives
Compare Random Forest and XGBoost performance in handling noisy data (outliers) using provided dataset.

### 1.2. Results
- **Performance Metrics:** XGBoost achieved lower Mean Squared Error (MSE), indicating better predictive performance.
- **Hyperparameters:** Tuned hyperparameters provided optimal configurations for each model.
- **Computational Efficiency:** XGBoost showed faster training time and lower memory usage.

### 1.3. Conclusion
XGBoost demonstrated better predictive performance, faster training time, and lower memory usage compared to Random Forest.

## 2. Varying degrees of dimensionality

### 2.1. Objectives
Compare Random Forest and XGBoost in handling varying degrees of dimensionality using given dataset.

### 2.2. Results
- **Performance Metrics:** Random Forest excels at lower dimensionality, XGBoost at higher dimensionality.
- **Hyperparameters:** Optimal hyperparameters selected for each model.
- **Computational Efficiency:** XGBoost showed better training time and memory usage, especially in higher dimensions.

### 2.3. Conclusion
Model choice depends on specific data characteristics. XGBoost outperformed Random Forest in predictive accuracy across varying dimensions.

## 3. Large datasets

### 3.1. Objectives
Compare Random Forest and XGBoost performance on a large, imbalanced dataset for binary classification.

### 3.2. Results
- **Performance Metrics:** Differences in precision, recall, and F1-score. Random Forest excelled in F1-score for class 1, XGBoost for class 0.
- **Hyperparameters:** Tuned hyperparameters for optimal configurations.
- **Computational Efficiency:** XGBoost demonstrated faster training time and lower memory usage.

### 3.3. Conclusion
XGBoost outperformed Random Forest in terms of classification performance, training time, and memory consumption on the large and imbalanced dataset.