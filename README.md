Title: Prediction of the Violent Crime per Population of a Community in the U.S.

**Datasets Summary**

The dataset to be used for this project is the USA Communities and Crime Dataset acquired from UCI machine learning repository [website](https://archive.ics.uci.edu/ml/datasets/Communities+and+Crime+Unnormalized). The dataset was created by Michael Redmond; Computer Science; La Salle University; Philadelphia, PA, 19141, USA from the 1990 US Census, 1995 US FBI Uniform Crime Report, 1990 US Law Enforcement Management and Administrative Statistics Survey, available from ICPSR at University of Michigan.

This dataset is a multivariate with a total number of 147 attributes and 2215 instances. The data of this sample is vague and requires a lot of attention on preprocessing. To perform exploratory analysis and build a better model we have considered another data set which acts as an extension of this data. It contains variables like state of county, coordinates of the community and frequency of different crimes that occur in that area.
Attribute Information: (141 predictive, 4 non-predictive, 2 potential goal)
non-predictive- state,countycode,communityname,fold
Goal- =(['ViolentCrimesPerPop', 'nonViolPerPop']
Descriptive stats- 'murders', 'rapes', 'robberies', 'assaults', 'burglaries', 'larcenies', 'autoTheft', and 'arsons’.

**Problem Statement**
- The U.S. is a country of 50 states covering a vast swath of North America plays a significant role in world trade and considered as one of the best countries to live in. America is the world’s largest national economy and leading global trader and  also unofficially considered as leaders of the world in trade industry. But unfortunately it is really not a good place to live thanks to the crime rate of the country. In the United States, the relationship between race and crime has been a topic of public controversy and scholarly debate for more than a century. The crime rate varies between different racial groups and communities. There are several other factors which can contribute to crime rate like population, percapita income etc. 
-	'murders', 'rapes', 'robberies', 'assaults', 'burglaries', 'larcenies', 'autoTheft', and 'arsons’ are registered as crimes in records. Based on magnitude or intensity of crime it is further classified as violent crimes and non-violent crimes. Our goal in this project is to 
- Identify which states has the highest crime rate and show cities of each state having the highest crime rate
- exploration of the crime estimators and indicate the best subset of features which contribute to the goal attribute i.e violent crime per population.
- Build suitable model which performs quantitative analysis on the problem.
