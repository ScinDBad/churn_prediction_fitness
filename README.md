# churn_prediction_fitness
Construction of a classifier model to predict customer churn in a fitness center. 

__Process:__

<img src="https://github.com/ScinDBad/churn_prediction_fitness/assets/153782475/d173b8ce-3555-4be8-9f52-02e97e16a9ff" alt="Diagrama en blanco" width="500">

- Exploratory Data Analysis with preprocessing, outlier replacement, and feature correlation study.<br>
- Pre-select 2 classification models, segment the data, train, predict, tune, compare and decide.<br>
- Group and characterize customers by clusters to determine churn profile.<br>
- Analyze the most influential features in membership cancellation.<br>
- Visualize clusters by paired features and get churn rate per cluster.<br>

__Tools:__<br>
Python, Jupyter, Project IDX

<img src="https://github.com/ScinDBad/churn_prediction_fitness/assets/153782475/f376ec1b-cf70-452a-b540-9b46284fd05b" alt="Diagrama en blanco1" width="175">


__Instructions:__
- Create a virtual environment
- Install PIP 
- Install `requirements.txt` (then install other libraries if needed)
- If necessary Set/enable the packages `pkgs.python311`, `pkgs.python311Packages.pip` in the .nix file

_*Note:* This project was carried out within the Project IDX environment (by Google) based on Nix.
A virtual environment was used to run Python version 3.11.8 supported by the environment and other libraries for data analysis.
The requirements.txt file contains detailed dependencies used in the project to function in the IDX environment.
The .idx/dev.nix file contains the package configuration to be used, which are: `pkgs.python311`, `pkgs.python311Packages.pip`._


