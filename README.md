
# Sign Language

Sign languages are languages that use the visual-manual modality to convey meaning. Sign languages are expressed through manual articulations in combination with non-manual elements. Sign languages are full-fledged natural languages with their own grammar and lexicon. (Important information: Sign languages ​​differ from one region to another, such as spoken languages)


## Contents

-[Problem Statement](#Problem_Statement)

-[Data Description](#Data_Description) 

-[Tools](#Tools)

-[Models](#Models)

-[Installation](#Installation)

-[MVP](#MVP)

-[Dataset Resource](#Dataset_Resource)


![Logo](https://44pcmk1er1zl3gbw7d4abgsh-wpengine.netdna-ssl.com/wp-content/uploads/2020/09/ASL_Alphabet.jpg)


## Problem_Statement

We will make a machine learning model to classify each picture of (American Sign Language) correctly. Basically we will be building a image classification model.
### Data_Description

We are given 2 comma saperated file(.csv) each on them contains some rows and 785 columns.

    -From 2nd columns onwards each column represents the pixel values associated , representing a 28x28 grayscale image.
    -First column in each row represnts label with the image.
    -There are total 24 lables (in american sign language) A-I,K-Y means A-Z except J and Z.



## Tools
Google colab

Language: Python

Libraries: numpy, pandas, seaborn, matplotlib, Sklearn, tensorflow

## Models

machine learning models: 

KNN, 
CNN using keras,
CNN using pytorch.

## Installation

Run pip install command to install related packages.

```bash
!pip install numpy
!pip install pandas
!pip install seaborn
!pip install keras-tuner --upgrade
!pip3 install torch torchvision
```
    


## MVP

Building a image classification model
## Dataset_Resource

https://www.kaggle.com/datamunge/sign-language-mnist
