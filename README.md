# Linear Regression Health Costs Calculator

The goal of this project is to build a regression model that predicts healthcare expenses based on personal information such as age, BMI, smoking status, and region. Additionally, it achieves a Mean Absolute Error (MAE) under $3500 on unseen data

## My Contribution
- Processed the data:
  - Converted categorical variables (sex, smoker, region) into numeric format using one-hot encoding
  - Split the dataset into 80% training and 20% testing sets
  - Separated the target variable (expenses) into **train_labels** and **test_labels**
 - Built and compiled a regression model using TensorFlow:
  - Input layer matched to the feature count
  - One or more hidden layers with ReLU activation
  - Output layer with a single neuron (for regression)
  - Loss function: **mae** (Mean Absolute Error)
  - Optimizer: **adam**
- Trained the model using the training data

## Strategy Summary
The project demonstrates the application of supervised learning (regression) to real-world datasets with both numeric and categorical features. The steps taken included:
1. Data preprocessing: Ensuring data is numeric and normalized
2. Model design: Simple dense network appropriate for tabular regression tasks
3. Training & validation: Avoid overfitting and aim for generalization
4. Evaluation: Use MAE to assess practical cost prediction accuracy

## Key skills developed
- Learned to handle mixed-type data (numerical & categorical)
- Gained experience with one-hot encoding, train/test splits, and model validation
- Built a working neural network regression model with TensorFlow
- Understood how to evaluate performance using Mean Absolute Error
