# Rock-Vs-Mine-Prediction-using-Logistic-Regression
The project refers to the prediction of the type of material it is, i.e., Rock or Mine.
Dataset overview:
The project uses the datset called "Sonar data.csv" which contains over 60 numerical features, each representing a measure of energy within a particular frequency band of the returned sonar signal.
The target variable is a categorical variable indicating whether the object is a Rock(R) or MIne(M).
Libraries used:
#### 1. Pandas : 
Pandas is an open source data analysis and data manipulation library for Python. Pandas is widely used for data cleaning, preparation, and analysis due to its powerful and flexible features. And to import a csv file, we use pandas as :
                            df = pd.read_csv("File_name.csv")
#### 2. Numpy : 
Numpy, short for Numerical Python, provides support for large multi-dimensional arrays and matrices along with a collection of mathematical functions to operate on these arrays efficiently.
#### 3. Sklearn : 
Sklearn, often referred as Scikit-learn, provides simple and efficient tools for data minng and data analysis. Sklearn is widely used for implementing various machine learning algorithms and techniques.
#### 4. sklearn.model_selection : 
Provides tools for model selection and validation, including cross-validation, grid search, and randomized search for hyperparameter tuning.
#### 5. sklearn.linear_model : 
It contains a variety of linear models, which are machine learning algorithms where the predicted output is a linear combination of the input features. These models typically used for both regression and classification tasks.
#### 6. sklearn.metrics : 
sklearn.metrics is a module that provides a wide range of functions for evaluating the performance of machine learning models. These metrics are used to assess the quality of predictions made by a modelon a given dataset. They are crucial for model selection, tuning and validation.
#### 7. Logistic Regression : 
Used for binary and multinomial classification problems. It predicts the probability of a categorical dependent variable belongs to a particular class.
