##Random Forest - Support Vector - Neural Network Model Accuracy Score comparison of  Wine dataset

    1. Import Necessary Packages

        Import Basic Packages such as Pandas, Numpy and Matplot library.

        Import various Machine Learning Pakagess such as RandomForestClassifier,SVM  form sklearn

        Import Performance related Packages such as confusion_matrix,classification_report
        
    2. Loading the dataset using read_csv command.Here the wine data set contains 12 columns. The data set contains 11 features columns(Independent columns) 
       and quality column as target(dependent variable.)

    3. When performing Data Analysis for the wine data set, observed that dataframe was not containing any null values. So there is no need to perform the cleaning 
       operation against the given dataset.
       
    4. Preprocessing data will replace the wine quality values by labels defined as bad or good.After executing preprocessing the wine quality now fall under two categories.
       It may be either good or bad.
       
    5. Label Encoder replace the categorical value with a numeric value between 0 and the number of classes minus 1. Here we two classes as good or bad. 
        So those categorical values will be replaced by 0 and 1.From the above Label encoder observations,wine dataset contains 1382 bad wine and 217 good wine count. 
      
    6. Variable Separation of Response Variable Vs. Feature Variable i.e segregation of Traing and Test data.
    
    7. Appled Standard Scaling to get Optimized result for the train and test data.
    
    8. Random Forest Classifier give 89% of accuray
    
    9. Support Vector Model (SVM) Classifier gives only 86% of accuracy. When it is compared with Random forest classifies it gives 3% less accuracy.
    
    10. Neural Network model also gives 89% accuracy for wine dataset.
    
    Conclusion : 
                 The above Accuracy score gives about the comparision of the Random Forest,Suppor Vector and Neral Network Model for the wine dataset.
                 Random forest model and Neural Network model gives more accuary when compared to support vector model for this wine dataset.


  

