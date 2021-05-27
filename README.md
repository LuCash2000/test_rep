# Sale of Shares Advisor
This is the student project "Stock Investing Advisor" which is part of the course "Programming - Introduction Level" by Mario Silic at the University of St. Gallen (HSG). The purpose of this project is a fundamental analysis of publicly listed companies in order to determine whether a stock is efficiently priced and should therefore be purchased. This is based on an automated process of calculating and analyzing future free cash flows (DCF analysis), which is industry standard across various industries. As this is a highly complex procedure that requires a considerable amount of time and expertise, we have tried to incorporate this process into a single tool to reduce the time consuming workload of every single investor. If you are curious to learn more about our approach, we encourage you to read on and experience our Stock Investing Advisor yourself!

## Table of Contents
- [Group Project Members](#group_project_members) 
- [Technical Information](#technical_information) 
- [Setup](#setup) 
- [Program Structure](#program_structure)
- [Disclaimer](#disclaimer) 


<a name="group_project_members"/>

## Group Project Members
- Lucas Jutzi
- Lukas Kevic-Niederer
- Katharina Ruschmann
- Samuel Weber


<a name="technical_information"/>

## Technical Information
- Python version: Python 3.8.5
- JupytherLab: Please refer to https://jupyter.org/install in order to install JupytherLab.
- Required libraries: ```numpy``` ```pandas``` ```yfinance``` ```pandas_datareader``` ```statistics``` ```datetime``` ```statsmodels.api``` ```matplotlib.pyplot```


<a name="group_project_members"/>

## Setup
In order to properly use our Stock Investing Advisor, it is essential to have installed the above listed libraries prior to running this program. To install the libraries, please use PowerShell in Anaconda with the following commands:
```
$ pip install numpy
$ pip install pandas
$ pip install yfinance
$ pip install pandas_datareader
$ pip install statistics
$ pip install datetime
$ pip install statsmodels.api
$ pip install matplotlib.pyplot
```


<a name="program_structure"/>

## Program Structure

### Step 0
Prior to getting started it is vital to install and import all the required libraries that are listed in the chapters above. Disregarding this step will lead to an incorrect execution of this program.

### Step 1

The first step is to enter the desired stock ticker (e.g. 'AAPL' for Apple Inc. or 'MSFT' for Microsoft Corporation). Please note that for some smaller companies there is not enough data available to value the stock based on a DCF valuation. 

### Step 2

In this section the program makes some assumptions that are essential for the excecution of the valuation process.


<a name="disclaimer"/>

## Disclaimer

This valuation model is based on the anticipation of future free cash flows. As with any intrinsic valuation method, it is essential to bear in mind that valuations are not equally applicable to all businesses. While some companies do not even meet the required criteria (e.g. generating positive cash flows), other companies' values are not directly linked to the generation of free cash flows (e.g. Tesla and other companies that are experiencing hype for various reasons). Therefore, it is important to consider the individual context of each company in order to correctly implement the output of this DCF valuation. The delivered value should never be considered as an isolated basis in any decision-making process.
