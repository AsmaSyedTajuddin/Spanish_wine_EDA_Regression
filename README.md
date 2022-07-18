# Spanish_wine_EDA_Regression

<img width="734" alt="Screenshot 2022-07-18 at 19 05 43" src="https://user-images.githubusercontent.com/100385953/179564916-d3e002c9-7ea7-4a01-be1a-282190b3c62e.png">

What to Expect?

In this notebook, we will explore the Spanish Wine Quality Dataset and fit a regression model on the price column. I will use Scikit-Learn, Pandas, Numpy, Seaborn and Matplotlib.pyplot in this notebook

Dataset Description

Context

This dataset is related to red variants of spanish wines. The dataset describes several popularity and description metrics their effect on it's quality. The datasets can be used for classification or regression tasks. The classes are ordered and not balanced (i.e. the quality goes from almost 5 to 4 points). The task is to predict either the quality of wine or the prices using the given data.

Content

The dataset contains 7500 different types of red wines from Spain with 11 features that describe their price, rating, and even some flavor description.

Attribute Information

winery: Winery name
wine: Name of the wine
year: Year in which the grapes were harvested
rating: Average rating given to the wine by the users [from 1-5]
num_reviews: Number of users that reviewed the wine
country: Country of origin [Spain]
region: Region of the wine
price: Price in euros [€]
type: Wine variety
body: Body score, defined as the richness and weight of the wine in your mouth [from 1-5]
acidity: Acidity score, defined as wine's “pucker” or tartness; it's what makes a wine refreshing and your tongue salivate and want another sip [from 1-5]
