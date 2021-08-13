# Prophet_Forecasting

This application relies on the FbProphet package to an analyze the correlation between time series data (namely stock price, company revenue, and google search trends) and then forecast those results to predict future correlations with reasonable certainty.

---

## Technologies

This project uses the Python Programming language in a Jupyter Notebook as well as the following libraries
    
    - pandas
    - pystan
    - fbprophet
    - Hvplot
    - holoviews
    - datetime


---

## Installation Guide

To install you will want to pull the entire Prophet_Forecasting folder from github including its subfolder
    
    * Subfolder
        * Resources (the folder containing the csv data of the historical stock, revenue, and google trends info)
        * forecasting_net_prophet.ipynb (the jupyter notebook itself)
    * ReadMe (This file)


---

## How it works

1) First the user will open the forecasting_net_prophet.ipynb notebook in the Prophet_Forecasting folder (using google colab)
2) Then the user will simply run each cell in the notebook in order to get its output

    i) The app will read the search data into a dataframe and then determine usual monthly search data to best identify unusual patterns in hourly google traffic
    
    
    ii) Then it will examine the google trends data to for seasonality, plotting its findings with hplot

    
    iii) Then it will compare the search traffic to patterns in the stock price itself, focusing in on the stocks volatility and hourly return and finally examining the time series correlation between them.
    
    
    iv) It will then use fbprophet to create a time series model that forecasts patterns in the hourly search data
    
    
    v) Finally it will utilize fbprophet one more time to forecast future revenue while also looking for seasonality in historical data.
    





---

## Usage

Overall it should be a very simple application to use, all you need to do is open the forecasting_net_prophet.ipynb notebook in the Prophet_Forecasting folder and run each cell in order using the google colab interface.

To open google colab all you have to do is open a new tab in google chrome and go to colab.research.google.com and upload the forecasting_net_prophet.ipynb notebook.
You will also have to load the appropriate csv files into colab when prompted by the notebook


---

## Contributors

Colin Benjamin

Linkedin: [Colin Benjamin](https://www.linkedin.com/in/colinbenjamin/)
    
email: cbenjamin33@gmail.com

---

## License

MIT
