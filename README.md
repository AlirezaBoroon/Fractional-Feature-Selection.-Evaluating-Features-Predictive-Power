# Fractional Feature Selection. Evaluating Features Predictive Power
🤖 In a Machine Learning process, we need the Feature engineering and Preprocessing stages before training on the main mode. This repository approaches the Feature Selection based on 1-dimensional decision tree classifiers on (default) datasets to specifying the features predictive power for having only high score and relevant features.

---

> Feature selection is crucial in machine learning as it enhances model performance by identifying the most relevant features for prediction. Using 1-dimensional decision tree classifiers for feature selection is popular due to its simplicity and interpretability. This method calculates feature importance based on how much each feature improves node purity in the tree.

---

💡 The process involves training a decision tree on each feature, ranking them by performance, and selecting those with the highest predictive power for further training. This focus on informative features leads to better model interpretability and generalization.

📊 To demonstrate this approach, we can apply it to datasets and evaluate the performance of selected features. By obtaining a ranked list of features, we can identify which have the most influence on the target variable. Additionally, comparing model performance with and without feature selection allows us to assess the impact of using only relevant features. This method is especially valuable for datasets with many features, helping to reduce overfitting and enhance interpretability.
