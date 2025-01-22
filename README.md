# principal-component-analysis-algorithm
A dimensionality reduction method called Principal Component Analysis (PCA) is used to reduce the complexity of complicated datasets while preserving the majority of their crucial information.
The way it operates is by converting the initial variables into a new set of main components, which are orthogonal
variables. The first component, which captures the most variation, is followed by the second, and so on,
in order of how much variance in the data they explain.
Let&#39;s say we wish to use PCA to reduce a dataset that contains two features—weight and height—to
only one dimension. PCA finds two eigenvectors and computes the covariance matrix after normalizing
the input. The direction of the maximum variance in the data is represented by the eigenvector with the
highest eigenvalue. In order to create a one-dimensional representation of the dataset, PCA then
projects the original data onto this eigenvector.
Accuracy on the custom dataset without PCA: 94.36% of the dataset&#39;s accuracy was attained without
using PCA. This suggests that without dimensionality reduction, the model trained on the original high-
dimensional dataset was successful in predicting the target variable.
Accuracy with PCA on the custom dataset: The output does not include the accuracy attained using PCA
on the custom dataset. This can be the result of a coding mistake or oversight. On the other hand, the
lack of accuracy using PCA raises the possibility that there is a problem with the model training
procedure or PCA implementation.
Principal component explained variance: The output does not include the principal component
explained variance. Determining how well PCA captures data variability requires an understanding of the
variation described by each primary component. Greater variance explained suggests that the original
dataset&#39;s information is retained by the primary components.
Difference in dataset sizes: The training and testing datasets have different sizes, with 6237 samples in
the target variable and 5996 samples in the training set. This discrepancy has to be fixed because it
could cause mistakes while training and evaluating the model.
