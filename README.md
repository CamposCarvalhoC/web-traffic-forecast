# Web Traffic forecast/prediction
## Made by Cédric Campos Carvalho

### Description

Web Traffic prediction/forecast with the data coming from 145'000 wikipedia different articles by counting the number of visits every day since July 2015 to September 2017. This project makes a statistics analysis and shows two models based on different techniques (SARIMA and Wavenet).

### Installation

*Tested with python: `3.9.7`*

This projects contains the `requirements.txt` file with all the modules needed. To create the environment, follow these steps:

1. Go into the folder `web-traffic-forecast`.
2. Create a *python* environment:
```
python -m venv venv
```
3. Activate the environment:
<p style="text-align: center;">On <i>Windows</i>:</p>

```
venv\Scripts\activate.bat
```

<p style="text-align: center;">On <i>Linux/MacOS</i>:</p>

```
source venv\bin\activate
```

4. Install the *python* modules:

```
pip install -r requirements.txt
```

5. All files are stored in Jupyter notebooks.

### Source

[Web Traffic Time Series Forecasting on kaggle.com](https://www.kaggle.com/c/web-traffic-time-series-forecasting)
