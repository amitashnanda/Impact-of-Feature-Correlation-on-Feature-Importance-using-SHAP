# Impact-of-Feature-Correlation-on-Feature-Importance-using-SHAP
Detail Analysis to know if Shapley interaction values capture information about feature correlations and if the interaction values can be used to obtain a more accurate feature ranking. The project investigates the relationship between blood pressure and health behaviors (e.g. sleep, exercise, diet, stress, etc.) 

## Folder Structure

```
Impact-of-Feature-Correlation-on-Feature-Importance-using-SHAP
│   README.md
│   requirements.text  
└───feature_ranking
│   │   Patient_2509.ipynb
|   |   Patient_2525.ipynb
|     
└───shap_analysis
|    |   shapley_demo.ipynb
|    |   
|       
└───results

```

## Prerequisites
The dependencies are listed under requirements.txt and are all purely python based. To install them simply run
```
pip install -r requirements.txt
```

## Dataset
The dataset is private. It consists of data collected and processed from patients in the trial with UCSD Health. 

## Running
For a local installation, make sure you have pip installed and run: 
```
pip install notebook
```
For running jupyter
```
jupyter notebook
```

  
![Boundary Box](/results/1.jpg)
![Bin detection](/results/2.jpg)
![Boundary Box](/results/3.jpg)
![Bin detection](/results/4.jpg)
![Boundary Box](/results/5.jpg)
![Bin detection](/results/6.jpg)
![Boundary Box](/results/7.jpg)
![Bin detection](/results/8.png)
