# Athlete_Profiling_based_on_similar_characteristics

This project aims to cluster athletes based on similar characteristics (multi-modal dataset). 

Explanation :

Data Preparation (MICE Imputation Technique) - Athelete's multimodal data is prepared into one final csv file which merges the data values across different seasons(game seasons) after imputing the data using MICE

Deriving Feature importance - After merging the data, the feature importance score for the features were derived.

GMM Clustering - PCA was applied on the scaled csv data before applying clustering

Then for XAI component - The clustering was explained using LIME (Locally Interpretable Model Agnostic Explanation)
