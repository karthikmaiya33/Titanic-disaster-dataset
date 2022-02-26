# Data-Analysis-Titanic disaster dataset


The RMS Titanic sank in the early morning hours of 15 April 1912 in the North Atlantic Ocean, four days into her maiden voyage from Southampton to New York City. The largest ocean liner in service at the time, Titanic had an estimated 2,224 people on board when she struck an iceberg at around 23:40 (ship's time)[a] on Sunday, 14 April 1912. Her sinking two hours and forty minutes later at 02:20 (ship's time; 05:18 GMT) on Monday, 15 April, resulted in the deaths of more than 1,500 people, making it one of the deadliest peacetime maritime disasters in history. We are considering the dataset involving the details of people present on the ship.

## Project Synopsis

>> This repo contains Data Cleaning, Exploratory Data Analysis, and Data Visualization of Titanic disaster dataset taken from the Kaggle website [Click here](https://www.kaggle.com/).

-------------------------------
## Project Walk-through

### Data Collection

Titanic disaster dataset taken from the Kaggle website consisted of 12 attributes and 418 tuples, the attributes are:
 'PassengerId',
 'Survived',
 'Pclass',
 'Name',
 'Sex',
 'Age',
 'SibSp',
 'Parch',
 'Ticket',
 'Fare',
 'Cabin',
 'Embarked'

------------------------------


## Data Cleaning

After collecting the data, checked for the null and duplicate values present in the dataset to provide better accuracy of the result by removing it. Changes I made and what all variables & scripts I wrote:

    * Handled missing values in the Age column by equating average aged value in three distinct passenger classes [Pclass1, Pclass2, Pclass3] to the Age column.
    * Dropped Cabin column as it had more than 90% missing values
-------------------------------
## EDA {Exploratory Data Analysis}

* All the imported distributions from the data cleaning data-set, I looked at the distributions of the data and the value counts for the various numerical and categorical variables.
* Using **Matplotlib & Seaborn**, categorized and crafted a beautiful data visualisation charts & plots
* Below are a few highlights from the *Pivot tables, Barplots & HeatMaps*.

![image](https://user-images.githubusercontent.com/98012611/155846912-390531bc-40ba-4a80-84c3-60e28638aef1.png)

![image](https://user-images.githubusercontent.com/98012611/155846928-145b3c8f-7a0e-4bdf-af8f-0b82b198d2f5.png)

-----------------


## Resources Consumed for this project & where you can find them:

    Python Ver: 3.9.0
    Packages Used: Pandas, Numpy, Matplotlib, and Seaborn.

* Matplotlib Documentation: [Click here](https://matplotlib.org/3.1.1/api/_as_gen/matplotlib.pyplot.boxplot.html?highlight=boxplot#matplotlib.pyplot.boxplot)
* Seaborn Documentation: [Click here](http://seaborn.pydata.org/examples/many_pairwise_correlations.html)

-----------------------------
