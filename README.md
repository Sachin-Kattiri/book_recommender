# Recommender System 

### What are recommender systems 

- Recommendation systems, or recommender systems, are software engines designed to suggest items to users depending on previous likes, dislikes, interests, product engagement and interaction, etc. 

- Recommender systems keep users interested in the site.

### We are Surrounded with Recommender systems: 

- OTT 
    - Amazon
    - Netflix 
    - Hotstar 
    - Jio Cinema
    -----> For that matter every ott tries to keep their customeres engaged in the the service.

- Music Apps
    - Spotify 
    - Wynk 
    - Jio Saavan 
    - Apple Music 

- Food Apps: 
    - Zomato 
    - Swiggy 

- Instant Delivery Apps: 
    - Zepto 
    - Blinkit
    - Big Basket 

- Social Media 
    - Instagram 
    - Facebook 
    - Youtube 
    - Youtube shorts 
    - Tik Tok 
    - Twitter

- Shopping 
    - Flipkart 
    - Myntra
    - Amazon 

- Medical Deliveries 
    - 1mg 
    - Medplus 
    - Apolo 

All the apps which are commonly used in our day to day have recommendation systems which try their level best not to leave the app. 

We can even say that every app, website tries their level best to keep the customers engaged in their service as much as possible to generate revenue. 

---

### Why Recommender Systems : 

1. To Increase Sales : --> Better of company & Every one wants to make money. 
2. To decrease load on the system : --> As we make the suggestion than the customer searching continiously.
3. Increasing engagement and Satisfaction : --> More engagement and more page real estate.

--- 

### Diffrent Types of Recommender Systems 

##### 1. Popularity Based Recommendation System : 

A Popularity Based Recommendation System is a type of recommender system that suggests items to users based on the overall popularity of the items. 

Eg: - Trending Section on Youtube 
    - Trending on Twitter 
    - Top 100 Imdb movies 
    - Top 100 Songs of the year Radio/Youtube


##### 2. Content Based Recommendation System : 

A Content-Based Recommendation System is a type of recommender system that suggests items to users based on the features or attributes of items they have shown interest in. This approach relies on the similarities between items, which are typically derived from their content

##### 3. Collaborative filtering : 


Collaborative Filtering is a method used in recommendation systems that makes automatic predictions (filtering) about the interests of a user by collecting preferences or taste information from many users (collaborating). The underlying assumption of collaborative filtering is that if a person A has the same opinion as a person B on an issue, A is more likely to have B's opinion on a different issue than that of a randomly chosen person.

There are two main types of collaborative filtering: **user-based** and **item-based**.

###### User-Based Collaborative Filtering

User-based collaborative filtering recommends items to a user based on the preferences of other users who are similar to them.

###### Item-Based Collaborative Filtering

Item-based collaborative filtering recommends items to a user based on the similarity between items. This method is particularly useful when the number of users is much larger than the number of items.


##### 4. Hybrid Recommender System 

A Hybrid Recommendation System combines multiple recommendation techniques to leverage their complementary strengths and improve the quality of recommendations. 

- The goal is to mitigate the limitations of individual methods and enhance overall performance by using a mix of content-based, collaborative filtering, and sometimes other techniques like demographic or knowledge-based recommendations.

---


# Content

- **The Book-Crossing dataset comprises 3 files.**

**Users:**

Contains the users. Note that user IDs (User-ID) have been anonymized and map to integers. Demographic data is provided (Location, Age) if available. Otherwise, these fields contain NULL-values. 

- User ID : Used to Identify User an anonymized number
- Location : Location of the User
- Age : Age of the User

**Books:**

Books are identified by their respective ISBN. Invalid ISBNs have already been removed from the dataset. Moreover, some content-based information is given (Book-Title, Book-Author, Year-Of-Publication, Publisher), obtained from Amazon Web Services. Note that in case of several authors, only the first is provided. URLs linking to cover images are also given, appearing in three different flavours (Image-URL-S, Image-URL-M, Image-URL-L), i.e., small, medium, large. These URLs point to the Amazon web site.

- ISBN : Unique Number to Identify the Book 
- Book-Title : Book title 
- Book-Author : Author of the Book
- Year-Of-Publication : The year when the book was published
- Publisher : Name of the publisher who published the book
- Image-URL-S : Amazon Image URL for the book in small size 
- Image-URL-M : Amazon Image URL for the book in medium size
- Image-URL-L : Amazon Image URL for the book in large size

**Ratings:**

Contains the book rating information. Ratings (Book-Rating) are either explicit, expressed on a scale from 1-10 (higher values denoting higher appreciation), or implicit, expressed by 0. 

- User-ID : 
- ISBN : 
- Book-Rating : Rating given by the user for a book. 

---
