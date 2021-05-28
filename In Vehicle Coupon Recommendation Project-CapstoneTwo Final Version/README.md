---
title: "Introduction"
author: "Shixin Li"
date: "5/28/2021"
---

![](pic/headPhoto.png)

## Introduction

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
This data was collected via a survey on Amazon Mechanical Turk. The survey describes different driving scenarios including the destination, current time, weather, passenger, etc., and then ask the person whether he will accept the coupon if he is the driver. I will apply this data set to train a supervised machine learning model to predict in what situation the drive will accept the coupon. 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
[For More Information, click here.](https://archive.ics.uci.edu/ml/datasets/in-vehicle+coupon+recommendation)


## Project Organization

##### file: 
* Project Proposal 

##### data:
* coupon_data.csv : data set after data warngling, removed the unique column, column with too much missing value(more than 50%), observations with missing... from the original data.
* coupon_data1.csv : data set after EDA
* coupon_data2.csv : data set after feature engineering, created dummy variables for categorial features, ready for model training. 

##### NoteBooks:
* 1.DataWrangling.ipynb
* 2.EDA.ipynb
* 3.Pre-processing & Training Data Development.ipynb
* 4.Model Selection.ipynb
* 5.Final Model-Support Vector Classifier.ipynb

##### reports:
* In Vehicle Coupon Recommendation Project Report.pdf : report of this project
* SupportVectorClassifierInfo.txt : information of the final model

##### pic:
* headPhoto.png
