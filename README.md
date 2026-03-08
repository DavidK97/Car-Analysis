# Car-Analysis


1 Which are the most decisive factors, forming the price of a car?
  - km's driven and age are the most imporant and has a negative correlation on the price


2) Which make and model of a car is most popular, according this data source? Which are its
technical characteristics?
  - Most popular car is the Ford Fiesta
  Mean stats for Ford Fiesta
  - Age: Ca. 5.2 years
  - Odometer: Ca. 81 195 km.
  - Price: Ca. 130 724 kr.
  - km/l: Ca. 22.4 km/l.

3) Is there any obvious tendency in the preference of the car models during the past 5-10 years?

4) Do people in Denmark prefer big or small cars? How reliable is your answer of this question?
  - The danes definetly prefers cars with smaller engine sizes, but our data mainly consists of only two brands so it is not quite representive for the real world

5) Are there any locations in Denmark, where the expensive cars are preferred choice by the
owners?
  - Syddanmark has a mean car price of 147 175, but is also the Region with the most cars for sale


7) Which machine learning methods did you choose to apply in the solution and why?
  - Linear Regression: To see the linear correlations between certain attributes
  - Classification: DecisionTree to classify cars in certain price segments
  - Clustering: Kmeans as there is already a quite disinct segmentation in the car market

8) How accurate are your solutions of prediction? Explain the meaning and the difference between
the various quality measures.

Liner Regression Model:
  - MAE (Mean Absolute Error): The average deviation in the price predtion: 26 412 kr.
  - RMSE (Root Mean Squared Error): Same as MAEm, but larger errors brings the value up more: 36 409 kr.
  - r2 (R-Squaref): The percentage of which the price can be explained by our dependent attributes: 80 %

Clustering Model:
  - Silhouette Score: Tells us the cohesion of the cars in a cluster: Score = 0.382

Classification Model:
  - Accuaracy_score method: The percentage of correct classification:  83.5%
  - Confuson matrix: To see what was predicted and what was true: It showed good results
  - K-Fold Cross-Validation: To do multiple folds to ensure that the model gets the same result on different part of the dataset: Average of 5 k-folds, 83.1%


10) What could be done for further improvement of the accuracy of the models?
  - Finding more car data, so we have more data to train on
  - Trying different ML methods
  - Reevalute data preparation (outliers, handling NaN's etc.)

11) Which were the challenges in the project development?
Mainly finding time to be thorough enough, some parts i went over too quick i feel.
