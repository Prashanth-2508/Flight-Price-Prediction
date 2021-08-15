# FLIGHT PRICE PREDICTION
**To predict flight fare of various airlines.**

Airline companies use complex algorithms to calculate the flight prices for given various factors present at the particular time. These methods take financial, marketing and various social factors into account to predict flight fares.
Nowadays the number of people using flights has increased significantly. It is difficult for airlines to maintain prices since prices changes dynamically due to different factors. That’s why we try to use machine learning to solve this problem. This can help airlines by predicting what prices they can maintain. It can also help the customers to predict future flight prices and plan their journey accordingly.


## Data Overview:
It contains the train.xlsx excel format file contains the data related Airlines prices based on the various parameters.

- Downloaded the dataset from https://www.kaggle.com/nikhilmittal/filght-fare-prediction-mh
- train.xlsx

## Problem type :
Continuous changing the prices /fare of the flights depends on the various parameters. Price is the ground truth variable and independent variables for this dataset based on those parameters price is decided, so price is not fixed with one variable it is continuously changing.

Hence this problem is **Regression Problem**.

##  Used Tools :
    1. Jupyter Notebook.
    2. Python.
    3. Matplotlib, Seaborn.
    4. Numpy and Pandas are used.
    5. Sklearn modules used.
    6. Supervised machine learning algorithms.

## Procedure
### Data Pre-processing
Data Analysis for relation between the different features which finds the relations between the one feature to another feature to find the ground truth predictable.

### Data Splitting
After analysing the data by visualization and various statistical parameters and methods we splitting the data into train and test because first we train the data to ML model then we test the Model to test data.

### Production the Model
Building the various models, We train the model on various supervised regression machine learning algorithms. 

### Testing the Models
Testing the model by best models as mentioned as above.
Hyperparamter tuning the algorithms by Random search.
We got the best score by ***XGBoost and Random forest*** algorithms

### Performance of model
Evaluating the model by performance metrics to pick the best model accurately predicting the truth variables based on the train set.
After all performing the model we got the **0.843 score and R2 error of 0.857**

### Storing the Model
Store the model into standard format like JSON, PICKLE, SQL etc for the further process like building the web APIs or model deployments and testing.
