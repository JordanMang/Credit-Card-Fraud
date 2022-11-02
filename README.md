# Credit-Card-Fraud
## Introduction <br>
Fraud detection is becoming increasing more important each day. Credit card companies have to earn trust from their customers and it seems that every day fraudsters are working to break that trust. This project aims to locate the best model for detecting fraud through the use of pipelines and GridsearchCV. There are roughly 300,000 transactions in this dataset and of those only 500 are fraudulent transactions. You can gain access to the dataset through [Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud).<br>
## Methodology <br>
### Exploratory Data Analysis <br>
We have found that there is no missing data within this dataset and most of the data within the set had already been scaled as a way of keeping customer data private. The only two categories that had not been scaled were "Amount" and "Time" which I chose to scale using RobustScaler<br>
## Model Selection and Evaluation <br>
Through the use of pipelines and GridsearchCV I was able to search four models and many parameters for each to find the most accurate model. GridsearchCV allowed me to run over 250+ model iterations while manipulating the parameters of Logistic Regression, Random Forest, Gradient Boost and SVM. 
## Conclusion and discussion<br>
In conclusion, I was able to achieve an f1-score of .7 using just a basic Logistic Regression. More could be done to improve this score but as practicce it has served it's purpose. 
