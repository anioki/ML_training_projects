# ML_training_projects
Repository for studying ML
## Repository description  
* [fish project](https://github.com/anioki/ML_training_projects#fish-project "fish project") (picture analythe) 
* [avocado project](https://github.com/anioki/ML_training_projects#avocado-project "avocado-project")  
* [wine project](https://github.com/anioki/ML_training_projects#wine-project "wine-project")  
* [mashroom project](https://github.com/anioki/ML_training_projects#mashroom-project "mashroom project")  
## Projects description 
### Fish project  
Structure of project:  
```` 
fish 
     ├── fish.ipynb                                  - code for machine learning 
```` 
The goal was to build CNN for predicting fish and compare the results.  
Best CPU result:  
![image](https://user-images.githubusercontent.com/77074682/122646459-eae8ff00-d127-11eb-932b-82f918a67b95.png)  
![image](https://user-images.githubusercontent.com/77074682/122646484-05bb7380-d128-11eb-84a8-973bbc243cd1.png)  
Best GPU result: 
![image](https://user-images.githubusercontent.com/77074682/122647115-47015280-d12b-11eb-8f9c-d0832de39ae1.png)  
![image](https://user-images.githubusercontent.com/77074682/122647124-52ed1480-d12b-11eb-9d8b-e9b2b92a681e.png)  
### Avocado project  
Structure of project:  
```` 
avocado
     ├── avocado.ipynb                               - code for data analysis and machine learning 
```` 
Database contains data about avocado (Date, AveragePrice, Total Volume, 4046 (total number of avocados with PLU 4046 sold), 4225 (total number of avocados with PLU 4225 sold), 4770 (total number of avocados with PLU 4770 sold), Total Bags, Small Bags, Large Bags, XLarge Bags, type, year, region) where region or AveragePrice are predicted values. The goal was to predict 2 or more values from one dataset and compare the result depending on algorithm's parameters.
### Wine project  
Structure of project:  
```` 
wine 
     ├── winequality-red.csv                        - contains data  
     ├── Wine_Quality.ipynb                         - code for data analysis and machine learning
```` 
winequality-red.csv contains data about wine (fixed acidity, volatile acidity, citric acid, residual sugar, chlorides, free sulfur dioxide, total sulfur dioxide, density, pH, sulphates, alcohol, quality) where quality is predicted value. The goal was to study the SMOTE method and compare the results.  
 
### Mashroom project  
Structure of project:  
```` 
mashroom 
     ├── mashrooms.csv                               - contains data  
     ├── mashrooms.ipynb                             - code for data analysis and machine learning 
```` 
winequality-red.csv contains data about mashrooms (cap-shape, cap-surface, cap-color, bruises, odor, gill-attachment, gill-spacing, gill-size, gill-color, stalk-shape, stalk-root, stalk-surface-above-ring, stalk-surface-below-ring, stalk-color-above-ring, stalk-color-below-ring, veil-type, veil-color, ring-number, ring-type, spore-print-color, population, habitat) where class is predicted value (e - edible, p - poison). The goal was to analyze database and compare the results of algorithms.  

