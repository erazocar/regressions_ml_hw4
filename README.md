# Ridge and Lasso reggressions
This repo serves for the usage of linear regressions in datasets that vary in decision making for housing and finances.
# Input Files
Please change the name of the path directories in which the data and the models can be saved. This are the variables named "path#". The docs should be found in a local directory called docs.
# Libraries
Please install libraries required for the Python program to run. In case there is a problem, a google colab link has been provided inside the code for usage online. It is linked to an open drive that contains the data used for the analysis. Would require a google account to access it but is open to anyone.
# Code Description
function reader = reads data from txt files.

function boston_split = serves for splitting datasets for boston housing info.

function optim_ridge = solution function for ridge regression of the boston housing data.

function optim_lasso = solution function for lasso regression of the boston housing data.

function optim_ridge_e20 = solution function for ridge regression of e2006 data.

function optim_lasso_e20 = solution function for lasso regression of e2006 data.

function ridge_model = creates a ridge model with varying alpha.

function lasso_model = creates a lasso model with varying alpha.

function e2006_split = splits data from e2006 dataset.

function coeff_matrices = creates matrices with interceptions, RMSE and the correlated variables.

function plot_rmse = plots RMSE curves.

function ridge_kfold = performs 5-cross validation analysis on ridge regression.

function lasso_kfold = performs 5-cross validation analysis on lasso regression.

