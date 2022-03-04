# Capstone project: Sparkify
## Table of Content
1. [Motivation](#motivation)
2. [Installation](#installation)
3. [File Description](#files)
4. [Summary of the results](#results)
5. [Blog Post](#post)
6. [Acknowledgements & Licensing](#acknowledgements--licensing)

## Motivation <a name="motivation"/>
Churn analysis is a typical task in data science which everyone should have done when diving into the field of machine learning. Another important reason for me for this project was that I get familiar with Apache Spark. It is a very powerful tool for big data and therefore very popular.

As the final capstone project for the Udacity data science course I build three machine learning models with Pyspark to predict churn users from a music streaming application. The app is called Sparkify. The app and the user data are fictional. Users can play songs, like/dislike songs, add them to playlist and add friends. There is a free and a paid user level. They can upgrade, downgrade or cancel their service at any time. With the churn predicion users can get special offers or discounts before they cancel their service.

## Installation <a name="installation"/>
Python version 3.6 or higher is recommended.

The following packages are used:
* Pyspark SQL
* Pyspark ML
* Numpy
* Pandas
* Seaborn
* Matplotlib

## File description <a name="files"/>
The repository contains one Jupyter notebook as well as a html version of it.

## Summary of the Results <a name="results"/>
Historical data from 255 users is analysed. A Random Forest Classifier is used to predict churn users. The data is split into train, test and validation using a 3-fold cross validation. The figure below shows all feature importances.

![Feature Importances of Random Forest Model](https://github.com/LollaPie/Sparkify/blob/main/fig11.png)

Churn user have a shorter usage time than no-churn users. They use more GET requests like settings, about and help. They do not use the app on weekends as much as other users. And they get more advertisement then no-churn users. Locations of users or operating systems do not play an important role for churn prediction.

## Blog Post <a name="post"/>
Main findings and explanations can be found in my Medium post [here](https://medium.com).

## Acknowledgements & Licensing <a name="acknowledgements--licensing"/>
I give credits to Udacity to provide the course and the data. The course was the best online course I did so fare. I appreciate the "hands-on" methodology very much.
  
Feel free to use the code here as you would like. The data is provided by Udacity and it is not public.
