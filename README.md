# Linear Algebra and Probability
## Dataset
The dataset taken for study is the ***Wine quality dataset*** consisting of 1599 rows and 12 columns.
## Preprocessing
The dataset is loaded from the csv file. The null values in the columns are replaced with the mean values of the respective columns.
## Extracting vectors
The ***alcohol*** and ***citric acid*** columns are extracted as vectors.
## Eigen decomposition
A feature matrix is created using the ***alcohol*** and ***density*** column. The covariance of this feature matrix is calculated. Eigen decomposition is performed on this covariance matrix.
## Interpreting the distribution of the wine quality
The skewness of the ***quality*** column is 0.22 which indicates that the quality scores are moderately and positively skewed.