
# Predictions on the existence of exoplanets 

## Project Description

In this project, I built and optimized the classification system to predict the existence of exoplanets and also analyzed the importances of dependent variables, based on 9500+ exoplanet disposition records from [Kaggle](https://www.kaggle.com/nasa/kepler-exoplanet-search-results).<br/><br/>

First, I performed basic data cleaning and data processing(scaling/dimensionality reduction/resampling) to prepare the data for modeling, and did the exploratory data analysis based on dependent variables and independent variables. <br/>Then, I built  logistic regression, SVM and random forest models, and further optimized model performances using `GridSearchCV`. <br/>Finally, I evaluated the final optimized model on the test set, and the test accuracy is 89.34%.



* All the project files are contained in this repo
* Tools/Languages: `Python(pandas, numpy, tensorflow, scikit-learn)`



## File Description

#### 1. `Resources`

* `cumulative.csv` contains the raw data obtained from Kaggle
* `cleaned_data.csv` contains the cleaned data


#### 2. `Static`
* `ETL_EDA.ipynb` contains the Python code for data cleaning, data processing (scaling/dimensionality reduction/resampling) and exploratory data analysis
* `pca_lda_test.ipynb` contains the Python code to check the performances of models based on PCA/LDA processed components
* `logistic_regression.ipynb`/`SVM.ipynb`/`random_forest.ipynb` contain the Python code for model training and model optimization process
* `logistic_regression.sav`/`SVM.sav`/`random_forest.sav` contain the optimized models
* `Test.ipynb` contains the Python code to check the performance of final optimized model on test set





