# SageMaker immersion day

In this repository you will find examples of the three main usages of Amazon SageMaker.

1- Using managed containers: A managed SageMaker container with the algorithm and the environment. You only need to provide the data set and SageMaker will do the rest.

2- Script Mode: A managed SageMaker container provides the environment and creates an API for serving the model. You provide the algorithm in a custom python script. 

3- Bring Your Own Container: You create a custom container with the environment, the algorithm and all the necessary code to build an API to serve model predictions. 
