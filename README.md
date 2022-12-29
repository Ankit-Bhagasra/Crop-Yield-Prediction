# Crop-Yield-Prediction


Why ?
 Agriculture is a business with risk and reliable crop yield 
prediction is vital for decisions related to agriculture risk 
management.
 Understanding worldwide crop yield is central to addressing 
food security challenges and reducing the impacts of climate 
change.
 It can help achieve zero hunger, which is among the top of 
UN Sustainable Development Goals for the year of 2030.
 Prediction could be used by crop managers/farmers to 
minimize losses when unfavorable conditions may occur. Also 
gives farmers information that enables them to boost 
productivity.
Agriculture plays a critical role in the global economy. 
The Agricultural yield primarily depends on weather 
conditions (rain, temperature), pesticides.
The climatic factors include rainfall and temperature. They 
are abiotic components, including pesticides and soil, of 
the environmental factors that influence plant growth and 
development.
And accurate information about history of crop yield is an 
important thing for making decisions related to agricultural 
risk management and future predictions.


How ?
There is a Scalable , Accurate, and Inexpensive and 
a versatile method to predict crop yield i.e. 
‘Decision Tree Regressor’ OR ‘ Artificial Neural 
Network’
Decision tree builds regression or classification 
models in the form of a tree structure. It breaks down 
a dataset into smaller and smaller subsets.
 The final result is a tree with decision nodes and leaf 
nodes.
It can be used to solve both Regression and 
Classification tasks.


About the Project
 Name of the project – “Crop Yield Prediction”
 Programming Language used – Python
 Dataset – Crop Yield Prediction Dataset 
 Libraries used - Sklearn- Matplotlib-Seaborn- Pandas- Numpy
 Tool used - Jupyter


Objective
The main objective is to collect data that can be 
stored and analyzed for forecasting the crop yield.
The machine will able to learn the features and 
extract the crop yield from the data by using machine 
learning and data science techniques.
The output of this work can help farmers pick most 
suitable crops to be grown depending on the factors 
like season and area available with least possible 
chances of losses.


Implementation
Gathering and Cleaning the data
Data Exploration
Data Pre processing
Model Comparison and Selection
Prediction on custom inputs
Model Results
Conclusions


Gathering and Cleaning Data
 Importing required libraries.
 Crops yield of ten most consumed crops around the world 
and Pesticides used for each item was downloaded from 
FAO(Food And Agricultural Organization) website. 
 The collected data include country, item, year starting from 
1961 to 2016 and yield value.
 For this project rain fall per year information was gathered 
from World Data Bank.


Data Exploration
India has the highest yield production in the dataset.
India is the highest for production of cassava and 
potatoes.
 Potatoes seems to be the dominated crop in the 
dataset, being the highest in 4 countries.
There is no correlation between any of the colmuns
in the dataframe.


Data Preprocessing
 Data Preprocessing is a technique that is used to convert the 
raw data into a clean data set. Whenever the data is gathered 
from different sources it is collected in raw format which is not 
feasible for the analysis.
 Encoding Categorical Variables(Many machine learning 
algorithms cannot operate on label data directly. They require 
all input variables and output variables to be numeric).
 For that purpose, One-Hot Encoding will be used to convert 
these two columns to one-hot numeric array.
 Dataset contains features highly varying in magnitudes, units 
and range. We need to bring all features to the same level of 
magnitudes. This can be acheived by scaling.



Model Results and Conclusions
 The crop being potatoes has the highest importance in the 
decision making for the model.
 We see the effect of pesticides.
 India has the largest crops sum in the dataset. 
 If the crop is grown in India then comes rainfall and 
temperature. The first assumption about these features were 
correct, where they all significantly impact the expected crops 
yield in the model


Future Work
Crop Disease Detection And Prevention.
A generalized prediction model for various crops by 
considering other parameters like humidity and solar 
radiation can be developed.



Model Comparison And Selection
 The dataset will be split to two datasets, the training dataset 
and test dataset. Common splits are 70/30 or 80/20 for 
train/test. 
 The evaluation metric is set based on R^2 (coefficient of 
determination) regression score function. R^2 is a statistical 
measure between 0 and 1 which calculates how similar a 
regression line is to the data it’s fitted to. R^2 score shows 
how well terms (data points) fit a curve or line.
 Decision Tree Regressor has the highest R^2 score of 96% , 
Gradient Boosting Regressor comes second.




