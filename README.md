# employee-promotion-prediction
![image](https://user-images.githubusercontent.com/81704848/128612046-bab05b8b-df39-4eba-bab6-895ec7aba725.png)

## Promotion Prediction
To predict if a employee is potential candidate for promotion or not with the help of past data such as his education, experience, age, ratings, overall score etc.(Analytics Vidhya Ml Practice Problem)
## Data Dictionary ##
![image](https://user-images.githubusercontent.com/81704848/128611997-c9d4d282-c986-43b3-977e-528d32b43def.png)
# Challenges:
The challenges in the data are the imbalance in the data, missing values and most of the data is either ordinal or categorical, finding out the best model.
![image](https://user-images.githubusercontent.com/81704848/128612130-d1f702cb-aecb-41bb-af87-1495b2bd69c2.png)
This is how the target variable looks when we count the number of records in the feature. So as we can see there is a big difference between 0 and 1 so we can say it is a classification problem and it is obvious that only some people will get the privilege of getting promoted. So it would be tough for the model to train on such imbalanced data. 
# Approach
So I started with some basic EDA and started understanding the data.
I have done soome descriptive statistics to see if the variance across the data is normal or are there any abnormal differences in the data. 
Now I have analyzed Ooutliers with the help of Boxplot. I see that there are some outliers in the Length of Service column. But I have not remove these values, as the values are not very far and huge.
![image](https://user-images.githubusercontent.com/81704848/128612570-8624b1a7-b2d7-40bf-8856-bf19e043de6d.png)
