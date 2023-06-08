# ERA_Assignment_6


![era](https://github.com/ParthaAIML/ERA_Assignment_5/assets/100613266/71a005f6-ce58-42c9-96f8-4d0954db54bd)
---

## Table of contents
---
* [General info](#general-info)
* [Setup](#setup)
* [Files info](#files-ino)
* [Model info](#model-ino)
* [Execution info](#execution-info)
* [Sample output](#sample-output)

### General info
---
`This repository contains the ipython notebook named as S6-Assignment-Solution used for the assignment 6 of the ERA course. Here we have build a CNN model to predict the hand written digits [0-9] using MNIST data availabe with torchvision library. The objective of this assignment is to create a CNN model which can achive validation accuracy >=99.40 % under few constarints, the constraints are mentioned below`

* The model should achive 99.4% validation accuracy
* The model shoul have less than equal to 20k parameters
* The model should achive this accuracy with less than 20 epochs  

`The below points are good to have but not mendatory`

### Setup
---
The below requirements needs to be installed before running the code

#### Requirements
* `torch`
* `torchvision`
* `matplotlib`
* `torchsummary`

### Files info
---
There is one ipython notebook inside the S6 folder in this repository, the name of the notebook is.
*  **`S6-Assignment-Solution.ipynb`**


The **`S6-Assignment-Solution.ipynb`** is a ipython notebook contains all the code to run and validate the model.

### Model info
The details of the CNN Model is given below.
The input to the model is a `28x28x1` black and white image containing the digits from `0-9`
 
 
 
 
### Execution info
---
Depending on the preference, the model can be run in google colab or in local system.The `S5.ipynb` notebook has all the code required to run the model

The repository can be cloned using the below git command

`git clone https://github.com/ParthaAIML/ERA_Assignment_5`

The uesr needs to change the directoty with the below code before importing the functionalities from `model.py` and `utils.py`

`%cd /content/gdrive/My\Drive/Assignment_5` 

### Sample output
---
*  **Accuracy and Loss Plots**








