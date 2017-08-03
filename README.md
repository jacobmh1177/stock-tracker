# stock-tracker
## Introduction
Welcome to your first python project! Today we will be building a nifty tool that will help 
you stay on top of your portfolio. Once we are done, you will be able to give your python 
program a file with the abbreviations for stocks you are interested in and it will return 
the current prices for each of the stocks. Ready? Let's get started!!

## General approach
Okay so the basic problem we are going to solve is this: How can we read in a file of stock
abbreviations and output each stock's current price? Let's break this problem down into two
parts:
1) Read a file of stock abbreviations
    * Checkout [this resource](http://www.pythonforbeginners.com/files/reading-and-writing-files-in-python) for how to read from
    file
2) Output each stock's current price
    * For now let's print out a stream of that looks like: APPL:$50
    
## Set up
Like C++ and Java you can use external libraries to help you write code. Before you can use
these modules you must first download them into your programming environment. For python,
you can use a module installer called pip. To load all the modules you'll need we will use
pip:

```pip install -r requirements.txt```

## About the starter code
* my_stocks.txt
    * This file is where you'll put the stock abbreviations of the stocks you're interested
    in. I've filled in some sample stocks so you can get a sense of how this file should be
    formatted. Notice that each stock abbreviation is on a new line.
* stock_tracker.py
    * This is where all your python code will reside. I've only filled in the import statements,
    so the rest is up to you!
* googlefinance
    * Your python program will be using the googlefinance python module which enables you
    to use google's finance api to get real-time stock prices. Please look [here](https://stackoverflow.com/questions/5081710/how-to-create-a-stock-quote-fetching-app-in-python) for 
    examples on how to use this module.

## How to run
To run your python program use the following command:
```python stock_trader.py```

