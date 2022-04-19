# What is Feature Selection?
Having a large number of features in your data? Does this make your model good or bad? 
An ideal model is the one that gives the best predictive accuracy. The model should give good predictions while the interpretation and usage of the model should not be complex. With many features the complexity(time/space) of any classifier or regressor increases while the performance could decrease. When the model has a good predictive accuracy it will also have a good interpretations. Feature Selection is one such technique to achieve this.
Feature Selection can use supervised or unsupervised techniques. In simple terms supervised methods use target/dependent variables and unsupervised methods do not use target/dependent variables.

Supervised feature selection methods may further be classified into three groups:

1. ### Embedded Methods: 
 Here feature selection is implemented by algorithms that have their own built-in feature selection methods. Algorithms perform automatic feature selection during training.
 
2. ### Wrapper Methods: 
 Wrapper methods evaluate multiple models using procedures that add and/or remove features to find the optimal combination that maximizes model performance. The model which performs best with an optimal subset of features will be chosen.
 
3. ### Filter Methods:
 This method makes use of statistical techniques for selecting the features.
 
## Filter Methods
It is a univariate feature selection technique where the predictive power of each variable is evaluated and the relationship between input and output variable of interest is considered for this method.

### Issue with filter methods:
Filter methods are univariate in nature, because statistical measures are applied considering one input variable at a time. This means that interaction between the predictors are not considered. Let’s say we are using correlation coefficient to select the features with this if we select all features with high correlation to the target what about the correlation between the features. This causes the problem of multi-collinearity which is against the assumptions of some of the predictive models (Linear/Logistic Regression). Based on the type of input and output variable there are different statistical measures that can be used for Feature Selection.

#### 1. Continuous Input and Continuous Output
#### 2. Categorical Input and Continuous Output
#### 3. Categorical Input and Categorical Output
