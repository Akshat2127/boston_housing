# Content: Model Evaluation and Validation
## Project: Predicting Boston Housing Prices

## Project Overview
In this project, we will apply basic machine learning concepts on data collected for housing prices in the Boston, Massachusetts area to predict the selling price of a new home. We will first explore the data to obtain important features and descriptive statistics about the dataset. Next, we will properly split the data into testing and training subsets, and determine a suitable performance metric for this problem. we will then analyze performance graphs for a learning algorithm with varying parameters and training set sizes. This will enable we to pick the optimal model that best generalizes for unseen data. Finally, we will test this optimal model on a new sample and compare the predicted selling price to wer statistics.

## Project Highlights
This project is designed to get us acquainted to working with datasets in Python and applying basic machine learning techniques using NumPy and Scikit-Learn. Before being expected to use many of the available algorithms in the sklearn library, it will be helpful to first practice analyzing and interpreting the performance of wer model.

Things we will learn by completing this project:

- How to use NumPy to investigate the latent features of a dataset.
- How to analyze various learning performance plots for variance and bias.
- How to determine the best-guess model for predictions from unseen data.
- How to evaluate a model's performance on unseen data using previous data.

## Description
The Boston housing market is highly competitive, and we want to be the best real estate agent in the area. To compete with wer peers, we decide to leverage a few basic machine learning concepts to assist we and a client with finding the best selling price for their home. Luckily, we\'ve come across the Boston Housing dataset which contains aggregated data on various features for houses in Greater Boston communities, including the median value of homes for each of those areas. wer task is to build an optimal model based on a statistical analysis with the tools available. This model will then be used to estimate the best selling price for wer clients\' homes.

## Software and Libraries
This project uses the following software and Python libraries:

- [Python](https://www.python.org/download/releases/3.0/)
- [NumPy](http://www.numpy.org/)
- [pandas](http://pandas.pydata.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [matplotlib](http://matplotlib.org/)

we will also need to have software installed to run and execute a [Jupyter Notebook](http://ipython.org/notebook.html).

If we do not have Python installed yet, it is highly recommended that we install the [Anaconda](http://continuum.io/downloads) distribution of Python, which already has the above packages and more included. 

## Starting the Project

For this assignment, we can find the `boston_housing` folder containing the necessary project files on the [Machine Learning projects GitHub](https://github.com/udacity/machine-learning), under the `projects` folder. we may download all of the files for projects we'll use in this Nanodegree program directly from this repo. Please make sure that we use the most recent version of project files when completing a project!

This project contains three files:

- `boston_housing.ipynb`: This is the main file where we will be performing wer work on the project.
- `housing.csv`: The project dataset. we'll load this data in the notebook.
- `visuals.py`: This Python script provides supplementary visualizations for the project. Do not modify.

In the Terminal or Command Prompt, navigate to the folder containing the project files, and then use the command `jupyter notebook boston_housing.ipynb` to open up a browser window or tab to work with wer notebook. Alternatively, we can use the command `jupyter notebook` or `ipython notebook` and navigate to the notebook file in the browser window that opens. Follow the instructions in the notebook and answer each question presented to successfully complete the project.

## Note
This dataset was originally obtained from the UCI - https://archive.ics.uci.edu/ml/datasets/Housing but it looks like the dataset is not available on the UCI anymore.
