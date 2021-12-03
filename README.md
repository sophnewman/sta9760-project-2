## Sophia Newman - 12/02/2021 

## STA9760 - Project 2

## Analyzing 10Gb of Yelp Reviews Data
### Project Overview
Project 2 challenges us to utilize a subset of Yelp's business, reviews, and user data and utilize what we have learned in class to analyze this data. Among the content discussed in class that will be covered in this project includes utilizing AWS EMR and S3 as well as Python and PySpark scripting.

### Dataset Description - [Link to Yelp Dataset](https://www.kaggle.com/yelp-dataset/yelp-dataset#yelp_academic_dataset_user.json)
For this project, we will be utilizing the 'Yelp Dataset' provided by Kaggle. This Kaggle link leads us to 5 datasets formatted in JSON that cover user data including the business, check-in, review, tips, and user datasets. Although, for this project we focused on utilizing the business, user, and review datasets. The data tracks Yelp user data across 8 metropolitan areas in both the U.S. and Canada. 

### Provisioning a Spark cluster on AWS EMR
In order to build and run our docker image, there are several different files that the image will reference:
## Cluster and Notebook Configs

![notebook](assets/notebook.png)

![cluster](assets/cluster.png)
