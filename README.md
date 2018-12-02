# Tools-Project-ROESM
## What is it

This project, based on the FFJR(1969), is to demonstrate stocks’ sensitivity to Fed interest rate hike and trade war events in python by measuring the cumulative abnormal return of target stocks in a given period. It aims to enable people to have a better understanding of the stock market turbulence and to become “calmer” investors.  

We used object-oriented programming (OOP) to contain data and code and leveraged the data analytical capability of several python packages, e.g. pandas, to analyze financial data such as return rates from Yahoo Finance. The python script will ask for several user inputs such as industries of interest, stock tickers, time period, events, etc. The script will then analyze the stock performance within the time period by regression of our model and highlight the impact of events using visualization packages, e.g. matplotlib. We in particular would like to investigate and demonstrate what kind of impact the market turbulence caused by those events will have on stocks by industries.


## Group Name and Section

 - Group name: ROSEM
 - Section: Three of four members are in section 1, who are Yidan Chen (yc3535), Yunzhu Liu (yl4005)  and Jiachen Xu (jx2357), and one of us is in section 2, who is Andy Sheng (ds3622).


## Where to get it

The source code is currently hosted on GitHub at: https://github.com/Amberyunzhu/Tools-Project-ROESM

## Dependencies

 - Numpy
 - Pandas
 - Datetime
 - Fix_yahoo_finance
 - Matplotlib.pyplot
 - Matplotlib.gridspec
 - Statsmodels.api

## Installation Instruction
```
!pip install pandas-datareader;

!pip install fix_yahoo_finance;
```

Other python packages have been listed in requirements.txt.


## Run Instructions

You need to input the ***absolute file path*** of the csv files you downloaded, and then ***RUN IT***!

***Notes***: If you want to try another data of your interested topic, please follow the format of our csv files e.g. ***Fed events v3.csv***.
