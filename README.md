# linear-regression-analysis
1. Exploratory data analysis on insurance data set 

I first loaded the necessary tools used in the anaysis followed by loading in the insurance dataset. The data consisted of 1338 rows and 7 columns

To get a visual representation of the numerical data, I created a histogram of the columns by using hist() from matplotlib. BMI has a gaussian distribution while charges is positively skewed, where most charges are aorund the 0–15000 range. It can ben see that there is relatively almost same number of female and male customers, with not a significant difference between number of customers per region. It is also obvious that most of the customers are non-smokers and there were only few who have more than 3 children.


2. MAE, RMSE, and MSE.

Linear regression analysis done on insurance dataset and calculations to find Mean Average Error (MAE), the Mean Squared Error (MSE) or the Root Mean Squared Error (RMSE)

I first loaded the necessary tools used in the anaysis followed by loading in the insurance dataset. The data consisted of 1338 rows and 7 columns

created a heatmap for the dependent and independent variables which shows their correlation followed by spliting the data into features and target variables,spliingt the data into training and testing sets,training the linear regression model,making predictions on the target variable then and lastly evaluate the model's performance using mean absolute error,root mean squared error and mean squared error

3. Churn analysis

I want to classify the  observations as the customer “will churn” or “won’t churn” from the platform. A logistic regression model will try to guess the probability of belonging to one group or another. The logistic regression is essentially an extension of a linear regression, only the predicted outcome value is between [0, 1].

The dataset contains 10000 rows and 14 columns. I cleaned the data for ease of use by dropping unnecessary data and doing label encoding(refers to converting the labels into a numeric form so as to convert them into the machine-readable form)

Splitting the Data
Separating the data into a target feature and predicting features.

Train — Test — Split
We now conduct standard train test split to separate the data into a training set and testing set.

Building the model and predicting  future values.

Finally evaluating the models performance.
