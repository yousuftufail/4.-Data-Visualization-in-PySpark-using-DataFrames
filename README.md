# Data-Visualization-in-PySpark-using-DataFrames

Two examples of dataframe (constructed through spark) plotting are presented. These examples are taken from DataCamp.

# important libraries

import findspark
findspark.init("path_to_hadoop 3.2")

from pyspark import SparkConf

from pyspark.context import SparkContext

from pyspark.sql import SparkSession

spark=SparkSession.builder.getOrCreate()
