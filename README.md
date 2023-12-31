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

I plot the histograms of the features that I want to take a closer look. From the histograms we see that BMI is around 30. A lot of people do not spend that much, most expenses is between 0-10000 approximatelly and it decreases when it exceeds 10000 Dollars. There is a pretty much balanced data set when it comes to sex. The number of male and female are equally repsesented and lastly we seet that a lot of people do not smoke. Approximatelly 300 people smoke in this study.

![10](https://github.com/batuhan6/Medical-Insurance-Premium-Prediction/assets/32600613/be58a77d-b4bd-4b75-8fe5-76868d1d8c72)
![11](https://github.com/batuhan6/Medical-Insurance-Premium-Prediction/assets/32600613/ea05c16b-2ba1-4495-ac99-720aea3b8d5d)


Used Seaborn to plot pairplots.

![12](https://github.com/batuhan6/Medical-Insurance-Premium-Prediction/assets/32600613/20f505e9-8f27-47fc-ab9b-c302f273787a)
![13](https://github.com/batuhan6/Medical-Insurance-Premium-Prediction/assets/32600613/038822a5-6146-4a2e-9244-37b2eb3cd6d3)


Regression plot. We see that when age and BMI increase, expenses increase as well.

![14](https://github.com/batuhan6/Medical-Insurance-Premium-Prediction/assets/32600613/d4801d8f-c31c-4050-a10c-257ce7d1eb9c)


Correlation Matrix.

![15](https://github.com/batuhan6/Medical-Insurance-Premium-Prediction/assets/32600613/b057dab2-dbbb-4565-bb7b-5608c6bf1d95)


Heat map that shows all correlations. We see that there is a strong correlation 0.79 between charges and smoker. People who tend to smoke have likely to have more charges.

![16](https://github.com/batuhan6/Medical-Insurance-Premium-Prediction/assets/32600613/e3a3194c-d3c3-451b-bbf0-462af9df1d88)



## Create Training and Testing Dataset

Cleaning the data and make it ready to train machine learning model. Converting the data into a numpy array with a size of float32. I am doing this because I am going to feed the entire data to the machine learning model. Inputs categorized as x and output in y.  

Scaling the data, input and output. Before training machine learning model.

Splitting the data 20% for testing and 80% for training. 



## Train and Evaluate a Linear Regression in SCIKIT-LEARN



## Train and Evaluate an Artificial Neural Network-Based Regression Model
