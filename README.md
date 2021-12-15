# Hi my name is Nate <img src="https://user-images.githubusercontent.com/1303154/88677602-1635ba80-d120-11ea-84d8-d263ba5fc3c0.gif" width="28px" alt="hi">

[My resume can be found here.](Nathaniel_Jones_Resume2021.pdf)

I am a data science student at Kennesaw State Univerisity and will be graduating at the end of this year.   

Some of my interests include:
 * Deep Learning, Regression Analysis, Nonparametric Methods, Abstract Mathematics, Numerical Analysis, and Data Visualizations.  

The coding languages I currently use are Python, R, and SAS but I also know Java, HTML, and SQL.

| Contact me! |
|  ----------- |
| nathaniel.jones711@gmail.com |
| [LinkedIn](https://www.linkedin.com/in/nathaniel-jones-4bb52a82/) |

------------------------------------------------------------------------------------------------

## Current Projects
### ["Education Deserts and Where to Find Them"]() - R, Python
* Food deserts are defined as geographic areas where residents have few to no convenient option for securing affordable and health food. Researchers working for the USDA have found that low-income census tracts often intersect with food deserts ([Source](https://www.ers.usda.gov/data-products/food-access-research-atlas/documentation/)). Additionally, researchers at the Education Resources Information Center ([ERIC](https://files.eric.ed.gov/fulltext/EJ838811.pdf)) found the median distance that a student with a family income less than $30,000 is willing to travel for post-secondary school is 63 miles.
* This project seeks to use similar metrics to define areas where access to the post-secondary education system is limited to non-existent. The resources this project will use will be the 2022 update of CollegeScorecard dataset, the most recent version of the census data, and grocery store data provided by [Safegraph](https://www.safegraph.com/).
* I will spatially analyze the post-secondary institutions by the median number of miles a student in a certain income bracket is willing to travel. I will create buffers using the metrics found by ERIC and analyze the relation to the median income of the census tracts that fall into the radius of the created buffers.

### ["Regressing Federal Loan Borrowers"]() - R, Python
* It was found in previous projects that the number of federal loan borrowers was important in modelling. So this project will seek to regress and understand the relationship the percent of federal loan borrowers at an institution has with the institutions demographic, student population demographics, geolocation, and admission data.
* The goal will be to spatial analyze the features of the institutions with the surrounding areas. 

### ["Accrediting the Accrediting Agencies "]() - R, Python
* Interestingly, the Classification of Pell Insitutions found that the accrediting agencies of post-secondary institutions bifurcate the majority Pell institutions and the minority Pell institutions when classifying. This project will seek to understand the differences in loan outcome, academic outcome, geolocation, and institutional demographics for these accrediting agencies.   
* The goal will be to explore differences, similarities, and ultimatley understand the different parameters associated with each accrediting agency.

## Previous Projects
### ["Classification of Pell Institutions"](https://github.com/njones738/Classification-of-Pell-Institutions) - R, Python
* This project sought to continue in the pursuit of understanding the stewardship of low-income students by classifying Post-secondary institutions. 
* The models I created included the methods XGBoost, k-nearest neighbors, random forest, principal component analysis, and Logistic Regression.
* This project I used Python and R in VScode to clean and structure the data, to process the data for modelling, and to build models that classify Pell institutions. During the process, the packages used were Tidyverse, magrittr, feather, and ggplot2 in R and sklearn, scipy, scikitplot, xgboost, category encoders, feather, matplotlib, plotnine, numpy and pandas.

### ["Does the Pell grant come with a price?"](https://github.com/njones738/Does-the-Pell-grant-come-with-a-price-) - R
* I spatially joined together the Census shapefiles with the CollegeScorecard dataset 
* I analyzed the association between the typical amount of debt an independent student and a dependent student accumulates while attending school for each U.S. state.
* VScode was used with R packages that include tidyverse, sf, tidycensus, stringr, magrittr, ggplot, ggh4x, geofacet, and others.

### ["Access to Higher Education"](https://github.com/njones738/Access-to-Higher-Education) - R
* I conducted research on the CollegeScorecard dataset through parametric and nonparametric methods.  
* I studied the differences in US schools with either a majority or minority proportion of their student popluation receiving a Pell grant.
* Rstudio was used with tidyverse functions to clean the dataset of missing values and manipulate the data into usable information. Visualizations were created with ggplot methods

### ["Two-Layer Neural Network"](https://github.com/njones738/2L_NN) - Python
* I created a Multilayer Perceptron in Python as a class object to predict
whether an individual in 1994 earned $50,000 or more from Census data.
* I used functions in NumPy to define functions in a class that creates a 0,1, or
2-layer neural net from user input.
* Python was used with the Pandas and NumPy libraries, as well as the shuffle method from sklearn's utilities module.

### ["Using Logistic Regression to Build Credit Scores"](https://github.com/njones738/Using-Logistic-Regression-to-Build-Credit-Scores) - Python, SAS
* I created a model to predict a customer’s credit score by a binary predictor that
indicated whether a customer was considered a credit risk
* SAS procedures were used to conduct a logistic regression analysis to analysis
the profitability of models created in the process.
* In addition to SAS, I used Python to aid in deciding which parameters should have their missing values imputed and which should be dropped from the dataset.

## GitHub Stats

[![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=njones738)](https://github.com/anuraghazra/github-readme-stats)