# Dataset Information:
The dataset consists of 303 rows and 14 columns with label Target as the 14th column which refers to Heart Disease detected 0/1 [yes/no].
Data contains categorical as well as continuous data.
This database contains 13 attributes (which have been extracted from
a larger set of 75)       

Attribute Information:
------------------------
      -- 1. age       
      -- 2. sex       
      -- 3. chest pain type  (4 values)       
      -- 4. resting blood pressure  
      -- 5. serum cholestoral in mg/dl      
      -- 6. fasting blood sugar > 120 mg/dl       
      -- 7. resting electrocardiographic results  (values 0,1,2)
      -- 8. maximum heart rate achieved  
      -- 9. exercise induced angina    
      -- 10. oldpeak = ST depression induced by exercise relative to rest   
      -- 11. the slope of the peak exercise ST segment     
      -- 12. number of major vessels (0-3) colored by flourosopy        
      -- 13.  thal: 3 = normal; 6 = fixed defect; 7 = reversable defect     

Attributes types
-----------------
Real: 1,4,5,8,10,12
Ordered:11,
Binary: 2,6,9
Nominal:7,3,13

Variable to be predicted
------------------------
Absence (1) or presence (2) of heart disease

# Data Cleansing:
There is only one column that contains null value that can easily be dropped by removing NA function.
# Data Visualization:
Data visualization is accomplished through a step-by-step process. I used a correlation matrix to determine which variables are the most dependent on the target variable. Target variable is plotted to show the ratio of Heart disease in the dataset for the variables.
# Methodology:
To explain and identify the problem and resolve medical objectives, diﬀerent data Science technique, which interpret the medical goals, have been implemented to diagnose the heart disease and to improve the success standards of the algorithms for prediction. Suitable machine learning algorithms, like: Random Forest, SVM (Support Vector Machine), Decision Tree and Logistics Regression were preferred for the training and implementation in python for developing and evolving the predictive model. These algorithms executed on the model will help medical experts to predict and diagnose heart attacks in the patient dataset. The main goal is to identify which machine-learning algorithm has the best accuracy for the prediction of heart disease from the patient dataset.
# Result:
Cross Validation is also done for all the models. The results are same but have some variance in accuracy. After Cross Validation the result seems like SVM has better accuracy But logistic Regression can also be taken into consideration.
