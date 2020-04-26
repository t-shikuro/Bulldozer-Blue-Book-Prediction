# Blue Book for Bulldozers 
# 🚜 Predicting the Sale Price of Bulldozers using Machine Learning. In this notebook, I'll be exploring the goal of predicting an auction sale price for a piece of heavy equipment to create a "blue book" for bulldozers. 

#### -- Project Status: [Active]

## Project Objective 
How well can a prediction be made on the future sale price of a bulldozer, given its characteristics and previous examples of how much similar bulldozers were sold for? 

**Note:** The goal for most regression evaluation metrics is to minimize the error. For example, the goal for this project will be to build a machine learning model which minimises RMSLE.

## Data
The data is downloaded from the Kaggle Bluebook for Bulldozers competition: https://www.kaggle.com/c/bluebook-for-bulldozers/data

There are 3 main datasets:

* Train.csv is the training set, which contains data through the end of 2011.
* Valid.csv is the validation set, which contains data from January 1, 2012 - April 30, 2012 You make predictions on this set throughout the majority of the competition. Your score on this set is used to create the public leaderboard.
* Test.csv is the test set, which won't be released until the last week of the competition. It contains data from May 1, 2012 - November 2012. Your score on the test set determines your final rank for the competition.
* For more on the evaluation of this project check: https://www.kaggle.com/c/bluebook-for-bulldozers/overview/evaluation

## 4. Features

Kaggle provides a data dictionary detailing all of the features of the dataset. You can view this data dictionary on Google Sheets: https://docs.google.com/spreadsheets/d/18ly-bLR8sbDJLITkWG7ozKm8l3RyieQ2Fpgix-beSYI/edit?usp=sharing


### Methods Used
* Python libraries - numpy, pandas
* Machine Learning - sklearn, `RandomForestRegressor()`, `XgBoost()`
* Data Visualization - matplotlib, seaborn
* Evaluation Metrics - __RMSLE__, MAE, R<sup>2</sup>
* etc.

### Technologies
* Python
* Pandas, jupyter
* XgBoost, SciKitLearn

## Project Description
(Provide more detailed overview of the project.  Talk a bit about your data sources and what questions and hypothesis you are exploring. What specific data analysis/visualization and modelling work are you using to solve the problem? What blockers and challenges are you facing?  Feel free to number or bullet point things here)

## Needs of this project

- frontend developers
- data exploration/descriptive statistics
- data processing/cleaning
- statistical modeling
- writeup/reporting
- etc. (be as specific as possible)

## Getting Started

1. Clone this repo (for help see this [tutorial](https://help.github.com/articles/cloning-a-repository/)).
2. Raw Data is being kept [here](Repo folder containing raw data) within this repo. Alternatively,  go into the cloned project folder and switch into the `data` directory using `cd data`.
* Download the data files from [Kaggle] https://www.kaggle.com/c/bluebook-for-bulldozers/data into the 'data' directory.
* Extract all of the `.zip` files you downloaded.
* Remove all the zip files by running `rm *.zip`.
* Switch back into the `bulldozer-prediction` directory using `cd ..`.

    *If using offline data mention that and how they may obtain the data from the froup)*
    
1. Data processing/transformation scripts are being kept [here](Repo folder containing data processing scripts/notebooks)
2. etc...

*If your project is well underway and setup is fairly complicated (ie. requires installation of many packages) create another "setup.md" file and link to it here*  

5. Follow setup [instructions](Link to file)

## Featured Notebooks/Analysis/Deliverables
* [Notebook/Markdown/Slide Deck Title](link)
* [Notebook/Markdown/Slide DeckTitle](link)
* [Blog Post](link)


## RESULTS:

**(Contacts) : [TED SHIKURO](https://github.com/t-shikuro[t-shikuro])(@slackHandle)** 

## Contact
* If you haven't joined the SF Brigade Slack, [you can do that here](http://c4sf.me/slack).  
* Our slack channel is `#datasci-projectname`
* Feel free to contact with any questions!
