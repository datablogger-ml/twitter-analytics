# Twitter Analytics

## Getting Started

##### Step 1: Go to [Twitter Developers](https://developer.twitter.com/en/apps) and sign in with your account
##### Step 2: Select **Create an app** and specify the app name and description
![Create An App](https://raw.githubusercontent.com/datablogger-ml/twitter-analytics/master/TwitterAppScreenshots/Screenshot%202020-09-30%20at%2012.23.54%20PM.png)
![App name and description](https://raw.githubusercontent.com/datablogger-ml/twitter-analytics/master/TwitterAppScreenshots/Screenshot%202020-09-30%20at%2012.24.31%20PM%201.png)
##### Step 3: Once the app is created, go to the Keys and Tokens sections, copy your API keys and generate Tokens
![Access Token and keys](https://raw.githubusercontent.com/datablogger-ml/twitter-analytics/master/TwitterAppScreenshots/Screenshot%202020-09-30%20at%2012.24.53%20PM.png)
##### Step 4: Install the libraries used
##### Step 5: Follow along the jupyter notebook :grinning:

#### -- Project Status: Active

## Project Intro/Objective
The purpose of this project is to Scrape Twitter Data and Visualise the trend, topics and the sentiment, which is helpful in predicting the perception of the general public on some event/commodity.

### Methods Used
* Twitter Scraping
* Data Visualisation - WordCloud, Topic Modelling
* Natural Language Processing

### Technologies
* Python
* Python-Twitter API
* sklearn
* Pandas, jupyter
* matplotlib
* nltk

## Project Description
(Provide more detailed overview of the project.  Talk a bit about your data sources and what questions and hypothesis you are exploring. What specific data analysis/visualization and modelling work are you using to solve the problem? What blockers and challenges are you facing?  Feel free to number or bullet point things here)

### Twitter Data Scraping
The industrial production index (IPI) is a monthly economic indicator measuring real output in the manufacturing, mining, electric and gas industries, relative to a base year. It also measures capacity, an estimate of the production levels that could be sustainably maintained and capacity utilization.

It is expressed as an index level relative to a base year (currently 2012) ie. the percentage change in production relative to the base year (2012). In this specific problem, we would be looking at the ice cream and frozen desert IPI.

<a href='https://fred.stlouisfed.org/series/IPN31152N'>Download Link</a>

### Methods

#### 1. TES
#### 2. Data Visualisation

ARIMA (Autoregressive Independent Moving Average) is a combination of 3 models:
* <strong>WordCloud</strong> - a regression model that utilizes the dependent relationship between a current observation and observations over a previous period.
* <strong>Topic Modelling</strong> - uses differencing of observations (subtracting an observation from an observation at the previous time step) in order to make the time series stationary (constant mean -> No trend, constant variance).


## Needs of this project

- frontend developers
- data exploration/descriptive statistics
- data processing/cleaning
- statistical modeling
- writeup/reporting
- etc. (be as specific as possible)


## Featured Notebooks/Analysis/Deliverables
* [Notebook/Markdown/Slide Deck Title](link)
* [Notebook/Markdown/Slide DeckTitle](link)
* [Blog Post](link)
