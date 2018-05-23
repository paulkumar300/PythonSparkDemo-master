README:


Problem Statement :  To predict multi classification problem of Online Visitors data in slib data format available provided in 


Prerequisites:

	-Download Spark in C: Drive and configure environment variables as SPARK_HOME , HADOOP_HOME
    -Set up Jupyter notebook using Anaconda continium


Code Comments as per prgm execution:

1) Import statements for Spark ML Libraries
2) Applied Spark MLIB python code  in reading lib as Spark Data Frame
3) Initialise spark session
4) Train and test split on Data provided
5) Create Logistic regression instance and fit model on training set, Test using test data split
6) Checkout metrics like accuracy , f1 score metrics
7) Seems predictions are 100% correct , hence model is doing great