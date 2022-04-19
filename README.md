# What is Feature Selection?
Having a large number of features in your data? Does this make your model good or bad? 
An ideal model is the one that gives the best predictive accuracy. The model should give good predictions while the interpretation and usage of the model should not be complex. With many features the complexity(time/space) of any classifier or regressor increases while the performance could decrease. When the model has a good predictive accuracy it will also have a good interpretations. Feature Selection is one such technique to achieve this.
Feature Selection can use supervised or unsupervised techniques. In simple terms supervised methods use target/dependent variables and unsupervised methods do not use target/dependent variables.

Supervised feature selection methods may further be classified into three groups:

1. ### Embedded Methods: 
 Here feature selection is implemented by algorithms that have their own built-in feature selection methods. Algorithms perform automatic feature selection during training.
2. ### Wrapper Methods: 
 Wrapper methods evaluate multiple models using procedures that add and/or remove features to find the optimal combination that maximizes model performance. The model which performs best with an optimal subset of features will be chosen.
3. ### Filter Methods: This method makes use of statistical techniques for selecting the features.
