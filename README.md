<!-- Suggested code may be subject to a license. Learn more: ~LicenseLog:903170691. -->
# churn_prediction_fitness
__Construction of a classifier model to predict customer membership churn in a fitness center.__ 

<img src="https://github.com/ScinDBad/churn_prediction_fitness/assets/153782475/ec542f17-8b48-4d86-8dcc-7bcab42b0762" width="250">


### Description:

"It's necessary to implement an effective customer retention strategy through data analysis. 
The main goal is to predict the probability of customer churn for the next month, identify key customer profiles, and develop specific recommendations to improve customer retention and satisfaction. 
This will enable optimizing the customer experience and strengthening their loyalty."

### Process: 
<img src="https://github.com/ScinDBad/churn_prediction_fitness/assets/153782475/d173b8ce-3555-4be8-9f52-02e97e16a9ff" alt="Diagrama en blanco" width="500">

- Exploratory Data Analysis with preprocessing, outlier replacement, and feature correlation study.<br>
- Pre-select 2 classification models, segment the data, train, predict, tune, compare and decide.<br>
- Group and characterize customers by clusters to determine churn profile.<br>
- Analyze the most influential features in membership churn.<br>
- Visualize paired-features clusters and get churn rate per cluster.<br>

### Tools:<br>
Python, Jupyter, Project IDX

<img src="https://github.com/ScinDBad/churn_prediction_fitness/assets/153782475/f376ec1b-cf70-452a-b540-9b46284fd05b" alt="Diagrama en blanco1" width="175">

___
### Instructions:
- Create a virtual environment
- Install PIP 
- Install `requirements.txt` (then install other libraries if needed)
- If necessary Set/enable the packages `pkgs.python39`, `pkgs.python39Packages.pip` in the .nix file

If requirements.txt is troublesome, then install separately the libraries:

pandas 1.2.4
numpy 1.26.4
seaborn 0.11.1
matplotlib 3.3.4
scipy 1.13.1
sckit-learn 0.24.1

```bash
pip install library_name==version_number
```

_*Note:* This project was carried out within the Project IDX environment (by Google) based on Nix.
A virtual environment was used to run Python version 3.9.19 supported by the environment and other libraries for data analysis.
The requirements.txt file contains detailed dependencies used in the project to function in the IDX environment.
The .idx/dev.nix file contains the package configuration to be used, which are: `pkgs.python39`, `pkgs.python39Packages.pip`._