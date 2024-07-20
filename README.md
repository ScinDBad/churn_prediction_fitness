<!-- Suggested code may be subject to a license. Learn more: ~LicenseLog:903170691. -->
# churn_prediction_fitness
__Construction of a classifier model to predict customer membership churn in a fitness center.__ 

<img src="https://github.com/ScinDBad/churn_prediction_fitness/assets/153782475/ec542f17-8b48-4d86-8dcc-7bcab42b0762" width="250">


### Description: 

"It's necessary to implement an effective customer retention strategy through data analysis. 
The main goal is to predict the probability of customer churn for the next month, identify key customer profiles, and develop specific recommendations to improve customer retention and satisfaction. 
This will enable optimizing the customer experience and strengthening their loyalty."

### Insights:

| ![imagen_1](https://github.com/user-attachments/assets/fcef9400-4917-4599-ad4c-c35004362d15) | ![imagen_2](https://github.com/user-attachments/assets/249681e4-a650-4618-8288-9a41363757ed) <br> ![imagen_3](https://github.com/user-attachments/assets/6a6f1551-ed15-4c8c-9807-335888acd6e3) |
| :--: | :--: |
| ![imagen_4](https://github.com/user-attachments/assets/95f912ac-144f-4828-850d-c1e3ee630b52) | ![image](https://github.com/user-attachments/assets/516a5342-4888-4c7d-b4ab-2bd50b10d59c)|

![image](https://github.com/user-attachments/assets/e5b51abe-baab-4e54-b2fa-8b60c2336def)


Users were characterized by 13 aspects, with the most influential factors regarding membership cancellation being: 
- 'lifetime' (tenure)
- 'avg_class_frequency_current_month' (weekly attendance in the month)
- 'age' - 'avg_additional_charges_total' (additional charges)
- remaining time.
  
Membership cancellation, classified as Churn = 1: abandonment, 0: retention, can be predicted using a binary classification supervised learning algorithm called Logistic Regression, which performs well with notable discriminative capability, is quick to train, and does not require hyperparameter tuning.
The model has a strong ability to predict true negatives, meaning it better identifies customers who stay rather than those who cancel, according to the confusion matrix. The prediction metrics were:

- Accuracy: 0.91
- Precision: 0.81
- Sensitivity (Recall): 0.81
- Quality (AUC-ROC): 0.96

Dendrogram indicates there are 5 featured groups, where No. 4 is clearly defined as the churning group, so its features describe what makes this group cancell their membership, generally young individuals who did not attend for more than 10 months. 
Cluster 3 had approximately a quarter of users who dropped out of the gym.The most loyal users were those in Clusters 0, 1 and 2.

---
### Process: 
<img src="https://github.com/ScinDBad/churn_prediction_fitness/assets/153782475/d173b8ce-3555-4be8-9f52-02e97e16a9ff" alt="Diagrama en blanco" width="500">

- Exploratory Data Analysis with preprocessing, outlier replacement, and feature correlation study.<br>
- Pre-select 2 classification models, segment the data, train, predict, tune, compare and decide.<br>
- Group and characterize customers by clusters to determine churn profile.<br>
- Analyze the most influential features in membership churn.<br>
- Visualize paired-features clusters and get churn rate per cluster.<br>

### Tools:<br>
Python, Jupyter, Project IDX

<img src="https://github.com/ScinDBad/gamEda/assets/153782475/b44447b0-2286-4c64-889c-1944c1c7e51c" alt="Diagrama en blanco1" width="175"><br>

<a href="https://idx.google.com/import?url=https://github.com/ScinDBad/churn_prediction_fitness">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://cdn.idx.dev/btn/open_dark_32@2x.png">
  <source media="(prefers-color-scheme: light)" srcset="https://cdn.idx.dev/btn/open_light_32@2x.png">
  <img height="32" alt="Open in IDX" src="https://cdn.idx.dev/btn/open_purple_32@2x.png">
</picture>
</a>

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
