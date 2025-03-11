# Predictive Maintenance for Machines

The objective is to predict when a machine will fall into failures to build a proactive maintenance
schedule over a selected time window. Additional objective is to understand what are the
key features that are indicative of an upcoming failure.

The notebook accomplishes the following:

1. Access & prepare data: Download dataset from Kaggle (https://www.kaggle.com/datasets/arnabbiswas1/microsoft-azure-predictive-maintenance?resource=download) and EDA
2. Provisioning and configuration of python instance
3. Forecast values for the 100 machines / equipment and identify potential errors 24 hours
in advance of the predicted error (24 hour forecast). 

### Quick Setup

If you're a conda user:
- Download the environment.yml file and navigate to the folder containing the file. 
- Run conda env create -f environment.yml to create the conda environment with all packages needed to run the notebook.
- Run conda activate predictive-maintenance to activate your new environment
- You're all set! Go ahead and run the notebook in this environment. 

