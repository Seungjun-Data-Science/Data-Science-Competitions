### PCA+LR,LDA,QDA+Simple Ensemble
- Applied PCA on data without any feature engineering
- Tried Logistic Regression, Linear Discriminant Analysis and Quadrant Discriminant Analysis as single models
- Used simple average for blending of probabilities of all the above single models

### Naive Bayes and Random Forest Ensemble Model.md
- Applied Standard Scaling on the dataset without additional feature engineering
- Then, tried Gaussian Naive Bayes and Random Forest Classifier

### Comprehensive Santander EDA
- After the previous two kernels which used baseline single models without any feature engineering, dived into actual comprehensive Explanatory Data Analysis to better understand the data

### Santander Gaussian Naive Bayes
- Found out that features were very uncorrelated to one another, so thought Naive Bayes algorithm would be a good fit
- Applied QuantileTransformer to transform data so that gaussian assumption of normality is better satisfied
- Used 5 fold cross validation strategy

