# Bootcamp Final Project: Book Recommender

The aim of this project was to built a book recommender based on other users with similar taste. 

## Dataset
The dataset I used for the recommender consisted of the 10k most popular books on https://www.goodbooks.io/. The ratings were added from another source and are on a scale from 1 to 5. 

## Approach
1. Data Inspection and Cleaning (see data_cleaning.ipynb) 
2. Choosing a ML method based on available data and goal (item-based collaborative filtering, see: final presentation link)
3. Creation of user-item-matrix and modelling (knn nearest neighbor algorithm) (see Modeling.ipynb)
4. Optimization and testing of recommender (see Modeling.ipynb)


## Links
The dataset can be found here: https://www.kaggle.com/zygmunt/goodbooks-10k

The final presentation can be found here: https://docs.google.com/presentation/d/1qs5_Nk6CJwCaTMaG06-m1SB0Iz_k0hPMzAq-iCaxZ-I/edit#slide=id.g85a15b113d_0_37
