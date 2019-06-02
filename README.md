### Leveraging Customer Data for Targeted Bank Marketing  

### A Machine Learning Model using Portuguese Bank Customer Data

This was a final project for a graduate school machine learning class at the University of St. Thomas.  Our three-member group divided algorithm analysis up between us, and these are the algorithms I analyzed with our data set.  Initially, I started with on my own with EDA/feature selection/encoding, but then we decided as a group to have one uniform process for our final comparison.  There are two sets of notebooks for some algorithms, one with our group data prep and one where I experimented with other methods.

- Started data exploration/visualization of numerical/categorical features, could remove some features highly correlated to each other (seaborn/matplotlib).
Encode categorical data if needed for the algorithm (scikit learn label encoding/one hot encoding).
- One issue with the data set was an imbalanced class label (88% did not buy cd), used the SMOTE algorithm(Synthetic Minority Oversampling Technique) to create synthetic values instead of making copies of data.
- My responsibility for the group was looking into decision tree/random forest/lightGBM algorithms.
- Optimized hyperparameter values using grid search.
- Tried with and without PCA (principal component analysis).
- Results/key features: (economic indicator (Euribar), age, pdays(number of days since last contact), month (dec/march).

#### Technologies used: python, scikit-learn, pandas, numpy, matplotlib, seaborn, lightGBM
