This project contains a Google Colab (ipynb) notebook for classifying Patients into those who have Alzheimers (Demented), who don't (Non - Demented), and others (Converted).
(It is a group project)
In order to view the notebook, install the ipynb file on google colab.


The main question of our project is to predict whether the patients in our dataset have alzheimers (demented) or don't have alzheimers (non-demented) or if they have progressed from MCI to having Alzheimers (converted). 
In order to get to know our dataset well, we have deleted the missing values and performed few data visualization graphs. 
In order to acheive our main goal, we have performed KNN algorithm on our dataset. 
We have encoded the 'M/F' column, and performed a 70/30 train test split on our data. 
We have also normalized our data using the MinMaxScaler(). 
After normalization, we have trained our model with 3 K-neighbors. 
Finally, we have tested our model, and analyzed it using the Classfication Report, Confusion Matrix and Accuracy Score
