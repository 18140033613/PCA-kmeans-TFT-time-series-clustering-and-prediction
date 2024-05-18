# PCA-kmeans-TFT-time-series-clustering-and-prediction
This repository contains code and sample data related to the essay title ***"InSAR time series clustering and Landslide displacement prediction with multiple variables and time series: A case study of the Badui area in Eastern Tibet"***, mainly focusing on clustering and prediction of time series.

To avoid environment conflicts, two separate environments are required for PAC-kmeans clustering and TFT prediction.

### I. First, for the PAC-kmeans clustering part, which is sourced from https://github.com/maybedave/InSAR-Time-Series-Clustering:

Open Anaconda Prompt and create a new Conda environment using the environment.yml file located in the specified path. Use the following command: _conda env create -f F:\PCA-kmeans-TFT-time-series-clustering-and-prediction\InSAR-Time-Series-Clustering\environment\environment.yml_. You may need to modify the path according to your setup. The environment name in environment.yml is set as _TSclustering_, but you can modify it and activate your environment accordingly later.You may use _python -m ipykernel install --user --name your_env_name --display-name your_env_name_ to connect your conda environment to ipykernel.

Once the environment is created, **run** the **PCA_kmeans_Clustering.ipynb** notebook.

### II. Next, for the TFT-Prediction part:

Follow the steps below to create a conda environment, which is feasible for hands-on testing:

conda create -n your_env_name python=3.9

pip install torch -f https://download.pytorch.org/whl/torch_stable.html

pip install jupyter

pip install ipykernel

pip install pytorch-forecasting

pip install autogluon

pip install optuna-integration

pip install optuna==3.4

Once the environment is created, **run** the **1_Allmodels.ipynb** , **2_Chronos_models.ipynb**, **3_Tune_TFT.ipynb** notebooks.
