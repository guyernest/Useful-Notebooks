# Useful-Notebooks

This is a repository for Jupyter notebooks that I'm using in my discussions and presetations to various audience. 
It is covering different topics from how to use Amazon AI set of APIs, to building your first neural network using PyTorch, or how to use SageMaker from efficently.

## Amazon AI Examples

The first journey to AI should start with using existing API that are able to solve many of the topics that we want AI to do, such as voice-to-text, text-to-voice, machine translation, natural language understanding and computer vision. [This notebook](https://github.com/guyernest/Useful-Notebooks/blob/master/AmazonAIDemos.ipynb) is showing how to use some of the Amazon AI services such as Polly, Translate, Rekognition, Comprehend and others and how to combine them together. 

## Boston Housing Example

This is a classical example of machine learning model from 1978. In [this notebook](https://github.com/guyernest/Useful-Notebooks/blob/master/Boston%20Housing.ipynb), we are loading the data from sklearn, exploring the data using a few graphs, building a linear regression model using sklearn, and then build a simple linear model using PyTorch which does better than the linear regression model.

## Chalice on Jupyter notebooks examples

Two notebooks with _hello_world_ and _hello_planet_ examples to demonstrate how to develop micro-services on AWS lambda directly from an interactive Jupyter notebook. Including development and local testing of functions, deployment to Lambda and API-Gateway, and testing the newly created REST API.


## XGBoost on SageMaker

This is a notebook that is designed to solve common confusions of using SageMaker. [This notebook](https://github.com/guyernest/Useful-Notebooks/blob/master/xgboost-on-sagemaker.ipynb) is showing
- how to load the data to the notebook on SageMaker, 
- how to use stardard libraries on the Jupyter notebook to explore the data, and 
- how to send the data to S3 to allow remote training using a training Job. 

Once the model is trained, it is showing 
- how to load to model back to the notebook to explore it with **feature importance** and other functionalities in the open source implementation, and
- how to build **confusion matrix** by calling **prediction locally** in the notebook instance 

Lastly, it is showing 
- how to call the deployed endpoint from the standard boto3 SDK and not from the SageMaker SDK. 
You can take that boto3 code and use it within a Lambda function or any other SDK and application. 
