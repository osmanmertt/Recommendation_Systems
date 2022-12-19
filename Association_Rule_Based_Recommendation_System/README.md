# General Information
Association Rule Learning is a rule-based machine learning technique used to find patterns in data. In other words, it is aimed at revealing the features that are related to each other and determining the size of the relationship between them.

For example, with this method, we can determine that those who buy X product also receive Y product. We can aim to increase sales by placing these products in close places in the market.

To summarize, past data is analyzed with association rule learning and associations between them are found so that future strategies can be developed.

![1](https://user-images.githubusercontent.com/78654212/208477755-d30dcee1-88ff-4f98-9ed8-18d1cb2873a1.PNG)


Various algorithms are used for Association Rule Learning. The most popular algorithm among these is the **Apriori Algorithm**. Apriori algorithm has some parameters. These parameters are listed below.

- **Support**  
- **Confidence**  
- **Lift**  


**Support**  
Indicates the rate at which a relationship repeats across all transactions. Considering the formula, it can also be said that the probability of X and Y occurring together. Support value is found by dividing the frequency of occurrence of X and Y together by all transactions.
> ***Support(X,Y) = Freq(X,Y) / N***

**Confidence**  
It can be defined as indicating the probability that customers who buy product X will buy product Y.The frequency of occurrence of X and Y together is divided by the frequency of sale of X.
> ***Confidence(X,Y) = Freq(X,Y) / Freq(X)***

**Lift**  
It is the value that expresses how many times the probability of buying Y increases when X is purchased.  
> ***Lift = Support(X,Y) / (Support(X) * Support(Y))***
  
   
   
For example, let's examine the situation of those who buy the cake product, also buy the coffee product.
  
-As can be seen in the table below, the support value is 0.054. Cake and Coffe products are seen together in 5% of all shopping.  
  
-Confidence value is 0.53. It has been observed that 53% of customers who buy cake also buy coffe.  
  
-The lift value is 1.11. The sales of the Coffe product increase 1.11 times in the purchases with the Cake product.

![2](https://user-images.githubusercontent.com/78654212/208477819-5c9763e0-67ef-4223-8970-e74aca67ba97.PNG)

# Business Problem and Dataset
In this study, the dataset of an online service platform will be used. This platform brings together those who provide service and those who want to receive service. A recommendation system will be created with Association Rule Learning.

Information about the columns is given below.

* **UserId :** Customer Id
* **ServiceId :** They are anonymized services belonging to each category. A ServiceId can be found under different categories and refers to different services under different categories.
* **CategoryId :** They are anonymized categories. (Example: Cleaning, shipping)
* **CreateDate :** The date the service was purchased
