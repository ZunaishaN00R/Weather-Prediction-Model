# Weather Prediction Model
Utilizing a weather dataset from sklearn, this project employs the train_test_split method to partition the data for model training and testing. The model's accuracy is evaluated, providing insights into its predictive capabilities for weather conditions.

# Weather Prediction Model: Train-Test Split and Accuracy Evaluation

## Project Overview:
This project focuses on predicting weather conditions using a dataset obtained from sklearn. The goal is to train a logistic regression model, assess its accuracy, and demonstrate its capability in predicting whether it will rain today.

## Project Steps:
### Data Loading and Preprocessing:
- Loaded weather dataset from sklearn.
- Dropped unnecessary columns for simplicity.
- Encoded categorical features using LabelEncoder.
- Handled missing values using SimpleImputer with mean strategy.

### Train-Test Split:
- Utilized the train_test_split method to partition the dataset into training and testing sets (70-30 split).

### Logistic Regression Model Training:
- Instantiated and trained a logistic regression model on the training set.
- Applied imputation to handle convergence warnings.

### Model Accuracy Evaluation:
- Predicted rain_today using the trained model on the test set.
- Evaluated the accuracy of the model using the accuracy_score metric.

## Results:
The logistic regression model achieved an impressive accuracy of 98.18% on the test set, showcasing its effectiveness in predicting whether it will rain today.

*Note: The convergence warning indicates that the model may benefit from increasing the number of iterations or scaling the data.*

This project provides a comprehensive example of building a weather prediction model, including data preprocessing, model training, and accuracy evaluation. The high accuracy emphasizes the model's proficiency in predicting rain conditions.
