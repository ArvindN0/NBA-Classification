# Abstract
This project used multiple classification methods to investigate whether an NBA player’s season statistics can be used to ascertain the position they play. The aim was to predict a player’s position in the 2022-2023 season based on training data from the prior 21 seasons. We applied support vector machines (SVMs), tree-based bagging, artificial neural networks, and developed a hybrid SVM-tree model to overcome the limitations of typical decision trees. A filter method was applied to identify relevant predictors across the models and k-fold cross validation was used across all models for hyperparameter tuning. After training on 2001-2021 data, models were tested on the test set of the 2022-2023 NBA season. Test results showed that the support vector machine with a linear kernel performed the worst, while the hybrid model and artificial neural network approaches were the best performing models—successfully classifying 83.1% of player positions for the 2022-2023 NBA season. While the training and hyperparameter tuning process for the latter methods were more computationally intensive, they resulted in better performance on both the training and test sets.
