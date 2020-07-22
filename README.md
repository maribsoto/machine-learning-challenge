# Exoplanet Exploration
## Machine Learning Challenge

![exoplanets.jpg](images/exoplanets.jpg)

## Background & Scope
 
For more than nine years in deep space, the NASA Kepler space telescope has been out on a planet-hunting mission to discover hidden planets outside of our solar system.
To help process this data, I created 2 machine learning models capable of classifying candidate exoplanets from the raw dataset.
I followed the following steps:

    * Preprocess the raw data
    * Tune the models
    * Compare two or more models

### Data sources
* https://www.kaggle.com/nasa/kepler-exoplanet-search-results
* https://exoplanetarchive.ipac.caltech.edu/docs/API_kepcandidate_columns.html

## Screenshots from data pre-processing and tuning

### Principal Components Analysis

![corr_coeff.png](images/corr_coeff.png)

### Pairplot Displays

![pairplot.png](images/pairplot.png)

### Logistic Regression Model - Results

![LR_classif_rep.png](images/LR_classif_rep.png)
![LR_pred_results.png](images/LR_pred_results.png)

### K Nearest Neighbors Model - Results

![knn_classif_rep.png](images/knn_classif_rep.png)
![knn_plot](images/knn_plot.png)
![knn_best_score](images/knn_best_score.png)