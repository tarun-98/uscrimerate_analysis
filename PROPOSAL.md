Project Proposal

**ITEC\_Pract\_05(Fri 7pm)\_Group F:**
Wasiu Oyeniyi Alimi (45540845), Bala Sai Tarun Goli (45786690), Jyoti Kumari (45771561), Aniket Pramanik (45714347)

**Project Title**
# Prediction of the Violent Crime per Population of a Community in the U.S.

**Summary**

Violence has been defined to be a physically harmful behavior carried out by an individual and directed against others. Thus, understanding why violent crime happens might predicted by knowing where the crime happens and what are the factors that favors the escalation of crime rate.

**Goals**

There are some important characteristics (such as population, race, unemployment, social background) to predict the level of violent crime and non-violent crime in a community, our goal is to explore these characteristics and determine the most influential on the level of violent crime in the community in order to predict the measure of violent crime of that community.

- Our project involves comprehensive exploration of the crime estimators and indicate the best subset of features which contribute to the goal attribute i.e violent crime per population. To do so we will be using RFE (Recursive Feature Estimation) Algorithm and identify appropriate features.
- We also intend to train neural network model that fits our problem. To avoid anomalies and issues that degrades our neural network model like Overfitting and vanishing gradient problem we intend to incorporate some noise to our layer by adding Dropout layers and choosing appropriate activation function for the problem.

**Datasets Summary**

The dataset to be used for this project is the USA Communities and Crime Dataset acquired from UCI machine learning repository [website](https://archive.ics.uci.edu/ml/datasets/Communities+and+Crime+Unnormalized). The dataset was created by Michael Redmond; Computer Science; La Salle University; Philadelphia, PA, 19141, USA from the 1990 US Census, 1995 US FBI Uniform Crime Report, 1990 US Law Enforcement Management and Administrative Statistics Survey, available from ICPSR at University of Michigan.

This dataset is a multivariate with a total number of 147 attributes and 2215 instances. The data of this sample is vague and requires a lot of attention on preprocessing. To perform exploratory analysis and build a better model we have considered another data set which acts as an extension of this data. It contains variables like state of county, coordinates of the community and frequency of different crimes that occur in that area. The per capita violent crimes variable was calculated using per community population and the sum of crime variables considered violent crimes in the United States: murder, rape, robbery, and assault in each community.

**Analysis Techniques**

The data set we get by integrating the above two mentioned datasets has lot of nan values and outliers. Our analysis adopts suitable strategies to deal with the nan values and remove the instances which contains the outliers. Later, we plan to use boxplot to identify outliers. Heat maps will be used on various crimes to indicate the measure of crime rate per 100k population of a particular state. We will also make use bar plots to compare different crimes for a state. In addition to heat maps and bar plots we intend to plot the coordinates of cities or counties for which the crime rate has been highest for different crimes like murders, rapes, robberies etc. To extract suitable features, we eliminate unnecessary redundant features using Pearson Correlation Analysis and other filtering methods for feature selection will be used. We will predict &quot;Violent crime per population&quot; by using Multinomial Regression and Neural networks. In order to improve the accuracy, we would normalize the data, cross validate, regularize or add dropout layers.

**Project Plan**

**Milestone#1 : Due Week 10**

Data Cleaning – Cleaning of the data of inconsistencies by Identifying outliers using boxplot, dealing with NaN values.

**Evaluation** : Verifying data contents and extracting relevant data from datasets. Preprocess data to establish error-free project base in GitHub .

**Milestone#2: Due Week 12**

Data analysis and exploration - This is where heat maps and bar plots will be used as explained in the analysis techniques

Feature Engineering - Feature Selection using filtering methods like Pearson Correlation Analysis (Correlation Matrix with Heat map) ,RFE .

**Evaluation** : Identify all python libraries, normalize, cross validate and manipulate data to improve accuracy and update jupyter Notebook in GitHub.

**Milestone#3: Due Week 13**

Predictive modeling- Multinomial Regression, Neural network

Strategies to improve accuracy- Normalizing data, cross validation, regularization or adding dropout layers.

**Evaluation** : Run tests and evaluate model. Complete and record all observations in GitHub.


