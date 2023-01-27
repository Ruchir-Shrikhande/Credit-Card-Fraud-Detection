# Credit-Card-Fraud-Detection
In this project, we have created a credit card fraud detection system, and find out whether a person will pay his/her credit card bill or not. The dataset was taken from : https://www.kaggle.com/mishra5001/credit-card.

The prediction are done on few columns after we drop the unnecessary columns. Sanity check was performed for columns like DAYS_BIRTH, DAYS_ID_PUBLISH, DAYS_EMPLOYED by converting the negative values to positive values.

The distribution of target values were visualized by calculating the percentage of non-defaulter(92%) and defaulters(8%) and it was observed that there was an imbalance in the dataset. This imbalance was handled by implementing Label encoder pre-processing package of sklearn. All the graph plots were done to figure out the correlation between columns.

8 classification algorithms were introduced to find the accuracy score on testing dataset. Below is the table showing the classification algorithm with their accuracy score.

![final accuracy of 8 models](https://user-images.githubusercontent.com/123781025/215226842-8040a2bf-19be-4cac-b057-e944825852a3.png)
After executing and analyzing various classification models on the given dataset, we found that Xgboost Random Forest Ensemble gives the best classification results., with an accuracy of about 92.55% (92.55441008018328% to be precise), as compared to 92.53% or less with other methods.
