This is a basic machine learning Decision Tree classifier built from scatch (in Python using Jupyter notebook) using Pandas, and NumPy — without any ML libraries like scikit-learn.
The model is trained on the UCI Adult dataset to predict whether an individual's income exceeds \$50K.

- Builds a decision tree from tabular data
- Entropy and information gain for splitting
- Recursive tree building
- Optional depth-based pruning to control model complexity (to prevent overfitting)
- Manual prediction function for new data
- Evaluation using F1-score and accuracy on test data

All code is implemented and runnable within a single Jupyter notebook. Data description availble in `data_description.txt`. Just load the training and test data CSVs (e.g., `adult_train_data.csv`, `adult_test_data.csv`) and run the notebook to see my analyses.
