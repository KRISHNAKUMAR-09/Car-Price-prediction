
<img align= "left" alt="Coding" width= "200" src="https://png.pngtree.com/png-clipart/20200701/original/pngtree-car-seller-deals-buying-and-sale-flat-illustration-png-image_5426832.jpg">
<h1 align="right">Car-Price-prediction</h1>

This project aims to estimate the price of a used car based on its features and characteristics using machine learning techniques.



# _Table of Contents_
       * Introduction
       * Dataset
       * Objectives
       * Model Building
       * Results

# _Introduction_
  The Car Price Prediction system utilizes machine learning algorithms to analyze the features of used cars and estimate their prices. The system is trained on a labeled dataset of used cars, where each car has associated features (such as "wheelbase","carlength","carwidth","enginesize","stroke","compressionratio","horsepower","peakrpm","citympg","highwaympg") and its corresponding price. It learns patterns and relationships from the data to make accurate predictions on new, unseen car data.

# _Dataset_
  The project utilizes a labeled dataset of used cars for training and testing the model. The dataset consists of 205 rows and 26 columns. It does not contain any null values.

Dataset link: 

# _Objectives_
The main objectives of this project are as follows:

   1. Explore and preprocess dataset.
   2. Checking and removing outliers in the dataset that may affect model performance.
   3. Calculate correlations between variables to understand their relationships.
   4. Calculate Multicolinearity between input variables and output variables to understand their relationships.
   5. Perform data pre-processing technique to prepare the dataset for model training.
   6. Apply machine learning techniques to train a fraud detection model.
   7. Evaluate the model's performance using appropriate metrics.
   8. Save the best predicted model for future use.

# _Model Building_
  The dataset was analyzed using four different machine learning models: 
    Linear Regression, 
    KNN,
    DecisionTree,
    Random Forest,
    SVR. 
  Among these models, the Random Forest and SVR performed the best in terms of predicting car price, achieving an accuracy score of 84%.

# Results
  The **Random Forest and SVR** demonstrated its effectiveness in predicting the car price, achieving an accuracy score of **84%**. Random Forest model can serve as a valuable tool for detecting the spam messages.
