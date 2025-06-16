# practicalappliaction3
Comparing Classifiers using different Models

Executive Summary:
This assignment involves around comparing different classification models and evaluating their accuracy, performance and time execution. The Bank dataset is used to determine how many customers will open a term Deposit. 

Model Performance:
There were 4 Models used to fit the data after data clean-up and Feature engineering without any hyper parameter tuning. The Models performed as listed in the table below:

Model Accuracy , score and time results without optimization
                    Model  Accuracy  Precision    Recall  F1-score  \
0      LogisticRegression  0.785714   0.750000  0.705882  0.784568   
1     K-Nearest Neighbors  0.642857   0.550000  0.647059  0.645938   
2           Decision Tree  0.666667   0.565217  0.764706  0.668939   
3  Support Vector Machine  0.666667   0.636364  0.411765  0.648810   

   Train Time  Inference Time  
0    0.025053        0.002458  
1    0.004773        0.011825  
2    0.011355        0.002407  
3    0.007181        0.002867  

After boosting the hyperparameters and using GridCV search, the model performance stands slightly changed as shown below. Hyper parameter tuning and Gridcv search didn’t boost the performance much.

Model Accuracy , score and time results with optimization
                    Model  Accuracy  Precision    Recall  F1-score  \
0      LogisticRegression  0.714286   0.619048  0.764706  0.716901   
1     K-Nearest Neighbors  0.642857   0.550000  0.647059  0.645938   
2           Decision Tree  0.642857   0.533333  0.941176  0.629508   
3  Support Vector Machine  0.666667   0.565217  0.764706  0.668939   

   Train Time  Inference Time  
0    1.945556        0.001917  
1    0.087862        0.002477  
2    0.089883        0.001720  
3    0.067601        0.002334


![image](https://github.com/user-attachments/assets/ca1a9b16-c628-4d14-a8cf-9928391fb1b1)
