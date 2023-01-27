# Credit-Card-Fraud-Detection

In this project, we have created a credit card fraud detection system, and find out whether a person will pay his/her credit card bill or not.
The dataset was taken from : https://www.kaggle.com/mishra5001/credit-card. 

The prediction are done on few columns after we drop the unnecessary columns. Sanity check was performed for columns like DAYS_BIRTH, DAYS_ID_PUBLISH, DAYS_EMPLOYED by converting the negative values to positive values. 

![image](https://user-images.githubusercontent.com/49121645/210013916-a1b25a25-7caf-4475-8d78-9b1ece1098d4.png)

The distribution of target values were visualized by calculating the percentage of non-defaulter(92%) and defaulters(8%) and it was observed that there was an imbalance in the dataset. This imbalance was handled by implementing Label encoder pre-processing package of sklearn.
All the graph plots were done to figure out the correlation between columns. 

8 classification algorithms were introduced to find the accuracy score on testing dataset. Below is the table showing the classification algorithm with their accuracy score. 
![image](https://user-images.githubusercontent.com/49121645/210014484-b2927f1c-80b7-4d07-b449-b4f8258da578.png)

After executing and analyzing various classification models on the given dataset, we found that Xgboost Random Forest Ensemble gives the best classification results., with an accuracy of about 92.55% (92.55441008018328% to be precise), as compared to 92.53% or less with other methods.
