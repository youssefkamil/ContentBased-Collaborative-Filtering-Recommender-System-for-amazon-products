# Collaborative-Filtering-Recommender-System-for-amazon-products

## products Recommender System
![image](https://user-images.githubusercontent.com/37241010/155924749-c3d0d4cb-d6a1-4ba1-b1c9-dfdb81f6c8af.png)


## Collaborative Filtering
#### Steps:

- Get products dataframe (given data)
- Get users ratings dataframe (given data)
- Get input user ratings (user input/assumption)
- Learning the similarity weights (Pearson Correlation)
- Find the recommendations (user profile * original products categories)



#### Advantages and Disadvantages of Collaborative Filtering
##### Advantages
- Takes other user's ratings into consideration
- Doesn't need to study or extract information from the recommended item
- Adapts to the user's interests which might change over time
##### Disadvantages
- Approximation function can be slow
- There might be a low of amount of users to approximate
- Privacy issues when trying to learn the user's preferences



## Content-Based Filtering
#### Steps:

- Get products dataframe with categoties (given data)
- Get input user ratings (user input/assumption)
- Weighing the categories (input user ratings * user products categories)
- Get input user profile (sum of user weighted categories)
- Find the recommendations (user profile * original products categories)

#### Advantages and Disadvantages of Content-Based Filtering
##### Advantages
- Learns user's preferences
- Highly personalized for the user
##### Disadvantages
- Doesn't take into account what others think of the item, so low quality item recommendations might happen
- Determining what characteristics of the item the user dislikes or likes is not always obvious
