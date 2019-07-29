# Generate machine learning model pipelines to choose the best model for your problem: AutoAI

## Introduction
It was inevitable to expect artificial intelligence, which facilitates every aspect of our lives, to facilitate its own development process. Building better models requires more complex, time-intensive and costly AI procedures, which requires expertise from cleansing the data to feature engineering, designing the architectures to parameter optimization. In order to ease this process and make it efficient in terms of time and effort, we need to automate these workloads. With the aim of creating AI for AI, IBM introduced the new service on Watson Studio called, AutoAI.

AutoAI is a service which automates machine learning tasks so that it eases the tasks of data scientists. It automatically prepares your data for the modeling, makes feature engineering on it, chooses the best algorithm for your problem and creates pipelines for the trained models.


## Learning Objectives

In this tutorial, the aim is to show the benefits of this service on a use case so that we can have a better understanding of how regression and classification problems can be handled without any code and how the tasks (feature engineering, model selection, hyperparameter tuning etc.) are done with this service. Then, the tutorial will include the details of how to choose the best model among the pipelines and how to deploy and use these models.

## Prerequisites

  * Sign up for an IBM Cloud account (This tutorial can be completed using an IBM Cloud Lite account)
  * Create a Cloud Object Storage service instance
  * Create a Watson Studio service instance
  * Create a Watson Machine Learning service instance
  * Basic knowledge of machine learning algorithms

## Estimated Time

This tutorial takes approximately 20 minutes to complete including the training part in AutoAI.

## Steps
IBM Cloud Lite account can be created by using this [link](https://cloud.ibm.com/registration). After completing the signing process, you can follow the steps below.

### Step 1: Create Required Service Instances

### i.	Object Storage
In order to store the data, we need a storage service which is going to be linked with our project later on. To do that:
*	Search for Storage in the [IBM Cloud Catalog](https://cloud.ibm.com/catalog?search=object%20storage&category=storage) or directly go to Storage tab from the left menu from the same page and click Object Storage service.

* From the upcoming page, optionally you can give a name to this service instance and click **Create**.

### ii.	Watson Studio
* Search for Studio in the [IBM Cloud Catalog](https://cloud.ibm.com/catalog?search=studio) and click the **Watson Studio** service tile.
*	As done with the Object Storage service, you can name your service and click **Create**.
*	After provisioning the Watson Studio service, click **Get Started** or directly go to [Watson Studio](https://dataplatform.cloud.ibm.com/) platform and login with your IBM Cloud account.

