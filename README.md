## Predicting the Survival of Titanic Passengers
This project creates a Machine Learing Model which predicts whether a passenger on the Titanic would have been survived or not.

### Workflow
* **Importing Data**<br>
Import all the necessary packages, get the train and test data from the folder into the notebook as Pandas dataframe.
* **Data Exploration**<br>
The dataset consists of different types of data. So, we need to convert a lot of features into numeric so that the Machine Learning algorithms can preocess them. Furthermore, the data has features having widely different ranges, that we will need to convert into roughly the same scale. We can also figure out some more features, that contain missing values (NaN=not a number).
* **Data Preprocessing**<br>
Data wrangling, preparing and cleansing the data are invloved in this step. For me, the factors likely to be involved in the survival of the passenger are Passenger Class (Pclass), Sex of the passenger (Sex) and Age of the passenger (Age). Drop all the columns apart from the three and survival. And we found missing values in the 'Age' column  which were substituted with mean value.<br>
* **Building Machine Learning Models**<br>
Now we will train several Machine Learning models and compare their results. We intend to do a classification and regression on a given set of features that we have extracted from data.<br>
* **Feature Importance**<br>
Measure the relative importance of each feature. The scores are computed automatically for each feature after training and scales the results. We will conclude from the model that Sex is a major factor in the survival of the passenger.

### Methods used to build the model
* Logistic Regression
* K-Nearest Neighbors
* Decision Trees
* Random Forest
* Support Vector Machines
