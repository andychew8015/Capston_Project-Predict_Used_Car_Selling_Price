# Capston_Project-Predict_Used_Car_Selling_Price
### Introduction:
Due to the reduction of COE quota, we had seen an increase in the COE premium. As a result, more buyers are turning to the used car market. But the prices for a particular make and model can have a lot of difference in the used car market due to the a few reasons like:
-  How old is the car
-  Mileage
-  Number of owners etc

For this project, we would like to train a model to predict the price of the car so as to let buyers have a guide on how much is the car that they are looking at.
### Objective:
- to train a model that can predict the asking price for a particular used car
- using web-scraping technics to collect dataset from [Stcars](https://www.stcars.sg/singapore-car/used-cars/search/)
- using Lazy Predict Library to get a few best performed base model and perform Hyperparameter Tuning
### Required Library:
- [Lazy Predict](https://pypi.org/project/lazypredict/#description)
- [Selenium](https://anaconda.org/conda-forge/selenium)
- Scikit-Learn
- Pandas
- Numpy
### Result:
Because we are keeping all outliers in the dataset, MAP(Mean Absolut Error) will be the metric we are using to evaluate the model since MAE is robust to outliers.
We got a model that can predict the price with a MAPE (Mean Absolute Percentage Error) of 3.25%
