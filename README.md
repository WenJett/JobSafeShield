# BT4012_Fraud_Analytics_Project
This is the Github repository for BT4012 Fraud Analytics group 26. 

## Dataset Description 
The dataset that is in use is from https://www.kaggle.com/datasets/shivamb/real-or-fake-fake-jobposting-prediction. 

The dataset consists of 18,000 job descriptions, of which 800 are fake in nature. This dataset can be used to train models to detect fake job listings posted, and help to flag them out as a preventive measure. These fake job listings may be used to scam potential job finders and potentially trick them of their money. It consists of 18 columns, which describes the nature of the job, salary, required level of experience and education and descriptions of the job requirements as well as information about the companies that are offering the position. The job posting descriptions are from worldwide and across different employment type in numerous industries, thus it will provide a holistic view of job postings.

## Problem Statement 
There are a few reasons why we decided to select this problem statement for our analysis. In particular, as soon-to-be graduates who are looking to find suitable roles in the job market, we are fully aware of the importance of job scams online. Therefore, we would like to explore ways to incorporate some algorithms that are able to handle the problem. 

In particular, we look to address these issues:

1. Addressing Unemployment and Job Scams:

Job scams have become an unfortunate part of the modern job-hunting process. Many individuals, especially those desperate for employment, can easily fall prey to these scams. By predicting and identifying fake job descriptions, we can potentially save countless job seekers from the heartbreak and financial costs associated with fraudulent job offers.

From employers’ point of view, they often spend considerable resources on recruitment. By reducing the noise of fake job listings, legitimate businesses can more efficiently reach and engage potential candidates, leading to quicker and more trustworthy hiring processes.

2. Enhancing Integrity in Online Job Platforms:

By ensuring that a platform's job listings are genuine, job seekers will have increased confidence when applying for positions. This can lead to a greater sense of security and trust in online job-seeking processes. As a result, online job platforms that can effectively filter out fake job descriptions will have a competitive edge over others. Higher trust also translates to higher user retention, more users, and potentially, greater revenue.

## File Descriptions

**ExploratoryDataAnalysis.ipynb**

This is the compiled script for our preliminary data analysis and exploration. It contains all the descriptive data analysis steps we taken in order to understand the data better. 

**TF-IDF_Script.ipynb**

This is the compiled script for our data preprocessing, feature engineering, model training and model evaluation steps applied on the dataset by utilising tf-idf vectorizer to convert our text data into numerical vectors.

**CountVectorization_Script.ipynb**

This is the compiled script for our data preprocessing, feature engineering, model training and model evaluation steps applied on the dataset by utilising count vectorizer to convert our text data into numerical vectors.

**Word2Vec_Data_Preprocess.ipynb**

This is the compiled script for our data preprocessing and feature engineering steps applied on the dataset by utilising Word2Vec Word Embedding to convert our text data into numerical vectors.

**Word2Vec_Model_Evaluation.ipynb**

This is the compiled script for our model training and model evaluation steps applied on the dataset by utilising Word2Vec Word Embedding to convert our text data into numerical vectors.
