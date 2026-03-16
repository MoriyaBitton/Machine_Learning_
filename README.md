# Machine Learning

This repository contains implementations and experiments from the **Machine Learning course**.

The projects explore several machine learning algorithms and evaluate their behavior on different datasets.

Algorithms implemented in this repository include:

- **Perceptron**
- **AdaBoost**
- **k-Nearest Neighbors (KNN)**
- **JL-transform**

Each exercise includes the implementation, datasets, and a report describing the experiments and results.

---

# Repository Structure

```
Machine_Learning_
├── Ex3
│ ├── data
│ │ ├── four_circle.txt
│ │ └── two_circle.txt
│ │
│ ├── Adaboost.py
│ ├── Answers - Adaboost.pdf
│ ├── Ex3 - 2022.pdf
│ ├── Perceptron.py
│ └── main.py
│
├── Ex4
│ ├── outputs
│ │ ├── Empirical Error.png
│ │ ├── Error.png
│ │ └── Total Error.png
│ │
│ ├── Knn.py
│ ├── hw4 2022.pdf
│ ├── main.py
│ └── two_circle.txt
│
├── Final_Project
│ ├── Final Project Project.pdf
│ ├── Final_Project_Machine_Learning.pdf
│ └── Project Graph Analysis.pdf
│
├── LICENSE
└── README.md
```

---
## Exercises Overview

### Exercise 3 – Perceptron & AdaBoost

This exercise implements two classical machine learning algorithms on synthetic circular datasets.

📄 [Assignment Description: Ex3 - 2022.pdf](./Ex3/Ex3-%202022.pdf)

#### Perceptron
Implementation of the **Perceptron algorithm** on the `two_circle` dataset (150 points).  
The model learns a linear classifier by updating weights when misclassifications occur.

Code:  
[Perceptron.py](./Ex3/Perceptron.py)

Dataset:  
[two_circle.txt](./Ex3/data/two_circle.txt)

#### AdaBoost
Implementation of **AdaBoost** on the `four_circle` dataset.  
The hypothesis space consists of **all lines defined by pairs of training points**, from which the algorithm selects the most informative weak classifiers.

Code:  
[Adaboost.py](./Ex3/Adaboost.py)

Dataset:  
[four_circle.txt](./Ex3/data/four_circle.txt)


---

### Exercise 4 – k-Nearest Neighbors (k-NN)

This exercise implements the **k-Nearest Neighbors (k-NN)** algorithm on the `two_circle` dataset.

The model is evaluated for different:
- **k values:** 1, 3, 5, 7, 9  
- **distance metrics:** \(L_1\), \(L_2\), and \(L_\infty\)

For each configuration, the dataset is randomly split into **training and testing sets**, the classifier is trained, and the **empirical and true errors** are computed.  
The experiment is repeated **100 times** and the average errors are reported.

📄 [Assignment Description: hw4 2022.pdf](./Ex4/hw4%202022.pdf)

#### Results

<p align="center">
  <img src="./Ex4/outputs/Empirical%20Error.png" width="32%">
  <img src="./Ex4/outputs/Error.png" width="32%">
  <img src="./Ex4/outputs/Total%20Error.png" width="32%">
</p>

#### Files

Code:  
[Knn.py](./Ex4/Knn.py)  
[main.py](./Ex4/main.py)

Dataset:  
[two_circle.txt](./Ex4/two_circle.txt)


--- 

## _Including_

* **Ex3:**
  * Perceptron
  * AdaBoost

* **Ex4:**
  * Knn
  * JL-transform
 
* **Final Project - [Link](https://colab.research.google.com/drive/1VcUgijfN7fyAbcL2zza4GUZNuhmdnI51?usp=drive_link):**
  * Methods: 
    * KNN
    * SVM
    * Logistic regression
    * NN
    * CNN
  * DataSet:
    * MNIST Digit
  * Check whether ML algorithms can classify images without image preprocessing
  * Extract feature vector from images using Auto-Encoder, use it as input to ML algorithms, and compare algorithms classification results.
  * Using the PCA algorithm, reduce image size, use it as input to ML classification algorithms, and compare them to results from the Auto-Encoder method.
 
---

###### Ariel University, Israel || Semester B 2022

  
