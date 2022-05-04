# ML assignment 3, option 1 documentation

## Data 

**Data: Amazon Fine Food Reviews**. The Amazon Fine Food Reviews dataset consists of 455,000 food reviews Amazon users left up to October 2012. 

Using [KMeans](http://scikit-learn.org/stable/modules/generated/sklearn.cluster.KMeans.html) clustering to create a **recommendation engine.** 

Objctive: Group the right features and number of clusters when the products in each cluster "seem" like they belong together. 


#### Clustering
https://github.com/Chayanitoey/machinelearning/blob/main/final_assignment_3/K_mean.jpg
Looking from the graph ![results](https://github.com/Chayanitoey/machinelearning/blob/main/final_assignment_3/K_mean.jpg)
I chose '21' as the optimal k-mean since the point represents the best evaluation of the data set. 
The point at '21' is the most descending one based on the range of 1 to 60 clusters and Intertia. 

### Results : 

![results](https://github.com/Chayanitoey/machinelearning/blob/main/final_assignment_3/assignment3_1.jpg)

- There are 20 clusters in total and based on this distribution, the min is '348' and max is '4097' - the range of the distributions is '3,749' 
- After conducting countless of trials and errors, I discovered that this # of clustering yields the most satisfying results. 

