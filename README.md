# 📊 Previsão de Estoque Inteligente na AWS com [SageMaker Canvas](https://aws.amazon.com/pt/sagemaker/canvas/)

## 1. Dataset imports
First we import all datasets thats gonna be used for this project.


## 2. Data Analysis
After the imports, we start to look at the data we collect so we can start to search for our target feature and check for missing values. After that we can select for how long we want to see our predictions, select brazillian holidays, select our id variable to predict values for a single item, than we can start building and predict our time series model.

## 3. Predictions
Finishing tyhe building, we get a MAPE of 0.149, a WAPE of 0.103, A RSME 0f 5.955 and a MASE of 0.310, looking at those we result, we can conclude that the model had a nice permormance. Cheking the columns impact, we can see that the column PRECO had a big impact on the predictions also the Brazilian holiday had a small impact as well.
