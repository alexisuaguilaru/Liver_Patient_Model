# Classification Model of Liver Patient
## Abstract
This project aims to create a classifying model of liver patients based on the medical and health indicators they present.

## Author, Affiliation and Contact
Alexis Aguilar [Student of Bachelor's Degree in "Tecnologías para la Información en Ciencias" at Universidad Nacional Autónoma de México [UNAM](https://www.unam.mx/)]: alexis.uaguilaru@gmail.com

Project developed for the subject "Sistemas basados en conocimiento" (Machine Learning: Supervised Learning) for the class taught in semester 2025-2.

## License
Project under [MIT License](LICENSE)

## Introduction
Understanding the possible relationships between certain medical and clinical factors in the increase of suffering from a disease, such as liver disease, allows creating new fields and lines of research, creating new solutions for the treatment, and possible cure, of these diseases. The latter being the most relevant to motivate the creation and use of Machine Learning (ML) models that are highly explainable or that the information obtained from them is understandable by anyone belonging to both the medical and data science fields.

## General Aim 
From what is mentioned in [Introduction](#introduction), the main objective of this project is to create a ML model that can learn to classify patients according to whether they have liver disease or not based on their clinical and medical indicators related to liver diseases. And according to the requirements in [Technical Requirements](TechnicalRequirements.pdf), the models to be built will be explainable in terms of their results and parameters.

## About Dataset
[[1]](#references) Death by liver cirrhosis continues to increase, given the increase in alcohol consumption rates, chronic hepatitis infections, and obesity-related liver disease. Notwithstanding the high mortality of this disease, liver diseases do not affect all sub-populations equally. The early detection of pathology is a determinant of patient outcomes, yet female patients appear to be marginalized when it comes to early diagnosis of liver pathology. The dataset comprises 584 patient records collected from the NorthEast of Andhra Pradesh, India. The prediction task is to determine whether a patient suffers from liver disease based on the information about several biochemical markers, including albumin and other enzymes required for metabolism.

## Exploratory Data Analysis (EDA)
The process related to a first exploration of the data of [[1]](#references) is found in [Exploratory Data Analysis](./ExploratoryDataAnalysis/ExploratoryDataAnalysis.ipynb), from which the first insights about the data and possible relationships between attributes were obtained. It should be noted that there is no significant difference between the values taken by the attributes when there is a liver disease, and this leads to the existence of possible non-linear relationships that provide the desired distinction or classification, thus, the appearance of a liver disease becomes a complex process that cannot be summarized to a set of attributes and values to determine the diagnosis in any patient. This is also compounded by a high correlation between certain attributes, evoking that different clinical signs cause or are present with others and making these attributes provide irrelevant information.

## Machine Learning Models
The process related to the creation, training, evaluation and final selection of the models is found in [Machine Learning Models](./Models/MachineLearningModels.ipynb), in which use is made of the insights and observations acquired in [Exploratory Data Analysis](./ExploratoryDataAnalysis/ExploratoryDataAnalysis.ipynb) to define the data preprocessing stages, the metrics used for training and to determine the best model considering both the metrics and the bias-variance trade-off that arises to evaluate the models in the test set.

## References
* [1] B. Ramana and N. Venkateswarlu. "ILPD (Indian Liver Patient Dataset)," UCI Machine Learning Repository, 2022. [Online]. Available: https://doi.org/10.24432/C5D02C.