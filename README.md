# market_place_clustering
Help marketing & communication teams having in-depth understanding of customer behavior.
Like any other project, very first step consists in data exploratory. Just to get to know data we are going to work with. Hence, result shows us
how many entries, features, data type, duplicated rows, missing values we have across all dataset. 
As we deal with market place data, sales figures are key items. It is important to visualize sales over time (value/volume).
Once it is done, next thing is to create criteria that we think help to categorize customers. Here we decide to set up 4 KPI: Recency, Frequency
Monetary and Delivery. This leads to create a new dataset we are going to use along next steps.
Next is KMeans and DBSCAN use to get customer clustering. From algorithm outputs, KMeans is best sized to cluster samples, boxplots are then used for
customer behavior interpretation purposes.
Last thing: Do we need to reshape KMeans model over time because customer behavior changes ? This is the last step we go through in that project.
