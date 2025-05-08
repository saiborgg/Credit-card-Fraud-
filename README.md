# Credit-card-Fraud-
This project applies machine learning to identify fraudulent credit card transactions using logistic regression, a widely used algorithm for binary classification. The dataset includes transaction features with a binary label indicating fraud or legitimate activity.

To improve data quality and reduce noise, preprocessing was performed using the groupby() function, allowing aggregation and summarization based on relevant features, This helped uncover patterns and reduce data imbalance or redundancy before model training.

Logistic regression models the probability of a binary outcome using a logistic (sigmoid) function. It is well-suited for binary classification tasks like fraud detection, where interpretability and probabilistic outputs are important. The model learns weights for each input feature to determine the likelihood of a transaction being fraudulent.

The effectiveness of the model is evaluated using accuracy_score, which quantifies the percentage of correctly classified transactions. While accuracy gives a basic measure of model performance, it is especially important in fraud detection to consider class imbalance and the potential for false negatives.

This project illustrates how foundational machine learning techniques can be applied to critical real-world challenges in financial security, providing insight into how models can assist in automated fraud detection systems.
