# Data Analysis and Prediction on Certificate of Entitlement (COE) Prices

## 1. About

This main goal of this project is to analyze the trends and factors that are correlated to the price of COE. With the data given and the trends observed, models are trained to predict the COE Prices for Category A and B vehicles.

### Data used in this project `/data`

1. Results of COE Bidding Exercise <br> `bidding-results.csv`
2. Monthly Motor Vehicle Population <br> `motor-vehicle-population.csv`
3. Monthly New Registration Of Motor Vehicle <br> `new-registraion.csv`
4. Monthly De-registration Of Motor Vehicle <br> `deregistration.csv`
5. Monthly Consumer Price Index (CPI) for Transport <br> `CPI-transport.csv`

## 2. Getting started

### Requirements

```
pandas
jupyter
matplotlib
scikit-learn
seaborn
numpy
scipy
```

### Installation

1. cd to the directory where `requirements.txt` is located
2. create and activate virtualenv with `python=3.8`
3. install requirements <br>
   `pip install -r requirements.txt`

### 3. Files

#### `1.exploration.ipynb`

> Data exploration, visualization and analysis. <br>
> Explanation on the trends and correlations observed <br>

#### `2.model.ipynb`

> Data preparation for model training <br>
> Scripts for model training <br>
> Evaluation of models performance <br>
> Visualisation of models prediction <br>

#### `3.open_ended_questions.md`

> Discussion and explanation on metrics and evaluation <br>
