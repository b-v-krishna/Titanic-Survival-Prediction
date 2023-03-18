# Titanic-Survival-Prediction

<h3>Problem Statement</h3>This project aims to predict whether a passenger on the Titanic survived or not, given a set of features such as PassengerId,Survived,Pclass,Name,Sex,Ticket,etc. The prediction model is based on logistic regression, a commonly used technique for binary classification problems.

<h3>Dataset Description</h3>
The dataset used in this project contains information about 891 rows and 15 columns of the passengers including their age, gender, ticket class, fare, cabin, etc. The target variable is a binary variable indicating whether a passenger survived or not.

<h3>Feature Engineering</h3>
Before training the model, some preprocessing steps were performed on the dataset to handle missing values and encode categorical variables.
<ul>
<li>Missing values in the Age and Embarked columns were filled using the mean and the mode of the respective columns.</li>
<li>Categorical variables such as Sex and Embarked were one-hot encoded to convert them into numerical variables.</li>
</ul>

<h3>Data Visualization</h3>
In data visualization we present a countplot of the number of survivors and non-survivors in the Titanic dataset. Countplot is a useful for displaying the distribution of a categorical variable. 
<h3>Model Training</h3>
The logistic regression model was trained using the preprocessed dataset. The training process involved splitting the dataset into a training set and a validation set, fitting the model on the training set, and evaluating its performance on the validation set.

<h3>Model Evaluation</h3>
The performance of the trained logistic regression model was evaluated using metric such as accuracy.The model produces 80% accuracy.
