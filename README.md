# Online-Education-Student-s-Adaptability-Level

# Overview
This Python script demonstrates a comprehensive analysis of a dataset related to students' adaptability levels in online education. The analysis includes data preprocessing, feature engineering, neural network development, hyperparameter tuning, and the application of machine learning algorithms.

# Analysis Steps
1. **Importing Libraries**: Import necessary libraries for analysis.
2. **Loading the File**: Load the dataset from the specified file path.
3. **Profile Report**: Generate a profile report using the ydata_profiling library.
4. **Feature Engineering and Encoding Columns**: Encode categorical columns, perform one-hot encoding, and create age bins.
5. **Standardization/Normalization**: Scale and normalize features.
6. **Train-Test Split**: Split the dataset into training, testing, and development sets.
7. **Neural Network Development**: Build and train a sequential neural network model.
8. **Hyperparameter Tuning**: Experiment with different hyperparameters for improved neural network performance.
9. **Applying ML Models**: Apply decision tree, k-nearest neighbors, and random forest classifiers.
10. **Grid Search**: Perform grid search for hyperparameter tuning of ML models.

# Results
- The best-performing model is a Decision Tree classifier with an accuracy of 88.79%.
- Random Forest and K-Nearest Neighbors also show competitive performance after hyperparameter tuning.

# Conclusion
Machine learning algorithms, particularly Decision Tree and Random Forest, outperformed neural networks in predicting students' adaptability levels in online education.

# Instructions to Run the Code
1. Install the required libraries using `pip install -r requirements.txt`.
2. Execute the Python script.

