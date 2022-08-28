# Forecasting Net Prophet
This application analyzes [MercadoLibre's](https://investor.mercadolibre.com/investor-relations) financial and company growth by predicting google search traffic and how it correlates to the price of the stock.  A Prophet forecast model is used to
predict hourly user search traffic and any future company revenue.

---


## Technologies

This application leverages python 3.7 with the following libraries and packages:

* [Google Colab](https://colab.research.google.com) - An IDE that allows you to run Jupyter NOtebooks in the cloud.

* [pandas](https://github.com/pandas-dev/pandas) - A flexible and power data analysis/manipulation Python library used in financial calculations.

* [holoviews](https://holoviews.org/) - An open-source Python library designed to make data analysis and visualization seamless and simple.

* [numpy](https://numpy.org) - The fundamental package for scientific computing in Python.

* [prophet](https://facebook.github.io/prophet/) - A forecasting procedure implemented in R and Python.  It is fast and provides completely automated forecasts that can be tuned by hand by 
                                                   data scientists and analysts.

* [hvplot](https://pyviz-dev.github.io/hvplot/user_guide/Introduction.html) - Provides a high-level plotting API built on HoloViews that provides a general and consistent API for plotting data.

* [datetime](https://docs.python.org/3/library/datetime.html) - The datetime module supplies classes for manipulating dates and times.

* [matplotlib](https://matplotlib.org/) - A comprehensive library for creating static, animated, and interactive visualizations in Python.

---

## Installation Guide

Before running the application first install the following dependencies.

```python
!pip install pystan
!pip install prophet
!pip install hvplot
!pip install holoviews
```

---

## Usage

To use the forecasting net prophet application you must first launch Google Colab within the internet browser by going to the following internet address :

[Google Colab](https://colab.research.google.com)


Within Google Colab you should then be able to run and execute the following notebook:

``` python
forecasting_net_prophet.ipynb
```

---

## Contributors

Brought to you by [Drew Herrera](https://www.linkedin.com/in/drew94591).

---

## License

Licensed under the MIT License. Copyright 2022 Drew Herrera.
