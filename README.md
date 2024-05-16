# PCA-kmeans-TFT-time-series-clustering-and-prediction
This repository contains code and sample data related to the essay title ***"InSAR time series clustering and Landslide displacement prediction with multiple variables and time series: A case study of the Badui area in Eastern Tibet"***, mainly focusing on clustering and prediction of time series.

To avoid environment conflicts, two separate environments are required for PAC-kmeans clustering and TFT prediction.

### I. First, for the PAC-kmeans clustering part, which is sourced from https://github.com/maybedave/InSAR-Time-Series-Clustering:

Open Anaconda Prompt and create a new Conda environment using the environment.yml file located in the specified path. Use the following command: _conda env create -f F:\PCA-kmeans-TFT-time-series-clustering-and-prediction\InSAR-Time-Series-Clustering\environment\environment.yml_. You may need to modify the path according to your setup. The environment name in environment.yml is set as _TSclustering_, but you can modify it and activate your environment accordingly later.

Once the environment is created, **run** the **PCA_kmeans_Clustering.ipynb notebook**.

### II. Next, for the TFT-Prediction part:

Follow the same procedure to set up the environment. My environment.yml file is located at _F:\PCA-kmeans-TFT-time-series-clustering-and-prediction\TFT-Prediction_, and the environment name in my environment.yml is set as _TFT_.

Once the environment is created, **run** the **TFT-Prediction.ipynb notebook**.
