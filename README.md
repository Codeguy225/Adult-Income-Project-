# Adult Income

## About Dataset 

The income dataset was extracted from 1994 U.S. Census database.

An individual's annual incom results from various factors. Intuitvely, it is influenced by the individual's education level, age, gender, occupation, and etc.

## Objective of the Project 

The goal of this machine learning project is to predict whether a person makes over 50K a year or not given their demographic variation. To achieve this, several classification techniques are explored and the random forest model yields to the best prediction result.

After understanding the problem statement, which is To calculate if the individual earns more than 50K dollars annually or less than 50K dollars annually, I make an assumption: the currency is in US dollars, and the period is one year

### Fields

The dataset contains 16 columns

Target filed: Income 

-- The income is divided into two classes: <=50K and > 50K

Number of attributes: 14

-- These are the demographics and other features to describe a person 

We can explore possibility in predicting income level based on the individual's information.

### Acknowledgements 

**Author:** Derek Overton

### Data:

This dataset named "adult income" is found in the UCI machine learning repository

http://www.cs.toronto.edu/~delve/data/adult/desc.html

The detailed description on the dataset can be found in the original UCI documentation

http://www.cs.toronto.edu/~delve/data/adult/adultDetail.html

## Methods

Before splitting the data, we will drop and duplicates, and check for any inconsistancies. This will help prepare our dat for machine learning. Then We identified the features (X) and the target (y). Then we performed a validation split. Next we created a preprocessing object to prepare the dataset for Machine Learning. We imputed missing values using the Simple Imputer after the validation split to minimize the chance of data leakage.

## Description of final model 

The Model I ended up using is Regression Forest Model. I used Gridsearch CV to find the best parameters to tune My best model for predicting Income greater than 50K. My best model ended up being a Regression Forest Model with an accuracty of 86%.  

## Recommendations:

More research and analysis on exploratory data analysis should be conducted to explore more detailed relationships (for example, classification analysis between income level and each occupation, regression analysis between age and capital-gain/loss etc).  My recommendation would be to get a more current dataset from which to build a model from that would be more reflective of today's society.  

## Limitations & Next steps 

The dataset is heavily white-based, it only can present the white-community not for the entire group in north america
the dataset is collected in 1994, the level of influence for each feature maybe changed since that time.

### For further information

For any additional questions, contact Email: Talented225@gmail.com
