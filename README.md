# Decision-Trees_python
This is a specific type of flow chart which is used to visualize the decision-making process 
via mapping out different courses of action and their possible outcomes. There are several
parameters of the model:

## max_depth
This indicates how deep the tree can be. The deeper the tree, the more splits it has and captures more information about the data.

## min_samples_split
min_samples_split represents the minimum number of samples required to split an internal node

## min_samples_leaf
min_samples_leaf is The minimum number of samples required to be at a leaf node.

## max_features
max_features represents the number of features to consider when looking for the best split.

# Simplest Model with no hyperparameters

from sklearn.tree import DecisionTreeRegressor
model = DecisionTreeRegressor(random_state=1)
# Fit model
melbourne_model.fit(X, y)
# predicting
model.predict(_)
