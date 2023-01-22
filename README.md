# Spark-nlp-Pyspark
This project is focused on building a Spark ML Pipeline using Pyspark to perform natural language processing on a dataset. The pipeline uses the following annotators:

## Getting Started
To get started with the project, you will need to have Spark and Pyspark installed on your machine. Additionally, you will need to import the necessary libraries, including the pretrained models for English.

## Prerequisites
- [Apache Spark](https://spark.apache.org/)
- [Pyspark](https://spark.apache.org/docs/latest/api/python/)
- [Spark NLP](https://nlp.johnsnowlabs.com/)

## Installing
To install Spark and Pyspark, please follow the instructions provided on the respective websites. To install the Spark NLP library, you can use the following command in your Pyspark project:

` !pip install spark-nlp `

## Running the Application
The application is run by executing the script file containing the pipeline. The pipeline will read the input dataset, and it will print the transformed DataFrame showing only the POS column and the NER column. As a bonus, it will only show the result attribute of these annotations. The result attribute of NER and POS will be collected, and the relationship between found entities and their part of speech attributes will be analyzed and explained.
