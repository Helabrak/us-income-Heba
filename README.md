# us-income-Heba

## Mission objectives

Predicting the income of every US citizen?
throuhg accomplishing the following: 
    Be able to analyze a machine learning problem
    Be able to reason about possible causes of overfitting
    Be able to remedy the causes of overfitting
    Be able to tune parameters of a machine learning model
    Be able to write clean and documented code.
    
    Must-have features
Baseline accuracy
Multiple evaluation metrics
Hyper parameter tuning
Some type of validation strategy

# Installation

## Python version
* Python 3.8

## Packages used
numpy
pandas
matplotlib
seaborn
%matplotlib inline
sklearn.model_selection 
sklearn.ensemble 
sklearn.metrics 

# Usage
| Filename                             | Usage                                                     |
|--------------------------------------|-----------------------------------------------------------|
| us_income final-checkpoint.ipynb | Jupyer Notebook file containing Python code


# Visuals
![image](https://user-images.githubusercontent.com/84380899/129574666-303a5fdf-fdcf-4277-abc8-fa3d3abba366.png)


# 


# Conclusion             
                   


| Random Forest | Precision| Recall      | f1-score    |support
| --------------| -------- | ----------- |-------------|-------------|
| 0 (75%-<=50K) | 0.89     | 0.93        | 0.91        | 12435       |
| 1 (25%->50K)  | 0.73     | 0.61        | 0.67        | 3846        |
| Accuracy      |          |             | 0.86        | 16281       |
| Macro avg     | 0.81     | 0.77        | 0.79        | 16281       |
| weighted avg  | 0.85     | 0.86        | 0.85        | 16281       |

We can see that the model needs improvment for the smaller proportion class (25% of those whose income is higher than 50K) 
So I shuffled the training and testing sets so that they have a random number of samples of each class training and testing data and that yield to higher accuracy
        Evaluating the model on the training set yields an accuracy of 99.99232186732186%
        Evaluating the model on the testing set yields an accuracy of 84.43%


# Contributors
| Name           | GitHub                                                                              |
|----------------|-------------------------------------------------------------------------------------|
| Heba Elebrak | <a href="https://github.com/Helabrak">https://github.com/Helabrak               |



# Timeline
13/08/2021 & 16/08/2021
