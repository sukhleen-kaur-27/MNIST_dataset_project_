

## Problem statement

Investigate the effect of training set size on the classification performance for the MNIST-Fashion dataset.


## Steps that I'm using to investigate and complete this project :

1.   Load data set and check for missing values.
2.   Plotting images from the dataset.
3.   Create a function to split the function into desired size.
4.   Create a Pipeline to scale the data, apply PCA to reduce dimensions and apply KNN to make predictions.
5.   Visualize to check how does the size of the dataset affect the predictions.

## Where to checkout the results?

Use collab to check out the results. 

## How to load the dataset ?

I have provided the link to the csv file of the train set. 

Download the file and then upload it to collab.

I could not create a direct link to the train set file since it is a huge file.

For test set the link is already create no need to download anything.

## Conclusion 

From the accuracy score we can see that the bigger the size of the train set the better is the prediction.
We can confirm that in the visuals as well that the accuracy score increases as the train set size increases.
This is because the train set has more data to learn from and can learn different types of patterns.
Hence, while training a machine learing model we should use large datasets.
