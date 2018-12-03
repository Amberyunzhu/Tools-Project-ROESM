# Tools-Project-ROESM
## What is it

This project aims at analyzing the stock market’s sensitivity to macroeconomic events such as Federal Reserve interest rate hikes and U.S./China trade disputes. The python script uses object-oriented programming (OOP) to process event and stock data in two csv files, and calculates the cumulative abnormal returns for the selected stocks in given periods. The theoretical background is explained in Prof. Binder’s paper from University of Chicago: https://link.springer.com/article/10.1023/A:1008295500105

The script then provides data visualization to demonstrate the events’ impact on individual stock level, industry level, and country level.  



## Group Name and Section

 - Group name: ROESM
 - Section 1 students: Yidan Chen (yc3535), Yunzhu Liu (yl4005), Jiachen Xu (jx2357)
 - Section 2 student: Andy Sheng (ds3622)


## Where to get it

The source code and datasets are currently hosted on GitHub at: https://github.com/Amberyunzhu/Tools-Project-ROESM

## Dependencies (Required packages)

 - Numpy
 - Pandas
 - Datetime
 - Fix_yahoo_finance
 - Matplotlib.pyplot
 - Matplotlib.gridspec
 - Statsmodels.api

## Installation Instruction
In most cases, we recommend you to install two packages below before running the class code.
```
!pip install pandas-datareader;

!pip install fix_yahoo_finance;
```

Other python packages have been listed in requirements.txt.

## Run Instructions

First, please download the two csv files and record their absolute paths. You will need to input the ***absolute file paths*** at the beginning of the Jupyter Notebook. Then you can continue to run the source code by simply hitting "SHIFT + ENTER".


