# Data Science Quiz

### Instructions

- Fork and Clone
- Work on quiz
- Push back up to your repository

### Questions

1. A vector is given, `[2,3,9]`. What's the norm?
    9.695

2. I have a biased 6-sided die. P(T) = 0.45. What's the probability, if I flip the coin 100 times, that I will get exactly 14 heads?
    

3. What is the rank of a matrix?
    The number of linearly independant rows/columns

4. Why is rank important for Linear Regression?
    Since LR involves inverting the feature matrix, the matrix must be full rank in order to be inverted.

5. What is the purpose of the sigmoid function in a Logistic Regression model?
    Sigmoid converts log odds into probabilities

6. What is bias vs variance?
    Bias is the degree to which the models predictions deviate from the training data, variance is the degree to which the model fails to produce robust predictions on real world data.

7. What is a hyperparameter? What part of the dataset (train, validation or test) is responsible for determining this value? 
    A hyperparameter is a parameter in the model that can be tuned to make the model more accurate. Validation data helps us determine this value. 

8. Model selection via cross validation. What part of the dataset (train, validation or test) is responsible for choosing the best model?
    Validation

9. What is parametric vs non-parametric model?
    parametric models have a fixed number of learned parameters, while non-parametric models require more data and have no learned parameters making them difficult to explain and interpret. 
    
10. What models do you need to scale the data prior to fitting?
    parametric models

11. What is entropy? Which model uses this concept?
    a measurement of diversity in a sample, decision trees and random forests

12. How is a random forest generated?
    by bagging data with replacement to create many trees and feature bagging to determine features

13. How do you determine the correct number of clusters when using KMeans?
    elbow method, or silhouette score

14. What is a dendrogram?
    binary tree of clusters

15. What is linkage?
    cluster distance

16. How does a recommender model work?
    uses NMF(non-negative matrix factorization) to determine hidden features

17. How can you reduce the number of features in a model?
    a). Lasso regression
    b). correlation matrix between all features so that the most important can be utilized
    c). PCA to compress multiple features

18. What is a good use of PCA?
    plotting high dimensional data on 2d or 3d plots to visualize the data

19. In general, how do neural networks "learn"?
    through backpropagation, optimizing the loss funtion to adjust the weights and bias

20. What is your favorite model? Why?
    Neural Networks - because there doesn't seem to be a limit to what you can put through the model that it cannot learn as long as you have enough data to train the model. To me it is the model that defines machine learning due to the wide range of data that the model can learn from, being numerical or even image data. 