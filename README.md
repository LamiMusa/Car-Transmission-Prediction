# Car-Transmission-Prediction
The purpose of this project is to identify the type of transmission a car has, to decide what kind of car to get. It uses several factors to determine this fact. 

In an instance where  a buyer is looking to get a car but is unable to decide the kind of car or the transmission of it. The factors can used to decide what the transmission of the car is going to be based in the particular kind/ brand of car. 
This model is for cases where a decision is to be made in the kind /transmission of a car based in some factors 

The model uses python as the support language on Apache Spark for its development.
This project work uses a Decision Tree Classifier and a Linear Regression Model that works through an algorithm in order to predict a classification variable in the dataset.
The decision tree is a popular method for machine learning classification. On the Pyspark work frame,  decision tree classifier is needed and imported and the use of a Multi Class Evaluator is also necessary so as to evaluate the results gotten from the classifier.
The String Indexer and Vector Assembler are both required in this prediction. The String Indexer is used  to convert categorical variables into index numerical variables as the classifier can only run numerical variables. The target variable in this prediction will be required to be indexed. A Vector Assembler is used to select the independent variables that will be used for the prediction and assemble them as one variable.

The algorithm for this will be used for a multi class classification.

The entire operation uses Google Colab which allows writing and executing codes through browser and will be used for the process of the modelling. 
On Google Colab, pyspark is first installed and and the SparkSession class is imported and used to create a new spark context.
The data was cleaned of all null values as it is a necessity in order for the algorithm to be properly carried out.
