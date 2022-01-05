
# Hart Disease

In this project I tryed to predict whethet some one has a hart related disease or not with almost all of the models from sklearn library.


## Features of dataset 
- age
- sex
- chest pain type (4 values)
- resting blood pressure
- serum cholestoral in mg/dl
- fasting blood sugar > 120 mg/dl
- resting electrocardiographic results (values 0,1,2)
- maximum heart rate achieved
- exercise induced angina
- oldpeak = ST depression induced by exercise relative to rest
- the slope of the peak exercise ST segment
- number of major vessels (0-3) colored by flourosopy
thal: 3 = normal; 6 = fixed defect; 7 = reversable defect
## Walkthrough
Here I explaine my notebook file

**step 1**: Loading data and extracting some information from it about attributes


**step 2**:Preprocessing:

- Finding missing values using a heatmap
- Finding correlation of attributes
- replacing non-numeric values with numeric ones ( *some of them were not binary so I reme)

**step 3**:some data analysis

**step 4**:Applying knn with a usual train test split and evaluating

**step 5**:Applying DecisionTreeClassifier with

**step 6**:Applying RandomForestClassifier with

**step 7**:Applying Search vector machine

**step 8**:Optimization:
        - Optimizing RandomForestClassifier with GridSearchCV
        - Optimizing SVM with GridSearchCV


      
## Results(*without optimization*)
- KNN
![](https://gcdn.pbrd.co/images/nBVTwERCRWq2.jpg?o=1)
- DecisionTreeClassifier

![](https://gcdn.pbrd.co/images/tCbJk3uzNwkw.jpg?o=1)

- Random Forest( *100 estimators* )

![](https://gcdn.pbrd.co/images/1uZJhnYt7JBz.jpg?o=1)

- SVM
![](https://gcdn.pbrd.co/images/rQ7EAdiOe2EC.jpg?o=1)
## Optimizations

So I tried to do some optimiazation in Random forest and SVM this time with gride search facing the up coming results:

- Random forest
![](https://gcdn.pbrd.co/images/hNDMpRUEMF6x.jpg?o=1)

so we could get 1 precent more accuracy with a 200 n_estimators instead of 100

- SVM
![](https://gcdn.pbrd.co/images/qV2yKd4drb0F.jpg?o=1)

 I got almost 10 precent more accuracy and it was raising as I increased my parameters size but because I did not use Deep learning I could not find the best parameters 
## Feedback

If you have any feedback, please reach out to us at Mahyarfardinfar@gmail.com


## Info
- DATA: https://www.kaggle.com/ronitf/heart-disease-uci/download
- Gride Search : https://scikit-learn.org/stable/modules/grid_search.html