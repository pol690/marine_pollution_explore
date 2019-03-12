## Exploring pollution of marine ecosystems with Machine Learning (and avoiding interpretation mistakes on the way)

### Link to blogpost

https://medium.com/@artem.krasnobaev/exploring-pollution-of-marine-ecosystems-with-machine-learning-and-avoiding-interpretation-6d1cbdc41817

### Short Description

Project on using Machine Learning to find out how different charastics influnce concentrations of pollutants in musels

### Abstract

The first aim of this project was to investigate relationships between concentrations of pollutants in marine animals and their histological data. The second, more practical aim, was to compare novel and relatively old machine learning methods of in-silico ecological or biochemical research.

For the former, the pivotal role of the peculiarities of local contaminant inputs, as well as animal size and lipid composition were confirmed. On the other hand, a new feature - digestive tubule atrophy was theorized to have a possible causality on contaminant concentration.

For the latter, the clear advantage of novel algorithms (Catboost and LightGBM) before more traditional algorithms (Random Forest and especially FAMD) is established. The main reason for that are the relative straightforwardness of interpretation and a better handling of inter-correlation of variables.

Generally, the usefulness of ML for ecological and biochemical studies was demonstrated.

### Dataset description
      
Datasets used were too big to be upload to github as single files. The files can be found online with the links below. 

Source:  Kaggle, original dataset from The National Oceanic and Atmospheric Administration (NOAA) National Status and Trends (NS&T) Mussel Watch Program of the USA

Links: https://www.kaggle.com/sohier/mussel-watch 

  https://products.coastalscience.noaa.gov/collections/ltmonitoring/nsandt/data2.aspx

### File description

##### 1 Mus_project.ipynb 

Jupyter notebook with code written in Python 3.

##### 2 README.md

### Packages

pandas 0.24.1 
numpy 1.12.1 
scikit-learn 0.20.2 
scipy 1.1.0
seaborn 0.9.0
prince 0.6.1
catboost 0.12.2
lightgbm 2.2.2

