# Titanic_Classification

Project Title: Titanic Survivor Prediction Using Logistic Regression

Description:
This project aims to predict whether a person survived or not in the Titanic accident using Logistic Regression. The dataset contains information about passengers: age, sex, passenger class (Pclass), and embarked location (Embarked). We preprocess the data, convert categorical columns to numerical values, and train a Logistic Regression model to predict survival outcomes.

Procedure:

1)Data Loading: The Titanic dataset is loaded from the CSV file 'train.csv', containing information about passengers, including survival status (Survived).
Data Preprocessing: The dataset is explored to understand its structure and the presence of any missing values. We drop the 'Cabin' column, fill in missing values in the 'Age' and 'Embarked' columns, and replace categorical values in 'Sex' and 'Embarked' with numerical representations.

2)Data Visualization: We create various count plots using the Seaborn library to visualize the distribution of data and explore the relationships between features and survival.

3)Data Splitting: The dataset is split into features (X) and target labels (Y). We then split the data into training and testing sets using the train_test_split function from scikit-learn.

4)Model Training: A Logistic Regression model is initialized and trained using the training data. The fit method trains the model on the features and corresponding target labels.

5)Model Evaluation: The trained model is used to make predictions on both the training and testing sets. Accuracy scores are calculated for both datasets to evaluate the model's performance.

Technologies Used:
1)Python: The programming language used for the implementation of the project.
2)pandas, numpy: Libraries used for data manipulation and numerical computations. 
3)Matplotlib, seaborn: Libraries used for data visualization and plotting count plots.
4)scikit-learn: Library used for machine learning tasks, including data splitting and Logistic Regression model implementation.
