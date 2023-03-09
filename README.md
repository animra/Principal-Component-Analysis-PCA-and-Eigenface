# Principal Component Analysis (PCA) and Eigenface
* Used PCA to analyze face images by using Python Language
* Used faces.dat each row represents an image (400 images), and each column represents a pixel (64 × 64 = 4096 pixels)
* Displayed the 200th image.
* Removed the mean of the images, and then display the 200th image.
* Performed PCA on the mean-centered data matrix. You can either implement PCA by yourself using eigenvalue decomposition over the sample covariance matrix, or use a existing machine learning toolbox. Sorted the eigenvalues in a descending order and plot them.
* Found the last (i.e., 400th) eigenvalue is 0 and explained why?
* Based on the eigenvalues, determined the dimensionality of the data we wanted to keep (i.e., how many principal components you want to keep), which accounts for most of the variance. Explain your reason.
* Displayed the top-5 leading eigenvectors (corresponding to the top-5 largest eigenvalues) in 5 figures.
