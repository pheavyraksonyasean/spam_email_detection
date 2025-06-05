"The model was evaluated using multiple classification metrics to ensure balanced and robust performance:

• Confusion Matrix: Visual representation of true positives, false positives, true negatives, and false negatives.
• Precision (Spam Accuracy): Measures how many predicted spam emails were actually spam.
• Recall (Spam Coverage): Measures how many actual spam emails were correctly identified.
• F1-Score: Harmonic mean of precision and recall, balancing both metrics.
• Cross-validation (5-fold): Used to assess generalization performance and avoid overfitting.
All evaluation was conducted on the test set after training, using sklearn.metrics."
