Recommender System With Python
what is recommender system? A recommender system, or a recommendation system (sometimes replacing 'system' with a synonym such as platform or engine), is a subclass of information filtering system that seeks to predict the "rating" or "preference" a user would give to an item(Francesco Ricci, 2011). It is used in variety of fields including entertainment , E-Commerce, open web recommenders and social media platforms.

collecting-data-1024x834.pngR. J. Mooney & L. Roy (1999) give a perfect explaination of how recommender system work. Please see below:

Recommender systems usually make use of either or both collaborative filtering and content-based filtering (also known as the personality-based approach),[8] as well as other systems such as knowledge-based systems. Collaborative filtering approaches build a model from a user's past behavior (items previously purchased or selected and/or numerical ratings given to those items) as well as similar decisions made by other users. This model is then used to predict items (or ratings for items) that the user may have an interest in.[9] Content-based filtering approaches utilize a series of discrete, pre-tagged characteristics of an item in order to recommend additional items with similar properties.

Now companies are able to provide customers with more options to purchase products. The purpose of recommender system is to increase the amount of information of information that customers must process before they are able to selct which items they desire to buy.

Our project is to build a recommendation system for Electronic products on Amazon.

The graph below will give us clearn understanding of how Amazon recommends other products. We search for 4k HD Webcome and we click on one of them. after scrolling down, It shows the best rating HD Webcams:image.png

Source
The source for the project file can be found at this link below: http://jmcauley.ucsd.edu/data/amazon/

We are going to use the Electronics datasets only.

Steps
1- Import the data and Extract some information from the dataset.

2- Keep only customers that have more then 50 reviews.

3- Split the data into target and features and train and test sets.

4- Build Popularity Recommendation Model

5- Build Collaborative Filtering model.

6- Evaluate Both model.

7- Get top- K ( K = 5) recommendations. Since our goal is to recommend new products to each user based on his/her habits, we will recommend 5 new products.

8- Summarise your insights.
