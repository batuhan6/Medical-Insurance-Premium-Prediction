# Medical-Insurance-Premium-Prediction-with-Machine-Learning

## Project Goal

The objective of this project is to predict the health insurance cost incurred by individuals based on their age, gender, body mass index(BMI), number of children, smoking habits, geo location.

The available features are:

* sex: Insurance contracter gender
* bmi: Body mass index (ideally 18.5 to 24.9)
* children: Number of children covered by health insurance
* smoker:  Smoking
* region: The beneficiary's resedential area in the US, northeast, southeast, southwest, northwest. 

Target(output):
* charges: Individual medical costs billed by health insurance.






## Project steps

1- Import Libraries and Datasets

2- Perform Exploratory Data Analysis

3- Perform Feature Engineering

4- Perform Data Visualisation

5- Create Training and Testing Dataset

6- Train and Evaluate a Linear Regression in SCIKIT-LEARN

7- Train and Evaluate an Artificial Neural Network-Based Regression Model


## Import Libraries and Datasets

![1](https://github.com/batuhan6/Medical-Insurance-Premium-Prediction/assets/32600613/991630e7-fdfa-4a1d-85fe-6a99abba14c8)

## Perform Exploratory Data Analysis

Checking are there any missing elements in the dataset. In this dataset there is no null value. 


![2](https://github.com/batuhan6/Medical-Insurance-Premium-Prediction/assets/32600613/0b2e0792-f26f-4cb5-a1b7-0bfdbcb2e4a1)


I grouped the data according to regions to see the relationships between region and charges. According to data south east region has the highest BMI and charges.

![3](https://github.com/batuhan6/Medical-Insurance-Premium-Prediction/assets/32600613/359cb8d4-2a26-48df-82b8-97ae14087d2d)


I grouped the data according the ages. Generally we see that when age increases charges increase as well.

![4](https://github.com/batuhan6/Medical-Insurance-Premium-Prediction/assets/32600613/1e49fe92-3e63-4934-bacf-25228c38b5e1)
![5](https://github.com/batuhan6/Medical-Insurance-Premium-Prediction/assets/32600613/35c51657-078b-424d-b987-f8eecb4f48fa)
![6](https://github.com/batuhan6/Medical-Insurance-Premium-Prediction/assets/32600613/db770162-e127-41fa-bd1a-9c2fe06ecb00)


## Perform Feature Engineering

Converting categorical variables(sex, smoker, region columns) to numerical.

![7](https://github.com/batuhan6/Medical-Insurance-Premium-Prediction/assets/32600613/1bcb1c44-d845-433e-a883-c3c04448c198)
![8](https://github.com/batuhan6/Medical-Insurance-Premium-Prediction/assets/32600613/a7be2c37-424a-40d4-a25e-e4a9eb3d632c)
![9](https://github.com/batuhan6/Medical-Insurance-Premium-Prediction/assets/32600613/ccab5863-d24b-484f-8685-940dbdbbdadf)



## Perform Data Visualisation

I plot the histograms of the features that I want to take a closer look.

![10](https://github.com/batuhan6/Medical-Insurance-Premium-Prediction/assets/32600613/be58a77d-b4bd-4b75-8fe5-76868d1d8c72)
![11](https://github.com/batuhan6/Medical-Insurance-Premium-Prediction/assets/32600613/ea05c16b-2ba1-4495-ac99-720aea3b8d5d)


## Create Training and Testing Dataset

## Train and Evaluate a Linear Regression in SCIKIT-LEARN

## Train and Evaluate an Artificial Neural Network-Based Regression Model
