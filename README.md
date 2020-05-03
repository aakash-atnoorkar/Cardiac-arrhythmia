# Analysis of Cardiac Arrhythmia and its classification

### A brief background

In this era of fast-paced and stressful lifestyle, people are unknowingly causing heart diseases. As it is extremely important to keep our heart and accordingly our health at the optimum level, one should take routine heart tests. Cardiac Arrhythmia is known to be a root cause for many serious heart diseases including heart failure. Arrhythmia is a form of irregularity in heart rhythms. The motive behind choosing dataset related to Cardiac Arrhythmia is to speed up the diagnosis of the disease and saving time for the cardiologist which can be utilized in treating the patients.


### Summary
The study aims at classifying the Cardiac Arrhythmia disease into two classes – Normal ECG and Heart Disease. We have obtained this data from University of California at Irvine Machine Learning Data Repository. Each record contains clinical measurements from ECG signals and intervals and some other information such as sex, age, weight, along with the decision of a cardiologist. The dataset has 452 records of patients and 279 attributes which mostly has numerical columns. We have performed PCA on 198 numerical columns and selected 41 principal components for further analysis. We applied several models on this dataset including K-Nearest Neighbors, Logistic Regression, Decision Trees, Random Forests, Boosted Trees, Linear Discriminant Analysis, Neural Networks and Support Vector Machines. Out of the models built using these algorithms, *Boosted Trees* gave the maximum accuracy of *80.74%*.


### Boosted Trees Algorithm
* Data after PCA was partitioned into train and test sets with 70:30 ratio
* Model was trained on the training set
* The trained model was then applied on test set
* Confusion Matrix, Lift Chart, ROC and AUC were determined and plotted

<table>
  <tr>
    <td>Confusion Matrix</td>
     <td>Lift Chart</td>
     <td>ROC Chart</td>
  </tr>
  <tr>
    <td><img src="https://github.com/aakashatnoorkar/Cardiac-arrhythmia/blob/master/Images/boosted%20tree%20confusion%20matrix.png" width=270 height=480></td>
    <td><img src="https://github.com/aakashatnoorkar/Cardiac-arrhythmia/blob/master/Images/lift%20chart.png" width=270 height=480></td>
    <td><img src="https://github.com/aakashatnoorkar/Cardiac-arrhythmia/blob/master/Images/ROC%20chart.png" width=270 height=480></td>
  </tr>
 </table>
