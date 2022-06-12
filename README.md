# Simplest_Classification_in_Pyspark
I have performed classification algorithms on Iris dataset by using pyspark mllib models.

There are three classificatoin algorithms applied on Iris dataset.

So first of all, load the Iris csv dataset and change column names for better understanding.
Then, create a feature column using VectorAssembler function from pysprk mllib feature library.
Then, we are going to perform classification so create a label column using StringIndexer from pysprk mllib feature library as well.
Once, we have feature and label columns it is time to split dataset in training and testing data by 60% and 40% respectively.
Then, we will create a model of NaiveBayes, MultilayerPerceptronClassifier and DecisionTreeClassifier.

For evaluating these models, we will measure the accuracy using multiclassClassificationEvaluator.
