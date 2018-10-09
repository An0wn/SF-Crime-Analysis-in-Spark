# SF-Crime-Analysis-in-Spark

Performed spatial and time series analysis for a 15 year dataset of reported incidents from SFPD. 
•Build data processing pipeline based on Spark RDD, Dataframe and Spark SQL for big data OLAP. 

# Exploration of San Francisco Crime Dataset with Spark

### Data
[sf_data.csv](https://data.sfgov.org/Public-Safety/sf-data/skgt-fej3/data): a 15 year dataset of reported incidents from SFPD. 

### Required Frameworks/Libraries
- ``Spark`` environment 
- ``pyspark``
- ``matplotlib``
-  ``seaborn``

### Methods and Results
We load the csv file to a Spark RDD object and then convert it to a data frame. We perform data exploration and visualization in four parts:     
- count the number of incidents for each category
- count the number of incidents at each district
- count the number of incidents each Sunday at SF downtown
- visualize the spatial distribution of incidents and run a ``KMeans`` clustering algorithm

All the codes and explanations are shown in [crime.ipynb](crime.ipynb).
