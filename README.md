# ![Zillow](https://github.com/rtlatimer/Zillow-Zestimate-Kaggle/blob/master/images/ZillowHomeValuePredictionModel.png)

## Project: Zillow Prize: Zillow’s Home Value Prediction (Zestimate)
### Can you improve the algorithm that changed the world of real estate?

### Summary

Zillow’s Zestimate home valuation has shaken up the U.S. real estate industry since first released 11 years ago.
A home is often the largest and most expensive purchase a person makes in his or her lifetime. Ensuring homeowners have a trusted way to monitor this asset is incredibly important. The Zestimate was created to give consumers as much information as possible about homes and the housing market, marking the first time consumers had access to this type of home value information at no cost.
“Zestimates” are estimated home values based on 7.5 million statistical and machine learning models that analyze hundreds of data points on each property. And, by continually improving the median margin of error (from 14% at the onset to 5% today), Zillow has since become established as one of the largest, most trusted marketplaces for real estate information in the U.S. and a leading example of impactful machine learning.
Zillow Prize, a competition with a one million dollar grand prize, is challenging the data science community to help push the accuracy of the Zestimate even further. Winning algorithms stand to impact the home values of 110M homes across the U.S.

The goal of this model is to improve the Zestimate residual error. More specifically, we are trying to minimize the mean absolute error between the predicted log error of a home and the actual log error.

### Install

This project requires **Python 2.7** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [seaborn](https://seaborn.pydata.org/)
- [SciPy](https://www.scipy.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [LightGBM](https://github.com/Microsoft/LightGBM)

You will also need to have software installed to run and execute a [Jupyter Notebook](http://ipython.org/notebook.html)

If you do not have Python installed yet, it is highly recommended that you install the [Anaconda](http://continuum.io/downloads) distribution of Python, which already has the above packages and more included. Make sure that you select the Python 2.7 installer and not the Python 3.x installer. 

### Code

Main code is provided in the `RLatimerZillow.ipynb` notebook file. 

### Run

In a terminal or command window, navigate to the top-level project directory `Zillow_zestimate_error/zillow` (that contains this README) and run one of the following commands:

```
ipython notebook RLatimerZillow.ipynb.ipynb
```  
or
```
jupyter notebook RLatimerZillow.ipynb.ipynb
```

This will open the Jupyter Notebook software and project file in your browser.

## Data

Zillow Zestimate Kaggle competition: https://www.kaggle.com/c/zillow-prize-1

**Features**

All features are described by the zillow_data_dictionary.xlsx