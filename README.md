# Overview
A Spark project that preprocesses big data and perform linear regression. PySpark is the Python API for Apache Spark, which enables us to perform real-time, large-scale data processing in a distributed environment using Python.

# DBFS
We first create and query a table or DataFrame that we uploaded to DBFS. DBFS is a Databricks File System that allows us to store data for querying inside of Databricks. This notebook assumes that you have a file already inside of DBFS that you would like to read from.

# Data
The data contains the amount of tip given by a client which is caracterised by column properties. We wish to linearly regress this data.
