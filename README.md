# SparkR Notebooks  

This is a collection of [Jupyter](https://jupyter.org/) 
notebooks intended to train the reader on different [Apache Spark](http://spark.apache.org/) concepts, from 
basic to advanced, by using the **R** language.  

If your are interested in being introduce to some basic Data Science Engineering concepts, you might find [these series of tutorials](https://github.com/jadianes/data-science-your-way) interesting. There we explain different concepts and applications 
using Python and R.  

## Instructions  


## Datasets  

#### [2013 American Community Survey dataset from Kaggle](https://www.kaggle.com/c/2013-american-community-survey).  

Every year, the US Census Bureau runs the American Community Survey. In this survey, approximately 3.5 million households are asked detailed questions about who they are and how they live. Many topics are covered, including ancestry, education, work, transportation, internet use, and residency. Although this data is public, we will us the file published on Kaggle.   


## Notebooks  

#### [SparkR basics: SparkSQL, Data Frames, and loading data](https://github.com/jadianes/spark-r-notebooks/blob/master/notebooks/nb1-spark-sql-basics/nb1-spark-sql-basics.ipynb)  

About starting up with SparkR and loading the [2013 American Community Survey dataset from Kaggle](https://www.kaggle.com/c/2013-american-community-survey).  

#### [Exploratory Data Analysis with SparkR](https://github.com/jadianes/spark-r-notebooks/blob/master/notebooks/nb2-spark-sql-eda/nb2-spark-sql-eda.ipynb)

More advanced use of SparkSQL and R in order to perform Exploratory Data Analysis on the [2013 American Community Survey dataset from Kaggle](https://www.kaggle.com/c/2013-american-community-survey).    

#### [Linear Models](https://github.com/jadianes/spark-r-notebooks/blob/master/nb3-linear-models/notebooks/nb3-linear-models.ipynb)  

Since version 1.5, SparkR allows the fitting of generalized linear models over DataFrames using the [`glm()`](http://spark.apache.org/docs/latest/api/R/glm.html) function. In this notebook we use that to make predictions in the [2013 American Community Survey dataset from Kaggle](https://www.kaggle.com/c/2013-american-community-survey). 

## Applications  

#### [Spark and R, powerful allies](https://github.com/jadianes/spark-r-notebooks/blob/master/applications/spark-and-r-powerful-allies.ipynb)  

A use case on how to use SparkR to process large datasets as part of our usual R Exploratory Data Analysis pipeline. Here we will be using other R ecosystem tools such as [ggplot2](http://ggplot2.org/), etc. to perform single and multiple variable analysis and visualisations on the [2013 American Community Survey dataset from Kaggle](https://www.kaggle.com/c/2013-american-community-survey). 



