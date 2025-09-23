## Decision Tree Classifier

### Task:

1) Open and read data from the provided file. 

2) Determine and display the number of records and the number of fields in the loaded dataset.

3) Display the first 10 records of the dataset.

4) Split the dataset into training and test sets.

5) Using the appropriate functions of the scikit-learn library, build a decision tree classification model of depth 5 and train it on the training sample, assuming that in the given dataset the target characteristic is determined by the last column, and all others act as output arguments.

6) Represent the constructed tree graphically using the graphviz library.

7) Calculate the classification metrics of the constructed model for the training and test samples. Present the results of the model on the test sample graphically. Compare the results obtained when applying different splitting criteria: information gain based on entropy or Gini.

8) Find out the influence of the depth of the tree and the minimum number of elements in the tree leaf on the classification results. Present the results graphically.

9) Draw a bar chart of the importance of the attributes used for classification (feature_importances_). Explain how you think this importance can be calculated.
