### A End-to-End Deployment of a Machine Learning Algorithm into a Live Production Environment

In this tutorial, we explore how to deploy a machine learning algorithm into a live production environment so that it could be “consumed” in a platform-agnostic way.  We'll start by using Jupyter Notebooks to develop a machine learning algorithm and progress to make it publicly available as a web application using Voila, GitHub and mybinder.

#### 1. Develop a Machine Learning Algorithm

Our first step is to develop the machine learning algorithm that we want to deploy. In the real world, this step involves many weeks or months of development time and lots of iteration across the stages of the data science pipeline.  For this tutorial, we will develop a basic ML algorithm as the main purpose of this tutorial is to illustrate how to deploy an algorithm for use by “consumers”.

Create a new directory and name it `drug_classification`.  This will be our project home directory.

We will use a drug classification [dataset](https://www.kaggle.com/prathamtripathi/drug-classification) from Kraggle. Having a [CC0: Public Domain](https://creativecommons.org/publicdomain/zero/1.0/) means that it has no copyright and that it may be used in our tutorial with no restrictions. 

Click on `Download` button and save the `archive.zip` in the project home directory created above.  Extract the dataset `drug200.csv` within the `zip` file, into the home directory.

![Download Drug Classification Dataset](https://github.com/hakngrow/drug_classification/blob/main/images/download.jpg)


The Python code to develop a predictive machine learning algorithm to classify drug prescriptions given a range of patient parameters is as follows: 
```

```
 
 [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/hakngrow/drug_classification/main?urlpath=%2Fclient.ipynb)
 
 .. image:: https://mybinder.org/badge_logo.svg
 :target: https://mybinder.org/v2/gh/hakngrow/drug_classification/main?urlpath=%2Fclient.ipynb
