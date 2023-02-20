# Boston Housing Dataset Analysis and Prediction
This is a simple Python code to explore the Boston Housing dataset and apply machine learning algorithms to predict housing prices. The code uses the following algorithms:

Linear Regression
Random Forest Regressor

## Prerequisites
The following libraries must be installed before running the code:

NumPy
pandas
matplotlib
seaborn
sklearn

## Dataset
The Boston Housing dataset is a built-in dataset available in the sklearn library. The dataset contains information about 506 census tracts of Boston in 1978. It includes 13 features such as crime rate, the average number of rooms, etc., and the target variable is the median value of owner-occupied homes in thousands of dollars.

## Data Preprocessing
The code performs the following data preprocessing tasks:

•Separate features and the target variable.
•Check for missing values.
•Compute correlation matrix and visualize heatmap and pairwise scatterplots.
•Split data into training and testing sets using train_test_split.


## Machine Learning Algorithms
The code uses the following machine-learning algorithms to predict housing prices:

•Linear Regression
•Random Forest Regressor


For both algorithms, a Pipeline object is created to scale the data and train the model. The models are trained on the training set and evaluated on the testing set using the following performance metrics:

•Mean Absolute Error (MAE)
•Mean Squared Error (MSE)
•R2 Score


## Results
The code outputs the performance metrics for both algorithms and stores them in a results DataFrame for easy comparison. Additionally, the code plots a scatter plot of the actual and predicted housing prices for both algorithms.
