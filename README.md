# IMDb Movie Theme Prediction
This repository contains an ensemble of Python scripts and notebooks designed to scrape, clean, and analyze IMDb datasets to predict specific movie themes (not genres).

With this project we wanted to find out whether movie themes can accurately get predicted based on metadata.

# Workflow
The project is broken down into a pipeline to take raw, messy IMDb data and turn it into datasets.

Then we use different predictive models to find out which model would suit this problem best.

## Cleaning
[cleaned.ipynb](cleaned.ipynb) and [preprocessing.ipynb](preprocessing.ipynb) are the notebooks where the IMDb data is translated to interpretable values.

[verschillende_datasets.ipynb](verschillende_datasets.ipynb) is where we created differently encoded datasets to see which encoding fits best for what type of data. 

[hierarchy.ipynb](hierarchy.ipynb) is where we look at groupings of themes to see whether this grouping increases accuracy.

## Analysis & Prediction

[Decision_tree.ipynb](Decision_tree.ipynb), [Logreg.ipynb](Logreg.ipynb), [XGBoost.ipynb](XGBoost.ipynb), [Naive_bayes.ipynb](Naive_bayes.ipynb) and [Random_forest.ipynb](Random_forest.ipynb)

Are all the notebooks of the different models we used for different augmented datasets.

This part of the project is where we wanted to answer the questions like:

What is the overall prediction accuracy for specific themes?

How many unique themes (labels) are within the dataset?

Which themes are the most difficult for the model to distinguish?

[data_visualization.ipynb](data_visualization.ipynb) is where we use the data and create graphs that give is a better insight.

# Tech Stack
Python 3.x

Scikit-learn / TensorFlow: For building and evaluating the predictive models.

Pandas: For data displaying and modifying.

NLTK: For text tokenization.

# How to Use
All notebooks run on the data provided in the Datasets folder.

Be sure to download the required python modules if you want to rerun any of the models.
