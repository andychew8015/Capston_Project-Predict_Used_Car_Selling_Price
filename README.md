# Capston_Project-Predict_Used_Car_Selling_Price
### To train a model that can predict the asking price for a particular used car:
- using web-scraping technics to collect dataset from https://www.stcars.sg/singapore-car/used-cars/search/
- using Lazy Predict Library to get a few best performed base model and perform Hyperparameter Tuning
### Required Library:
- [Lazy Predict](https://pypi.org/project/lazypredict/#description)
- [Selenium](https://anaconda.org/conda-forge/selenium)
- Scikit-Learn
- Pandas
- Numpy
### Result:
- We got a model that can predict the price with a MAPE (Mean Absolute Percentage Error) of 3.25%
