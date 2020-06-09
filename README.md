# Distributed-Training-on-Edge-Devices

This project aims to implement a proof of concept of distributed training on edge computing devices by training and update a shared machine learning model on multiple smartphones utilizing the current state-of-the-art technologies from existing researches. This project is divided into two phases, the first phase is on the literature review and the second phase for project implementation. In the first phase of this research project, we are providing the literature review of feasibility studies on the topic to gain sufficient research on the current state of the technology, previous researches, and findings. Besides the literature review on the topic, this report also provides the technical objectives and the statement for the second phase of the project.


# The steps to implement the project architecture are:

1.Create a notebook instance

2.Prepare the data

3.We need to store the learning model along with datasets in S3 buckets. Create an S3 bucket in the same region where the notebook instance is created. 

4.Split the data into train and test sets.

5.Train the model to learn from the dataBoto is the Amazon Web Services (AWS) SDK for Python. It enables Python developers to create, configure, and manage AWS services, such as EC2 and S3. Boto provides an easy to use API to AWS services.
Deploy the model.

6.Deploying the model on a server and create an endpoint that can be accessible

7.Evaluate ML model's performance

8.Integrating Amazon sagemaker endpoints into internet facing applications

  ## a.Create a SageMaker model endpoint
  b.Create a Lambda function that calls the SageMaker Runtime Invoke_Endpoint
  c.Create an API Gateway – Integration request setup
  d.Test with Postman
  
9.Terminate resources

10.Delete the Amazon SageMaker endpoint, training jobs and the objects in S3 bucket

