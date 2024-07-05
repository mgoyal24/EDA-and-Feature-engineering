#Feature Engineering on Flight Price 
Feature Engineering

Feature Engineering is the process of using domain knowledge to extract new features from raw data that can improve the performance of machine learning models. It involves creating, transforming, and selecting features to enhance model accuracy and efficiency.

Key Techniques in Feature Engineering:

Creating New Features:

Polynomial Features: Generating new features by combining existing features (e.g., interaction terms).
Binning: Converting continuous variables into categorical bins.
Date time Features: Extracting features like day, month, year, hour from date time variables.
Aggregations: Summarising data using statistical measures like mean, sum, count, etc.

Transforming Features:

Scaling: Standardising or normalising features to ensure they contribute equally to the model.
Encoding Categorical Variables: Converting categorical data into numerical format using techniques like one-hot encoding, label encoding, or target encoding.

Feature Selection:

Univariate Selection: Statistical tests to select features that have a strong relationship with the target variable.
Recursive Feature Elimination (RFE): Iteratively building models and removing the least important features.
Principal Component Analysis (PCA): Reducing dimensionality by transforming features into a new set of orthogonal components.



Tools for Feature Engineering:

Python Libraries: Scikit-learn, Pandas, Feature-engine.
R Libraries: caret, dplyr.

Benefits of Feature Engineering:

Enhances the predictive power of machine learning models.
Reduces overfitting by selecting relevant features.
Improves model interpretability by highlighting important features.

