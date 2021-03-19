# new_data_science_project
new project based on data gathered from Kaggle. 

This project has been created based on data gathered from Kaggle, located (here)[https://www.kaggle.com/c/loan-default-prediction/overview]. It achieved a score of XXX during the first commit of this repository.

The data is a set of financial transactions associated with individuals with 778 unnamed features, some of which are categorical. Making this tasks particularly difficult. 

For each observation, it was recorded whether a default was triggered. In case of a default, the loss was measured. This quantity lies between 0 and 100. It has been normalised, considering that the notional of each transaction at inception is 100. For example, a loss of 60 means that only 40 is reimbursed. If the loan did not default, the loss was 0. You are asked to predict the losses for each observation in the test set.

The Machine Learning model created predicts the loss column. 
....with a performance of: .



Folder structure is loosely based on cookiecutter. 

The `notebooks` folder contains Jupyter notebooks and have been split to allow for readability: 
- Data analysis and exploration
- Data preparation 
- Build Machine Learning model 
- Evaluate Machine Learning model

The `src` folder contains the raw python code. The `setup.py` file can be run in a way that cleans, processes and splits the data. The output of the script are raw predictions.
