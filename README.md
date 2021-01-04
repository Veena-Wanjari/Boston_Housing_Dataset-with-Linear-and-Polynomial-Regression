__About Bostonhousing dataset__

The Boston housing dataset is a famous dataset from the 1970s.
Alongside with price, the dataset also provide information such as Crime (CRIM), areas of non-retail business in the town (INDUS), the age of people who own the house (AGE), and there are many other attributes that are available.

__Aim__:
In total, there are 506 samples and 14 feature variables in this dataset. The objective is to predict the value of prices of the house using the given features.

__Information available__:

* data : has all the inputs
* target: has house median values
* bostan_data: has all the details or data of housing dataset
* feature_names: ['CRIM', 'ZN', 'INDUS', 'CHAS', 'NOX', 'RM', 'AGE', 'DIS', 'RAD', 'TAX', 'PTRATIO', 'B', 'LSTAT']

__Steps Involved__:

1) Loading libraries
2) Augment new column
3) Data Preprocessing
- Replacing Missing values
- Dropping Misiing values
4) EDA
- Checking multicollinearity
- Dropping again few columns
- Use of scatterplot
5) Create a model
6) Split the data
7) Apply Linear Regression
8) Apply Polynomial Regression
9) Evaluate model with metrices 
