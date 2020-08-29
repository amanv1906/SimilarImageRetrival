# SimilarImageRetrival
The task is to find the similar image in the dataset when the query image is passed kind of Image Search Engine.

So there are different method for doing this task like color histogram and many more .

I done this using auto encoder . first I trained the deep autoencoder and take the encoder part to predict the image features.

For searching the image I used nearest neighbour technique KNN and use the cosine distance when the distance is small i returned the N closest feature for image .

For finding the cluster i used Kmean and find optimal cluster with elbow method.

