# Classify_Songs_Genre

## Load and Merge Data:
- Start by loading metadata about tracks and track metrics compiled by The Echo Nest using pandas. The data is merged based on the track_id and genre_top columns.

## Pairwise Relationships and Correlation:
- Explore correlations and Visualize the correlation metrics using a heatmap.

## Normalize Feature Data:
- Normalize the data using StandardScaler from scikit-learn to ensure fair treatment of different feature scales.

## Principal Component Analysis (PCA):
- Apply PCA to reduce dimensionality. Explore scree plots to determine the number of components to use.

## Further Visualize of PCA:
- Plot cumulative explained variance to determine the number of features required to explain a certain percentage of variance. In this case, aim for about 85% explained variance.

## Train a Decision Tree:
- Utilize the lower-dimensional PCA projection to train a decision tree classifier. Split the data into training and testing sets and evaluate the model's performance.

## Compare with Logistic Regression:
- Implement logistic regression as an alternative classification algorithm. Compare the performance of the decision tree and logistic regression using classification reports.

## Cross-Validation for Evaluation:
- Apply k-fold cross-validation to get a more robust evaluation of model performance. Use both decision tree and logistic regression classifiers and examine the cross-validation scores.
