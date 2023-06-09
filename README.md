This project is aimed to build a linear regression model to predict the closing stock prices of a company based on its open price and volume.

Data
The dataset used in this project is stored in the 'b_dataset.csv' file. It contains 1000 rows and 3 columns including 'Open', 'Close' and 'Volume'. The data was collected from Yahoo Finance.

Libraries
To build and evaluate the model, we have used the following libraries:

pandas: to read and manipulate the dataset
numpy: for numerical calculations
matplotlib: for data visualization
sklearn.model_selection: for test-train-splitting the data
sklearn.linear_model: for building the linear regression model
Model Building Steps
We first loaded the dataset using pandas.read_csv() method.
Then, we defined the features and target variables.
We split the dataset into training and testing sets using train_test_split() method.
A linear regression model was built using LinearRegression() method and trained on the training dataset.
Predictions were made on the testing dataset using predict() method.
Finally, we evaluated the performance of the model using r2_score() method and plotted the actual vs predicted values as well as the residual plot.
Results
The model achieved a high accuracy with an R-squared score of 0.9996. The actual vs predicted values plot and the residual plot indicates that the model performed well on the testing dataset.

Conclusion
The linear regression model built in this project can be used to predict the closing stock prices of a company based on its open price and volume. However, it is important to note that the performance of the model may vary depending on the dataset used and other factors affecting the stock market.
