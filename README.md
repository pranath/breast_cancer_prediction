# Breast cancer prediction

## Introduction

In this project I will look at a dataset of patient data relating to breast cancer, which is available on Kaggle as the [Wisconsin Breast Cancer dataset](https://www.kaggle.com/uciml/breast-cancer-wisconsin-data). 

The dataset features are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. They describe characteristics of the cell nuclei present in the image in the 3-dimensional space is that described in: K. P. Bennett and O. L. Mangasarian: "Robust Linear Programming Discrimination of Two Linearly Inseparable Sets", Optimization Methods and Software 1, 1992, 23-34.

The dataset was released in November 1995 and the original source can be found [here](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29). 

An example of images of cells that this data comes from of both malignant and benign tumors can be seen below.

![title](img/bc_cells.png)

I will develop a machine learning model that will aim to predict Malignant tumors with the highest accuracy.

## Key files

- [Jupyter notebook of analysis and ML model development](https://github.com/pranath/breast_cancer_prediction/blob/master/breast_cancer_prediction.ipynb)
- [Interactive topological network of breast cancer dataset](https://pranath.github.io/breast_cancer_prediction/tda_breast_cancer.html)

## Conclusion

In this project I looked at a dataset relating to breast cancer, and developed a model able to predict malignant tumors with a very high degree of accuracy (an F-score of 0.9957).

We have also gained an understanding of the reasons why our model is able to predict this well. Our earlier analysis showed the difference in morphology beween cell metrics for malignant v benign tumors, which could be seen visually in the images and were expressed in different distributions of values for particular feature measurements of the cells that we observed.

Our use of higher level analytical tools such as TDA also allowed us to gain a much better understanding of the dataset, in particular a better idea of the range of feature values that were typical for malignant and benign tumors as 'groups' within the dataset.
