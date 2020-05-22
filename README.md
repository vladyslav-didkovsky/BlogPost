# BlogPost
# Table of Contents

1. [Installation](#ins)
2. [Project Motivation](#pro)
3. [File Descriptions](#fil)
4. [Results](#res)
5. [Licensing, Authors and Acknowledgements](#lic)

<a name="ins"></a>
# Installation

There should be no necessary libraries to run the code here beyond the Anaconda distribution of Python. The code should run with no issues using Python versions 3.*.

<a name="pro"></a>
# Project Motivation
Project Motivation

CRISP-DM Process
1. Business Understanding: From Business perspective there are many questions on how this infectious disease spreads around the world. This code helps in analysis current Corona situation in the world like reasons for Spread, Death Rates and Predicts Future Hotspots:

    *What is the global trend of the COVID-19 cases? Which countries suffer the most at the moment?

    *What is the impact of quarantine policy to the spreading of COVID-19 for each country?

    *What is the relationship between number of test to confirmed cases?

    *Which aspect of the country correlate most with COVID-19 cases and deaths?

    *What is the relationship between healthcare system of the country and COVID-19 cases and deaths?
    
2. Data Understanding：COVID19 dataset consists of 3 datasets(test,general and info). Datasets were investigated before any preprocessing.
3. Prepare Data: Including data cleaning, filling NAN value, one-hot encoding and MinMax preprocessing. Please refer to Preprocessing for detail.
4. Data Modeling: Used Data Visualization and Data Analyse methods to indentify the causes of COVID19 spreadings, I tried to built different types of formulas to analyze the best answer. Some other models are trained and compared as well beforehand. Please refer to */ipynb for detail.
Evaluate the Results: Result and discussion are published in [here](https://medium.com/@vladyslav.didkovsky/the-covid-19-riddle-why-does-the-virus-wallop-some-places-and-spare-others-896ca551a36a?sk=12959bc7e16d5abf09e6f7707efed29c).

<a name="fil"></a>
# File Descriptions

The full set of data is available here, while the updated data is available in Kaggle. There is a notebook available to answer the above questions.

<a name="lic"></a>
# Licensing, Authors, Acknowledgements

You can find the Licensing for the data and other descriptive information at the Kaggle link available [here](https://www.kaggle.com/sudalairajkumar/novel-corona-virus-2019-dataset) and also [here](https://www.kaggle.com/koryto/countryinfo). Otherwise, feel free to use the code here as you would like!
