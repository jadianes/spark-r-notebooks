# SparkR Notebooks  

This is a collection of [Jupyter](https://jupyter.org/) 
notebooks intended to train the reader on different [Apache Spark](http://spark.apache.org/) concepts, from 
basic to advanced, by using the **R** language.  

If your are interested in being introduced to some basic Data Science Engineering concepts and applications, you might find [these series of tutorials](https://github.com/jadianes/data-science-your-way) interesting. There we explain different concepts and applications 
using Python and R. Additionally, if you are interested in using Python with Spark, you can have a look at our [pySpark notebooks]().    

## Instructions  

For these series of notebooks, we have used Jupyter with the [IRkernel](http://irkernel.github.io/) R kernel. You can find 
installation instructions for you specific setup [here](http://irkernel.github.io/installation/).  

A good way of using these notebooks is by first cloning the repo, and then 
starting your [Jupyter](https://jupyter.org/) in **pySpark mode**. For example, 
if we have a *standalone* Spark installation running in our `localhost` with a 
maximum of 6Gb per node assigned to IPython:  

    MASTER="spark://127.0.0.1:7077" SPARK_EXECUTOR_MEMORY="6G" IPYTHON_OPTS="notebook --pylab inline" ~/spark-1.5.0-bin-hadoop2.6/bin/pyspark

Notice that the path to the `pyspark` command will depend on your specific 
installation. So as requirement, you need to have
[Spark installed](https://spark.apache.org/docs/latest/index.html) in 
the same machine you are going to start the `IPython notebook` server.     

For more Spark options see [here](https://spark.apache.org/docs/latest/spark-standalone.html). In general it works the rule of passign options 
described in the form `spark.executor.memory` as `SPARK_EXECUTOR_MEMORY` when
calling IPython/pySpark.   


## Datasets  

#### [2013 American Community Survey dataset](http://www.census.gov/programs-surveys/acs/data/summary-file.html).  

Every year, the US Census Bureau runs the American Community Survey. In this survey, approximately 3.5 million 
households are asked detailed questions about who they are and how they live. Many topics are covered, including 
ancestry, education, work, transportation, internet use, and residency. You can directly to 
[the source](http://www.census.gov/programs-surveys/acs/data/summary-file.html) 
in order to know more about the data and get files for different years, longer periods, individual states, etc. 

In any case, the [first notebook](https://github.com/jadianes/spark-r-notebooks/blob/ma≈ster/notebooks/nb1-spark-sql-basics/nb1-spark-sql-basics.ipynb) 
will download the 2013 data locally for later use with the rest of the notebooks. 
There we will also load our first data frame and get to know each feature. A description of each of them can be 
seen [here](http://www2.census.gov/programs-surveys/acs/tech_docs/pums/data_dict/PUMSDataDict13.txt).  

The idea of using this dataset came from being recently [announced in Kaggle](https://www.kaggle.com/c/2013-american-community-survey)
 as part of their Kaggle scripts datasets. There you will be able to analyse the dataset on site, while sharing your results with other Kaggle
users. Highly recommended!  

## Notebooks  

#### [Downloading data and starting with SparkR](https://github.com/jadianes/spark-r-notebooks/blob/master/notebooks/nb0-starting-up/nb0-starting-up.ipynb)  

Where we download our data locally and start up a SparkR cluster.  



