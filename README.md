
ABOUT THIS PROJECT:

In this project we are trying to perform Sentimental Analysis on the Ukraine Crisis dataset obtained from kaggle. Our Objective is to identify what are the sentiment of people in social media, mainly Twitter.

Our initial idea was to do Sentimental Analysis on live Twitter data using PySpark (Spark Structured Streaming) for which we have integrated our Juypter Notebook with Kafka but since Twitter has closed there free API we decided to make use of historical data from the kaggle which is also a Twitter data extracted by a user on the ongoing Russia-Ukraine crisis.

FOR THIS PROJECT WE HAVE USED:

Sentiment140 dataset for Academic purpose, which is used to build our supervised machine learning model.
Twitter data set on the ongoing Russia-Ukraine Crisis on which we have applied our sentimental analysis.
mongoDB for the storage of our data.
Regular expressions and UDF (User Defined Function) for data wrangling and feature extraction tasks.
NLP preprocessing for ML model construction.
Also, in the end we will be showing showing how use Spark UI and also a small demo on how we can produce and consume messages from Apache Kafka.

DATA SOURCES:

http://help.sentiment140.com/for-students

https://www.kaggle.com/datasets/bwandowando/ukraine-russian-crisis-twitter-dataset-1-2-m-rows

CHALLENGES FACED:

In this project we are dealing with unstructured data which is completely new to us.
Identifying a data source on which we can train our Supervised Machine Learning model.
Learning about NPL preprocessing and Text Analytics where we have used regular expressions.
Integrating mongoDB and Kafka with our Juypter Notebook.
Learning about how to use Spark UI including DAG (Directed Acyclic Graph) for debugging issues.
Tried to implement other ML models such as Decision Tree Classifier, SVM, Random Forest Classifier but we faced issue with respect to the executor driver memory and even when we increased to memory size to 50gb the issue was there.

FINAL NOTE:

We have tried our best to make sure that this project simulates the Real-Time scenarios. Also, we have used all the things we learned in the class such as NoSQL DB for storage, PySPark for Analysis, SparkML for making predictions and finally storaging back our final results into NoSQL DB.

This archicture can be used to perform sentimental analysis on other data source either streaming data sources like Reddit or on historical data source.

References:

https://developer.hpe.com/blog/streaming-ml-pipeline-for-sentiment-analysis-using-apache-apis-kafka-spark-and-drill-part-2/

https://spark.apache.org/docs/latest/ml-classification-regression.html

https://spark.apache.org/docs/latest/ml-clustering.html

https://chat.openai.com/
