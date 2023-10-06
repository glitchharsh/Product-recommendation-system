
# Product Recommendation System

Built for Flipkart Hackathon round

This is a product recommendation system that demonstrates the use of three different approaches to building a recommendation system. Each has its own usecase, advantages and disadvantages discussed below.

## Popularity Based

This is the simplest approach for a recommendation system. The products are ranked on the basis of their popularity and displayed in that order. This is used for cold-start problem, i.e. when a new user joins the platform and we have no purchase history to tailor the recommendations.

## Collaborative Filtering

In this approach, the users' purchase history is used to find out similar users to filter out the products that the user might like. 

#### Advantages
- Can help users discover new interests
- No need for extensive cataloging of products

#### Disadvantages
- Cold Start problem
- Cannot handle new items

## Content-Based Filtering

This approach uses the similarities found in the products themselves to recommend new products to the user.

#### Advantages
- Can recommend niche items that very few other users are interested in
- No need for other users' data

#### Disadvantages
- Cold Start problem
- Low quality items may be recommended

### Datasets
Datasets are not added here due to file size restrictions by github.

Add the datasets to the Dataset folder
- https://www.kaggle.com/datasets/PromptCloudHQ/flipkart-products/
- https://www.kaggle.com/datasets/datafiniti/consumer-reviews-of-amazon-products

### Outputs
Output files are not added here due to file size restrictions by github.

- https://drive.google.com/drive/folders/1coxVgi_1ncs__RaXuyFgAWzGOqQwTa4A?usp=sharing