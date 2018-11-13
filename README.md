# AzureML
Construct a decision tree for abalone dataset. Clustering the dataset using K Means on attribute Plant Name based on their locations. Classification of the dataset using KNN on attribute Class Name.

## PROBLEM 1

**Objective**

Construct a decision tree for abalone dataset. Also,

1. Compare accuracy of the model for all the 29 classes with the accuracy provided with
    dataset for previous experiments.
2. Compare accuracy of the model by treating data set as a 3-category classification problem
    (grouping ring classes 1-8, 9 and 10, and 11 on) with accuracy provided with dataset.

**Total Classes in Dataset**

There are 29 ring classes in the given dataset.

**Methodology**

1. Tools Used: Microsoft Azure Machine Learning cloud computing platform and R
    programming language.
2. Features/Preprocessing:
     Apart from sex field all other are numerical so it is made categorical using meta data
       editor module.
     R script is used for grouping the ring classes for second problem.

**Results**

**Problem I: With 29 Classes**

```
A. Model
```
![](https://github.com/prakhardhama/AzureML/blob/master/snips/1.a.png)

B. Sample Tree

![](https://github.com/prakhardhama/AzureML/blob/master/snips/1.b.png)

C. Accuracy
Our Accuracy: **27 .5%**

![](https://github.com/prakhardhama/AzureML/blob/master/snips/1.c.png)

```
Accuracy Mentioned with dataset for previous experiments: 21~26%
```

![](https://github.com/prakhardhama/AzureML/blob/master/snips/1.c.i.png)

```
D. Confusion Matrix
```

![](https://github.com/prakhardhama/AzureML/blob/master/snips/1.d.png)

**Problem II: With 3 Groups**

```
A. R Script
```
![](https://github.com/prakhardhama/AzureML/blob/master/snips/2.a.png)

B. Model

![](https://github.com/prakhardhama/AzureML/blob/master/snips/2.b.png)

C. Sample Tree

![](https://github.com/prakhardhama/AzureML/blob/master/snips/2.c.png)

D. Accuracy
Our accuracy: **65.8%**

![](https://github.com/prakhardhama/AzureML/blob/master/snips/2.d.png)

```
Accuracy Mentioned with dataset for previous experiments: 59~65%
```
E. Confusion Matrix

![](https://github.com/prakhardhama/AzureML/blob/master/snips/2.e.png)


## PROBLEM 2

**Objective**

Clustering the dataset using K Means on attribute Plant Name based on their locations.

**Total Classes in Dataset**

There are 2 classes in the given dataset, one US and other is Canada.

**Methodology**

1. Tools Used: Microsoft Azure Machine Learning cloud computing platform and R
    programming language.
2. Features/Preprocessing:
     Fields with states as dengl (Denmark) and fraspm (France) are not included in
       clustering using Scrubber module.

**Results**

```
A. Model
```
![](https://github.com/prakhardhama/AzureML/blob/master/snips/3.a.png)

B. Result
Plants clustered in cluster 0: **16.8%**
Plants clustered in cluster 1: **83.2%**

![](https://github.com/prakhardhama/AzureML/blob/master/snips/3.b.png)

## PROBLEM 3

**Objective**

Classification of the dataset using KNN on attribute Class Name.

**Total Classes in Dataset**

There are 3 classes in the given dataset i.e. (49 balanced, 288 left, 288 right).

**Methodology**

1. Tools Used: Microsoft Azure Machine Learning cloud computing platform and R
    programming language.
2. Features/Preprocessing:
     Class name is made categorical using meta data editor.

**Results**

```
A. Accuracy
```
![](https://github.com/prakhardhama/AzureML/blob/master/snips/4.a.png)
```
B. Confusion Matrix
```
![](https://github.com/prakhardhama/AzureML/blob/master/snips/4.b.png)

**Note:** Interactive model and results are available in mhtml files.

