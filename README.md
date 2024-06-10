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

<img src="https://github.com/ScinDBad/gamEda/assets/153782475/b44447b0-2286-4c64-889c-1944c1c7e51c" alt="Diagrama en blanco1" width="175">

___
### Instructions:
- Create a virtual environment
- __For local work:__ Install `Python 3.9.19`
- __For Cloud work:__ Set/enable the packages `pkgs.python39`, `pkgs.python39Packages.pip` in the .idx/dev.nix file.
- Install `requirements.txt`
  
<details>
<summary>Or install libraries manually in terminal</summary><br>

  - pandas 1.2.4
  - numpy 1.26.4
  - seaborn 0.11.1
  - matplotlib 3.3.4
  - scipy 1.13.1
  - scikit-learn 0.24.1
    
```bash
pip install pandas==1.2.4 numpy==1.26.4 seaborn==0.11.1 matplotlib==3.3.4 scipy==1.13.1 scikit-learn==0.24.1
```
</details>


___*Note:___
_This project was carried out within the Google IDX environment based on Nix.
A virtual environment was used to run `Python 3.9.19` and other libraries for data analysis.
The `requirements.txt` file contains detailed dependencies used in the project to function in the IDX environment._
