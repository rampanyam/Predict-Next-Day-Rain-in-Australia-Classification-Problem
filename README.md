# Predict-Next-Day-Rain-in-Australia-Classification-Problem
A Pyspark approach including , Data Cleaning, Curation, Feature Transformation, Selection, Data Modelling, and Model Selection on Rain Data from Kaggle.com


### About the Dataset:
This dataset contains about 10 years of daily weather observations from numerous Australian weather stations.

RainTomorrow is the target variable to predict. It means -- did it rain the next day, Yes or No?
This column is Yes if the rain for that day was 1mm or more.


### Where can this Data be Found?
https://www.kaggle.com/jsphyg/weather-dataset-rattle-package


## WHAT LIBRARIES WERE USED FOR THIS PROJECT AND WHY ?

#### 1) Spark Context :  
Spark Context is the entry point to the services of Apache Spark.This library is imported to initialize spark.

#### 2) Spark Session : 
Importing Sparksession to allow programming Spark with DataFrame and DataSets.

#### 3) SQL Functions

Importing SQL functions such as mean(),when(),col() etc.


#### 3) Feature Transformation : 

Importing feature transforemers  and estimators , such as  StringIndexer,OneHotEncdoer and VectorAssembler from pyspark.ml.features module.

#### 4) MultiClassificationEvaluator : 

MultiClassificationEvaluator  is used to calculate the accuracy. It accepts two columns , the 
raw Predictions and the label. 

#### 5) Classification Algorithms:

The Libraries DecisionTreeClasifier, RandomForestClassifier ,GBTClassifier,LogisticRegression are imported
from the pyspark.ml.classification for the Classification Algorithms.


#### 6) Matplotlib : 

The library Matplotlib is imported to plot the Bar Graph for the Accuracies.






# This Project is a nine-step process, and the steps can be listed as: 

 ##  Step 1 : Step 01: Import ​ pyspark ​ and initialize Spark
 ##  Step 02: Load the dataset and print the schema and total number of entries
 ## Step 03: Feature Selection:  Delete unnecessary columns from the dataset
 ##  Step 04: Identify Missing Data
 ## Step 05: Imputing Missing Data
 ## Step 06: Feature Vectorization using Vector Assembler 
 ##  Step 07: Dividing Into Training and Testing
 ## Step 08: Applying Various Models 
 ## Step 09: Selecting Best Model based on Metrics.
 
 
 
 
 
 


