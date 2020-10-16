# Housing-price-estimation-
this is machine learning model using Decision Trees and search grid to estimate housing prices in Boston

# necessary libraries:
- Pandas
- Numpy
- Scikit-learn

# Features (independant variables) and output (dependant variable) used in this project:
- RM: Room Number
- LSTAT: ratio student to teachers in the neighberhood
- PTRATIO: Poverty ratio
- MEDV: the price = the output

# Steps of this project
- import all libraries
- load data and divide data into features and output using data.drop()
- Split data into training and test data
- Apply cross validation to avoid overfitting
- using the scoring function which is the coeffecient of determination R^2 as a performance metric
- use a search grid to find the optimal max depth of the decision tree applied
