# Higgs Boson Challenge 2020 EPFL

## General Information

The repository contains the code for Machine Learning course 2020 (CS-433) project 1 (Higgs Boson challenge: https://www.aicrowd.com/challenges/epfl-machine-learning-higgs/leaderboards) at EPFL. More information about this challenge can be found in the folder `documents`.

### Team
The project is accomplished by team `Ma_BG` with members:
- Marie-Alix Gilltboeuf: [@GILLYBOEUF]
- Baptiste Hernette: [@Bapitou]
- Gaspard Villa: [@gaspardvilla] 


### Data
The data `train.csv` and `test.csv` should be found in https://github.com/epfml/ML_course/tree/master/projects/project1/data, to run the code please download and place them in the `data` folder

### Environment
The project has been developed and test with `python3.6`.
The required library for running the models and training is `numpy`.
The library for visualization is `matplotlib`.

### Results

Results to predict the test datasets are generated by running:
`python3 run.py`.
And the final results are saved in: `/data/test_prediction_submission.csv`.
* * *
## Project structure

### Training data
`implementations.py`: the implementation of 6 methods to train the model with specific argument for the hyper parameters. 

`methods.py`: the implemention of the 6 methdos to train the model using class Parameters() argument (for convenience).

`run.py`: the results obtained for the best submission.

### Processing data 
`EDA.py`: exploratory data analysis on the data set.

`losses.py`: contains all the classes for the loss functions and the class Parameters().

`proj1_helpers.py`: usefull tools to load the data sets, the computation of number of errors and the function that create a submission.

### Selecting Model

`cross_validalidation.py`: using cross-validation to test the accuracy of different models.

`plots.py`: functions that gives us the tools to visualize the datas and the results from the cross-validation.

### Notebook

`class_0.ipynb`: An example of the process we apply on the four different classes. Here, the process was applied specifically to the class 0 as an example.

### Report

`ML_Project_1.pdf`: a 2-pages report of the complete solution.

