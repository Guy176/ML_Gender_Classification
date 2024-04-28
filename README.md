Gender Classification Using Three Different Algorithms
This project focuses on classifying gender using three different algorithms. It encompasses data preprocessing, model training, and evaluation steps. Below is a structured overview of the project:

1. Loading Required Modules
pandas
numpy
scikit-learn
imbalanced-learn
xgboost
seaborn
2. Check for Missing Values
A function is defined to add missing values to the dataset. Three different imputation methods are applied to handle missing values:

Row Mean
Column Most Frequent
KNN Imputation
3. Preprocessing
Normalization is performed for each dataset after imputation using the three different methods.

4. Data Balancing
Two techniques, NearMiss and SMOTE, are applied to address class imbalance in the dataset.

5. Train-Test Split
The dataset is split into training and testing sets for each imputation method.

6. Training Models
Three different classification models are trained on the datasets:

Logistic Regression
XGBoost
Naive Bayes Classifier
Hyperparameter tuning is performed using GridSearchCV for each model.

7. Evaluation
The performance of each model is evaluated using accuracy scores and classification reports on both training and testing sets for each imputed dataset.

8. Conclusion
After evaluating the models, the best-performing model is identified considering factors such as overfitting, underfitting, and proper fitting. The classification report of the test set using the best model is printed.
