PCA is a unsupervised algorithm

1. PCA Uses:
    - Noise filtering
    - Visualization
    - Feature extraction
    - Stock market prediction
    - Gene data analysis

2. The gole of PCA:
    - Identify patterns in data
    - Detect the correlation between variables
    - Reduce the dimensions of a d-dimensional dataset by projecting it onto a 
      (k)-dimensional subspace (where k<d)
    
3. The main functions of PCA:
    - Standardize the data
    - Obtain the Eigenvectors and Eigenvalues from the covariance matrix or     correlation matrix, or perform Singular vector decomposition.
    - Sort eigenvalues in decending order and choose the k eigenvectors that correspond to the k largest eigenvalues where k is number of dimensions of the new feature subspace (k=<d).
    - Construct the projection matrix W from the selected k eigenvectors.
    - Transform the original dataset X via W to obtain a k-dimentional feature subspace Y.

- Learn about the relationship between X and Y values 
- Find list of principle axes

2D and 3D view : https://setosa.io/ev/principal-component-analysis/