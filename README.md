# Portfolio 4 - Mushrooms, Edible or Poisonous? 
## Context

Collected from Audobon Society Field Guide: mushrooms described in terms of physical characteristics. classification: poisonous or edible. 
The dataset has been imported from [UCI](https://archive.ics.uci.edu/dataset/73/mushroom) and for the purpose of this portfolio it has been simplified from 22 different features to 10 + a one (1) target value - poisonous. 
Only visual and easiest to observe in nature features were selected. The exact dataset that was used has been uploaded to github: 'agaricus-lepiota-data.csv'

## Goal

The goal is to find answers to the following questions:  

**Q1. Can we predict whether a mushroom is poisonous or edible based on its physical characteristics?**  
**Q2. What are the most significant features that influence a mushroom's edibility?**

## Field Description

|Column|Description|
|:-----:|:-----:|
|poisonous|edible = e, poisonous = p|
|cap-shape|bell = b, conical = c, convex = x, flat = f, knobbed = k, sunken = s|
|cap-color|brown = n, buff = b, cinnamon = c, gray = g, green = r, pink = p, purple = u,red = e, white = w, yellow = y|
|bruises|bruises = t, no = f|
|gill-color|black = k, brown = n, buff = b, chocolate = h, gray = g, green = r, orange = o, pink = p, purple = u, red = e, white = w, yellow = y|
|stalk-shape|enlarging = e, tapering = t|
|veil-color|brown = n, orange = o, white = w, yellow = y|
|spore-print-color|black = k, brown = n, buff = b, chocolate = h, green = r, orange = o, purple = u, white = w, yellow = y|
|ring-number|none = n, one = o, two = t|
|population|abundant = a, clustered = c, numerous = n, scattered = s, several = v, solitary = y|
|habitat|grasses = g, leaves = l, meadows = m, paths = p, urban = u, waste = w, woods = d|

## Project Structure
1. Data Preparation and Exploration
    * Data Exploration and Cleaning
    * Encoding Variables
2. Model Training
    * Logistic Regression
    * K-Nearest Neighbors KNN
       - Tune the hyper-parameter K
    * Decision Tree Model
       - Feature Visualisation
    * Random Forest
       - Feature Comparison Visualisation
3. Model Comparison & Conclusion
      - Model Comparison
      - Conclusion

  
## Author

Project done by Alexandru Stefan Moroe under MQ COMP6200 unit in Jupyter Notebook

