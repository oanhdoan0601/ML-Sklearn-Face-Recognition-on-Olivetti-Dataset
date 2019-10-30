# ML-Sklearn-Face-Recognition-on-Olivetti-Dataset
Machine Algorithms: 1. Logistics Regression 2. RandomForestRegressor 3. KNN 4. SVM 5. Naive Bayes (with PCA and without PCA)
Libraries: sklearn, Matplotlib, Pandas, Numpy
Olivetti Dataset: 
The data set contains 10 face images for each subject. The data set has 40 different person-owned,
facial images. Size of each image is 64x64. There are 40 distinct subjects, and each has 10 images
taken differently. (Hence the data set has 400 rows and pixel size of each image is 64 X 64). Names
of 40 people were encoded to an integer from 0 to 39, the images were taken at different times,
by varying the lighting, facial expressions (open / closed eyes, smiling / not smiling) and facial
details (glasses / no glasses).
performing multioutput regression on the Olivetti images and predicting the
faces.
Best results is on Logistics Regression (Train-70%: Test-30%), Accuracy 98.33% with PCA (With variance of 95% we could reduce to 103 principle components or
dimensions)
