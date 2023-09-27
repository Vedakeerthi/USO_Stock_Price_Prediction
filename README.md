# USO Stock Price Prediction

## Table of Content
  * [Results](#results)
  * [Synopsis](#synopsis)
  * [Appendix](#appendix)
  * [Links](#links)
  * [Directory Tree](#directory_tree)
  * [Features](#features)
  * [Run Locally](#run_locally)
  * [License](#license)
  * [Technology Used](#technology_used)

## Results

| Method Used      | Result                              | 
| :---             | :----:                              |   
| ARIMA MODEL      | ![Results of ARIMA](Results%20of%20Arima%20Model.png) | 
| LSTM             | ![Results of LSTM](Results%20of%20LSTM.png)           | 

## Synopsis

United States Oil ETF Stock is forecasted from the period of 2018 to 2019, by using the previous year's data from the period of 2011 to 2018, I have considered both statistical and as well as machine-learning approaches, the dataset is scraped from an online website and with overall more information about the data, I have only considered the date and the close value of the stock, since with the help of those two data we are going to forecast the values and find out which approach have performed well.

So based on the given data,
#### Independent variable (X): Date
#### Dependent variable (Y): Close value for the stock of the particular date

Statistical Model : ARIMA

Machine learning model : LSTM

Data preprocessing : Pandas

Data visualization : Matplotlib

## Appendix

The requirement for developing this model is present in [requirements.txt](https://github.com/Vedakeerthi/USO_Stock_Price_Prediction/blob/main/requirements.txt) file.

The development of the model is present in [main.ipynb](https://github.com/Vedakeerthi/USO_Stock_Price_Prediction/blob/main/USO%20Stock%20Price%20Prediction.ipynb) file.

## Links

 - #### Dataset link : https://github.com/Vedakeerthi/USO_Stock_Price_Prediction/tree/main/Datasets
 - #### Github link : https://github.com/Vedakeerthi/USO_Stock_Price_Prediction
 
## Directory Tree <a name='directory_tree'></a>

```
├── Datasets
    ├── FINAL_USO.xls
├── LICENSE
├── README.md
├── Results of Arima Model.png
├── Results of LSTM.png
├── USO Stock Price Prediction.ipynb
├── requirements.txt
```
 
## Features

- Live prediction analysis.
- Forecasting for the future value with much better accuracy.
- Compatible for training model with other stock data.

## Run Locally <a name='run_locally'></a>

Clone the project

```bash
  git clone https://github.com/Vedakeerthi/USO_Stock_Price_Prediction.git
```

Install dependencies

```bash
  pip install -r requirements.txt
```

Start the server and run the file

```bash
  python USO Stock Price Prediction.ipynb
```

## License

[![GPL-3.0 License](https://img.shields.io/apm/l/atomic-design-ui.svg?)](https://github.com/Vedakeerthi/USO_Stock_Price_Prediction/blob/main/LICENSE)

## Technology Used <a name='technology_used'></a>

<a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> &nbsp;
<a href="https://scikit-learn.org/" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" alt="scikit_learn" width="40" height="40"/> </a> &nbsp;
<a href="https://www.tensorflow.org/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/tensorflow/tensorflow-ar21.svg" alt="scikit_learn" width="70" height="40"/> </a> &nbsp;
<a href="https://matplotlib.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/valohai/ml-logos/master/matplotlib.svg" alt="matplotlib" width="40" height="40"/> </a> &nbsp;

