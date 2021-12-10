### Introduction :

The face cream industry is currently experiencing huge growth, The Market looks set to skyrocket as people look for quick and easy solutions. and Price manipulation 
By doing web scrubbing from IHERB.com
### Data Description:
A model performance depends heavily on the data it was trained on . To acquire the data, we used web scraping on iHerb website. The features of the products dataset are the following:

Name: the name of the product.

Price : the price of product.

Ratings: the average rate of the product.

Reviews: the number of customers reviews on the product.

### The target : 
Price prediction 

### workflow:
After getting the data we start to clean them remove nulls values, review conversion . then the data need to feature engineering new column "Label_brand" .After that we started to explore the dataset and split the data into %60 train/%20validation, and %20 for the test. Finally we tried two types of models:

First one is linear regression :
The(Train) = 0.025

The (validation) = 0.049

The (Test) = 0.054

Second is Polynomial Regression :
The  (Train) = 0.038

The (validation) = 0.074

The (Test) = 0.090

As we can see here, for the polynomial regression which will give the best test value  than from Linear regression and fits the data

### Tools :
- Technologies: Python, Jupyter Notbook.
- Libraries: Pandas, NumPySeaborn, BeautifulSoup,Regression, Polynomal.
