# FlavorFriend

FlavorFriend is a yelp restaurant reccomendation system that learns latent information about the relationships between users and restaurants.

Dataset: https://www.yelp.com/dataset

How to run:
In each notebook make sure to set the base_dir variable to the directory of the yelp dataset

First run data_cleaning.ipynb
 - This notebook cleans the yelp dataset to our specifications

Then run ncf.ipynb
  - This notebook runs the yelp dataset through a vanilla Neural Collaborative Filtering with Sentiment Augmentation

Finally run ncf_mf.ipynb
  - This notebook runs the yelp dataset through a Matrix Factorization - Neural Collaborative Filtering model with Sentiment Augmentation
  
