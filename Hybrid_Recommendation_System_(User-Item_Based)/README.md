# General Information
Recommendation systems have become increasingly popular in recent years. It is used in many areas such as eCommerce Industry, Streaming Media Businesses, Online Gaming Business. Companies such as Netflix, YouTube, and Spotify, eBay, Alibaba, Amazon use recommendation systems. It can be defined as, systems that recommend products or services to users using various techniques. It is based on filtering and sorting.  

Some types are given and explained below.
> - **Association Rule Learning**  
> - **Content Based Filtering**  
> - **Collaborative Filtering** 
>  - **Memory-Based Filtering**
>    - **User-Based Filtering**
>    - **Item-Based Filtering**
>   - **Model-Based Filtering** 
  
**Association Rule Learning**  
It is a rule-based machine learning technique used to find patterns in data. It uses the apriori algorithm to find associations.  

You can view the Association Rule Based Recommendation System study here.  
[Association Rule Based Recommendation System](https://www.kaggle.com/code/omrttn/association-rule-based-recommendation-system)

**Content Based Filtering**  
Content-based filtering is an approach in recommender algorithms which makes use of content metadata to produce recommendations.

**Collaborative Filtering**  
"Collaborative Filtering is a technique used to identify relationships between pieces of data. This technique is frequently used in recommender systems to identify similarities between user data and items."
 - **Memory-Based Filtering**  
  - **User-Based Filtering**  
  It makes recommendations by using the information of users with similar liking habits.
  
  - **Item-Based Filtering**  
  It is based on the similarity of the liking structures of the products. 
  
 - **Model-Based Filtering**  
 "In this approach, Collaborative Filtering models are developed using machine learning algorithms to predict user’s rating of unrated items."  
   
     
   
![3](https://user-images.githubusercontent.com/78654212/208479033-496669da-1a24-40ee-95e7-807b6d103dfd.PNG)

  
  
# Business Problem and Datasets

Movie recommendations will be made for the user whose ID is given. Item-based and User-based filtering
methods will be used. There are 2 datasets. Information about the datasets columns is given below.  

**movie**
- **movieId :** Unique movie id.  
- **title :** Movie name
- **genres :** Category

**rating**
- **userid :** Unique user id.
- **movieId :** Unique movie id.
- **rating :** Rating given to the movie by the user.
- **timestamp :** Rating date
