

Capstone project for **Udacity Machine Learning Engineer Nanodegree**.

## Installation
To run the Jupyter notebooks and python scripts, you will need a standard installtion of Anaconda with Python 3.6.x. If an Anaconda installation is not possible, you can install these libraries using `pip install -r requirements.txt` available in the same repository.

## How to Run?
Once you have installed all the requirements, you run the notebook. First, the `Arvato Project Workbook.ipynb` contains all code required.

Make sure you have downloaded the `utils` repository, where customized functions are created and imported inside the notebook.

You need the data to run this repo, but it´s only available for Udacity Machine Learning Engineer Nanodegree. It was provided only to those participating in the "in class" competition.

## Arvato Project 
This project involves two section. First, a clustering analysis of demographic data which the goal to identify buyer personas from a mail company. The second is a prediction model to predict the likelihood of a user becomes a customer. The metric used is AUC score. 
There are three main notebook files.
- arvato-udacity-reference is the original notebook provided by Udacity, this contains the segmentation analysis. 
- arvato-analysis focuses in the EDA and Feature Engineering for the supervised model.
- arvato-modelling contains the model building process. 

## Results
For the Segmentation Part, 6 clusters were identified. Three of those 6 were identify as buyer persona for the mail company. 
Fot the Supervised learning, the best model was a GradientBoostingClassifier that yield a AUC score of 75% during testing. Using this model, the final score in the competition test set was about 80% AUC. 