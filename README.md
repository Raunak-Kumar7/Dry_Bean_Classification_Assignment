# Parameter Optimization of SVM
Assignment for UCS654

## About SVM and Parameter Optimization

Support Vector Machine or SVM is one of the most popular Supervised Learning algorithms, which is used for Classification as well as Regression problems. However, primarily, it is used for Classification problems in Machine Learning.

Some of the most important parameters of SVM such as kernel, C, and gamma can be changed in order to achieve a higher accuracy. This is called as Hyperparameter Tuning. 

We can perform this task using GridSearchCV for optimizing these parameters.

In this python file, I've used a Fitness Function to optimize the parameters.

## Dataset

The dataset for the project has been downloaded from the UCI Machine Learning Repository.
[https://archive.ics.uci.edu/ml/datasets/Dry+Bean+Dataset](https://archive.ics.uci.edu/ml/datasets/Dry+Bean+Dataset)

Seven different types of dry beans were used in this research, taking into account the features such as form, shape, type, and structure by the market situation. A computer vision system was developed to distinguish seven different registered varieties of dry beans with similar features in order to obtain uniform seed classification. For the classification model, images of 13,611 grains of 7 different registered dry beans were taken with a high-resolution camera. Bean images obtained by computer vision system were subjected to segmentation and feature extraction stages, and a total of 16 features; 12 dimensions and 4 shape forms, were obtained from the grains.


Number of Instances: 13611

Number of Attributes: 17

## Final Result Table

| Sample  | Best Accuracy | Best Kernel | Best Nu | Best Epsilon |
| -----   | ------------- | ----------- | ------- | ------------ |

| 1	| 0.30	| poly	| 8.54	| 5.85 |
| 2	| 0.61	| linear	| 6.57	| 6.46 |
| 3	| 0.50	| poly	| 4.53	| 2.14 |
| 4	| 0.53	| linear	| 7.54	| 6.45 |
| 5	| 0.29	| linear	| 1.96	| 1.63 |
|	6	| 0.46	| poly	| 4.51	| 6.15 |
| 7	| 0.47	| poly	| 0.17	| 5.41 |
|	8	| 0.39	| poly	| 9.84	| 5.97 |
|	9	| 0.64	| poly	| 7.24	| 9.23 |
|	10	| 0.40	| poly	| 5.05	| 3.99 |

## Convergence Graph
![Graph](https://user-images.githubusercontent.com/73169853/233138068-d4821a97-a21b-485c-8459-2172570d2cc0.png)

## Discussion
From the above graph, we can conclude that the model is well trained and parameter have been optimized due to the less gap between training and cross-validation curve.

The graph is made for the sample which has best accuracy. Sample 9 has the best accuracy of 0.64 having kernel = Poly, Nu = 7.24 and Epsilon = 9.23.

## Written By
Name : Raunak Kumar
  
Roll No. : 102017148

Sub-Group: 3CS7
