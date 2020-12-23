# final2-eiggenFace

## Introduction.
The human face is an extremely complex and dynamic structure with characteristics that can quickly and significantly change with time. It is the primary focus of attention in social relationships and plays a major role in the transmission of identity and emotions. Therefore, face recognition is applied in many important areas such as security systems, identification of criminals, verification of credit cards and so on. Unfortunately, many face features make development of facial recognition systems difficult.

## Background. 
The algorithm is based on an eigenfaces approach which represents a PCA method in which a small set of significant features are used to describe the variation between face images. One of the simplest and most effective PCA approaches used in face recognition systems is the so-called eigenface approach. This approach transforms faces into a small set of essential characteristics, eigenfaces, which are the main components of the initial set of learning images (training set). 

## Implementation.
In order to recognize and find the similarity between different faces we used the Eigenfaces algorithm. The implementation of this algorithm was based on principal components analysis (PCA). To realize this project we have used Jupyter Notebooks with python libraries like matplotlib, numpy, os, scipy.io, which will be needed to show the plots and calculate PCA.

First of all, we should obtain a facial image dataset : We need a collection of facial images containing different kinds of faces. For this project we get a collected data of 37 different faces on 8x8 different light positions. That means 37 people with 64 different shadow pictures, so in total 2868 images of faces.
![alt text](https://github.com/yelnarMurat/Final_Advanced_Python/blob/main/Снимок экрана 2020-12-23 в 17.52.13.png?raw=true)
