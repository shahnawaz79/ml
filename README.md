Decision Tree

Author: Shahnawaz Alam

Takes a training dataset, builds a decision tree and predicts the class of test data using the learned tree.
Training data file should be comma separated values. First column should be row id and last
column should be class.
Test file should be like the training file. Class column is not required in this file.
Information gain metric is also calculated for comparison.

python> import decision_tree as dt

tree = dt.train( training_data_file )
  
tree.print_tree()

d = dt.predict( tree, test_data_file )
  
