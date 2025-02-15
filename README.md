### KMeans

In this example we'll look at k-means clustering. This will break a dataset into N clusters, where we have to specify N.

### Gaussian Mixture Models

Ih this example we'll look at a GMM. This extends k-means, such that rather than having hard cluster boundary, we now have a set of disrtibutions, and we can capture uncertainty. For example, we'll be able to tell when a point is close to being part of two different classes.

### DBScan

Our final clustering method is DBScan. This one doesn't need us to specify the number of clusters. Instead we specifya minimum cluster size, and a proximity threshold, and it goes ahead and builds a set of clusters by finding points that are near each other. Nicely, it also considers noise, and so will attempt to filter out isolated points that are like nothing else, rather than trying to fit those into a cluster where they don't really go.
