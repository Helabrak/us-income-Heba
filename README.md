# us-income-Heba

## Mission objectives

Our team was hired to make an automated bearing testing system and was asked to make a model to use in a scheduled maintenance system. A sample of the bearings in use of their new-fangled machine would be tested, and your model would predict whether a bearing is faulty or not.

We'll implement different classification algorithms in Python and choose the most appropriate algorithm.

![](/Visuals/bearing_explanation.jpeg)

# Installation

## Python version
* Python 3.9

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
             precision    recall  f1-score   support

           0       0.89      0.93      0.91     12435
           1       0.73      0.61      0.67      3846

    accuracy                           0.86     16281
   macro avg       0.81      0.77      0.79     16281
weighted avg       0.85      0.86      0.85     16281

|
             precision    recall  f1-score   support  | 
| --------------| -------- | ----------- |-------------|
|  0       0.89      0.93      0.91     12435 |
|  1       0.73      0.61      0.67      3846|
| accuracy                           0.86     16281
   macro avg       0.81      0.77      0.79     16281|
   weighted avg       0.85      0.86      0.85     16281



In the end, we can see that either the SVC or KNN models are the best performer with perfect scores of 1.00.
We choose KNeighbors as our model and made further analysis/visuals about its performance.

KNeighbors Classifier's confusion matrix
![](/Visuals/visual_confusion_matrix.png)<br>
KNeighbors Classifier's AOC
![](/Visuals/visual_AOC.png)

# Contributors
| Name           | GitHub                                                                              |
|----------------|-------------------------------------------------------------------------------------|
| Heba Elebrak | <a href="https://github.com/Helabrak">https://github.com/Helabrak               |



# Timeline
29/07/2021 - 03/08/2021
