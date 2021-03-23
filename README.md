# Machine-Learning-Challenge
Exoplanet Exploration

## About
Over a period of nine years in deep space, the NASA Kepler space telescope has been out on a planet-hunting mission to discover hidden planets outside of our solar system.

To help process this data, you will create machine learning models capable of classifying candidate exoplanets from the raw dataset.

In this homework assignment, you will need to:

  1. Preprocess the raw data
  2. Tune the models
  3. Compare two or more models

## Conclusion

For this project I decided to choose these 2 machines learning algorithms:
  1.	KNN (K- Nearest Neighbors):
      This model did well with the data set as we got a score or 0.83. I used pipeline method for cross validation. 
  
  2.	SVM (Support Vector Machine):
      The SVM With Hyperparameter scored 0.68. Interesting fact is that without the hyperparameter tuning the accuracy was 0.88.

  3.	Deep Learning Model with TensorFlow.
      Finally tried a deep learning model with TensorFlow. With this model I got an accuracy score of 0.86 but with a loss of 0.77. Which is not ideal. Hence we           cannot consider this model ideal for this data set. 
      
  KNN would be my pick of the model for this data set.
