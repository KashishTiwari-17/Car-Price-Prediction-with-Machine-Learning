# OIBSIP_Data-science_task3
# Objective of the Task
The aim of this project is to develop a machine learning model that accurately predicts the selling price of a used car based on various input features such as present price, kilometers driven, fuel type, transmission, number of owners, and the car's age. The model uses a combination of data preprocessing, feature engineering, and regression algorithms, with a focus on performance optimization and user interaction.

# Steps Performed
1. Data Exploration and Visualization
Loaded the dataset from a CSV file.
Inspected data structure, checked for missing values, and reviewed basic statistics.
2.Visualized:
 Selling Price distribution
 Year-wise car distribution
 Fuel type and transmission distribution
 Correlation matrix of numerical features
3. Data Preprocessing and Feature Engineering
Removed irrelevant features (Car_Name) and transformed Year to Car_Age.
Applied StandardScaler to numerical features.
Applied OneHotEncoder to categorical features (Fuel_Type, Selling_type, Transmission) using ColumnTransformer.
4. Model Training and Evaluation
Trained and evaluated multiple regression models:
Random Forest Regressor
Gradient Boosting Regressor
Linear Regression
5. Evaluation Metrics:
Root Mean Squared Error (RMSE)
R² Score
6. Hyperparameter Tuning
Applied GridSearchCV to find the best hyperparameters for the Random Forest model.
The best model was saved using joblib as car_price_predictor.pkl.
6. Interactive User Prediction Tool
Created a command-line interface for users to input car details.
Predicts and displays the expected selling price using the trained model pipeline.
# Tools & Technologies Used
1. Language: Python 🐍
2. Libraries:
pandas, numpy – Data manipulation
matplotlib, seaborn – Visualization
scikit-learn – Model training, preprocessing, evaluation, and hyperparameter tuning
joblib – Model saving/loading
3. Models: Random Forest, Gradient Boosting, Linear Regression
4. Environment: Jupyter Notebook / Google Colab / Any Python IDE
# Outcome / Results
✅ Achieved high prediction performance with Random Forest (best RMSE and R²).
🧠 Final model pipeline includes full preprocessing and is production-ready.
🧪 Users can interactively enter car details and get predicted prices instantly.
💾 Best model is saved as: car_price_predictor.pkl
