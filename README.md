# Churn Modeling 
Binary classification using embeddings of categorical features.

#### Dataset:
The dataset used for this experiment is provided in https://github.com/sharmaroshan/Churn-Modelling-Dataset
Balance of Data: 
{1: 0.2037, 0: 0.7963}

### Pipelines:
1. Package categorical features together and separate those from numerical features.
2. Package each categorical features separately and separate from numerical features.

### Modeling:
Used both Tensorflow and Pytorch to achieve an 85% accuracy on test data. The aim was to compare the performance of these two packages on the same dataset. 

It would be nice to compare with the performance of tree-based models.


