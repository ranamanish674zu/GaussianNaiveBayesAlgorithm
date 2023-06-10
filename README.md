# GaussianNaiveBayesAlgorithm
### Gaussian Naive Bayes is a variant of the Naive Bayes algorithm that is specifically designed for continuous or numerical features. Unlike the standard Naive Bayes algorithm, which assumes categorical or discrete features, Gaussian Naive Bayes assumes that the features follow a Gaussian or normal distribution.The key idea behind Gaussian Naive Bayes is to estimate the parameters of the Gaussian distribution (mean and variance) for each class in the dataset. It assumes that the continuous features within each class are independent and have a Gaussian distribution.
### The algorithm works as follows:
### Data Preparation: Gaussian Naive Bayes requires a labeled dataset with continuous or numerical features.
### Prior Probability: Similar to the standard Naive Bayes algorithm, Gaussian Naive Bayes calculates the prior probability for each class in the dataset.
### Parameter Estimation: For each class, Gaussian Naive Bayes estimates the mean and variance of each feature. This is done by calculating the sample mean and sample variance of each feature for the instances belonging to that class.
### Likelihood Calculation: Given the estimated mean and variance for each class and feature, Gaussian Naive Bayes calculates the likelihood probability using the Gaussian probability density function (PDF).
### Posterior Probability: Using the prior probability and the likelihood probability, Gaussian Naive Bayes calculates the posterior probability for each class.
### Prediction: Finally, Gaussian Naive Bayes selects the class with the highest posterior probability as the predicted class for the input data.
## Gaussian Naive Bayes is particularly useful when dealing with continuous or numerical features that are assumed to follow a Gaussian distribution. It is a simple and efficient algorithm that can handle high-dimensional datasets. However, it assumes that the features are independent, which may not always hold in real-world scenarios.
