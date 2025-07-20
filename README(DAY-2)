Import Libraries
Essential tools from pandas, sklearn, and numpy are imported for data handling, modeling, and evaluation.

Load Dataset
The original dataset is loaded using pd.read_csv().

One-Hot Encoding
Categorical columns like Gender, Country, JobRole, etc., are converted into numeric format using pd.get_dummies().

Feature Scaling
Numerical features are standardized using StandardScaler to improve model performance.

Define Features and Target

X = all relevant input features

y = target variable (BurnoutLevel)
Irrelevant columns like EmployeeID and BurnoutRisk are dropped.

Train-Test Split
Splits the data (80% train / 20% test) using train_test_split().

Train Models
Three regression models are trained:

Linear Regression

Ridge Regression (with L2 regularization)

Lasso Regression (with L1 regularization)

Evaluate Models
Models are evaluated using:

R² score (goodness of fit)

Mean Squared Error (MSE)

Mean Absolute Error (MAE)

Save Cleaned Data
The final preprocessed dataset is saved as day2_updated_mental_health.csv.
