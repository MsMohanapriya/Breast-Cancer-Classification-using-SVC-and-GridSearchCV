# Breast_Cancer_Classification_using-SVC-and-GridSearchCV
Classifiying the cancer cells whether it is benign or malignant based on the given data

To Predict if the cancer diagnosis is benign or malignant based on several observations/features
30 features are used, examples:

  - radius (mean of distances from center to points on the perimeter)
  - texture (standard deviation of gray-scale values)
  - perimeter
  - area
  - smoothness (local variation in radius lengths)
  - compactness (perimeter^2 / area - 1.0)
  - concavity (severity of concave portions of the contour)
  - concave points (number of concave portions of the contour)
  - symmetry 
  - fractal dimension ("coastline approximation" - 1)

Datasets are linearly separable using all 30 input features

Number of Instances: 569
Class Distribution: 212 Malignant, 357 Benign
Target class:
   - Malignant
   - Benign
Pandas for data preprocessing
Importing matplotlib and seaborn for data visualisation

Looking at the Visualization of important features in relation to target variable diagnosis to see on which features it is more related

Next use map to plot all the possible kdeplots for the 'Age' column by the hue choice

The importance of data correlation has an effect when you have a dataset with many features. 
It’s tempting to think that a larger number of features will help a model make better predictions. But that’s incorrect.
If you try to train a model on a set of features with no or very little correlation, you will get inaccurate results.

Checking the correlation among different features and target variable diagnosis using heat map

I beleive for this problem Support Vector Machines are good classification algorithm for this problem

Grid Search is an algorithm with the help of which we can tune hyper-parameters of a model. 
We pass the hyper-parameters to tune, the possible values for each hyper-parameter and a performance metric as input to the grid search algorithm. 
Then it outputs the hyper-parameter combination that gives the best result.
