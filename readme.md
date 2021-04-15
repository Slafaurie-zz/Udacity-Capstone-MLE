

Capstone project for **Udacity Machine Learning Engineer Nanodegree**.

## Installation
To run the Jupyter notebooks and python scripts, you will need a standard installation of Anaconda with Python 3.6.x. If an Anaconda installation is not possible, you can install these libraries using pip install -r requirements.txt available in the same repository.


## How to Run?
Once you have installed all the requirements, you run the notebook. There are three main notebook files.

- arvato-udacity-reference is the original notebook provided by Udacity, this contains the segmentation analysis.
- arvato-analysis focuses on the EDA and Feature Engineering for the supervised model.
- arvato-modelling includes the model building process.

You need the data to run this repo, but it's only available for Udacity Machine Learning Engineer Nanodegree. It was provided only to those participating in the ""in-class competition.

## Arvato Project 
This project involves two sections—first, a Segmentation analysis where the goal is to identify buyer personas for a mail company. The second is a prediction model to predict the likelihood of a user becomes a customer. The metric used is AUC score. 

## Results
In the Segmentation Part, KMeans algorithm identified 6 clusters. Three of those six were identified as buyer persona for the mail company. For the Supervised learning, the best model was a GradientBoostingClassifier that yield a AUC score of 75% during testing. Using this model, the final score in the competition test set was about 80% AUC.