# pyspark

This repository is an introduction to using pyspark for Big Data. This tutorial was taking from [guru99](https://www.guru99.com/pyspark-tutorial.html)

## Notes and Definitions:

1. Big Data
2. Apache Spark 
3. What is PySpark? 

## Tutorial Coverage

### Introduction
Spark is designed to work with Python, Java, Scala and SQL. 
Spark has a vast amount of built-in library (e.g MLlib) and can read a broad type of files.

PySpark provides an API that helps the developer/data scientist to circumvent writing parallel code that may end up having issues or being very complex. It essentially handles the tasks of multiprocessing. 

Spark works closely with structured data and allows real-time querying of the data.

### Installation

`conda install pyspark` should work given you are working in an python env. Otherwise see [instructions](https://www.guru99.com/pyspark-tutorial.html)

Initiation of SparkContext is also necessary. SparkContext is the internal engine that allows connections with clusters. It is needed to run an operation. 

Last Updated:
February 27th, 2022