# P8451_HW4_ML

Part I: Implementing a Simple Prediction Pipeline

The New York City Department of Health administered a questionnaire on general health and physical activity among residents. Using the dataset class4_p1.csv, fit and evaluate two prediction models using linear regression. The aim of the models are to predict the number of days in a month an individual reported having good physical health (feature name: healthydays). A codebook is provided so you can look-up the meaning and values of each feature in the dataset. (Note the codebook lists information on features that are not included in your dataset).

Your analytic pipeline should include the following:

1. Perform basic data cleaning. Note which features are continuous, which are categorical and ensure they are being stored that way in your R dataset (That is, if categorical variables have been read-in as continuous variables, convert them to factors)

2. Partition data into training and testing (use a 70/30 split)

3. Fit two prediction  models using  different subsets of the features in the training data. Features can overlap in the two models, but the feature sets should not be exactly the same across models. Clearly state which features were used in the two models.

4. Apply both models within the test data and determine which model is the preferred prediction model using the appropriate evaluation metric(s). 

5. Describe one setting (in 1-2 sentences) where the implementation of your final model would be useful.

 

Part II: Conducting an Unsupervised Analysis

Using the dataset from the Group assignment Part 3 (USArrests), identify clusters using hierarchical analysis.

6. Conduct a hierarchical clustering analysis. Use a Euclidian distance measure to construct your dissimilarity matrix. Use complete linkage.

7. Determine the optimal number of clusters using a clear, data-driven strategy.

8. Describe the composition of each cluster in terms of the original input features

9. Pretend that the data are from 2022 and not 1973. Describe one research question that can be addressed using the newly identified clusters. Briefly comment on any scientific or ethical considerations one should review before using these clusters for your specific question. NOTE: The clusters can be used as an exposure, an outcome or a covariate. (2-4 sentences)

10. Optional Repeat analysis with a different linkage method (e.g. single or average). Do the clusters change?