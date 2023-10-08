# Improved-KNN-through-Hyperplane-Division-and-Instance-Removal
Quarter 2 Project for ML at TJHSST. By Kaushik Siruvuri and Liam Baird
This repository contains the final paper, presentation, and code of the project.
Abstract

The KNN algorithm is a lazy learning algorithm requiring the computer to iterate through all data points in a training data set. For datasets with multiple dimensions and a high instance count, this is a very high cost in both time and memory, making KNN unviable. 
To solve this issue, we propose reducing the training data to make KNN more time and space efficient. To accomplish this, we plan to add two steps before the lazy learning process. First, data should be aggregated and reduced in size and space to remove unneeded data. Next, the data should be randomly split by hyperplanes, after which KNN will run. The testing point would only be compared to the aggregated points inside the same group of points split by the hyperplane. This leads to far fewer distance comparisons needing to be made, thus improving the speed of subsequent classifications. The combination of both of these methods should lead to a noticeable decrease in time and space complexity, especially on larger datasets.
