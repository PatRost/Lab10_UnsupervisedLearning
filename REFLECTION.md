
# Lab 10 – Unsupervised Learning
## Group 4 – Reflection Journal
**Course:** ITAI 1371 – Introduction to Machine Learning

---

### Member 1: Patrick Rostand Gandjouon Tchassem
**Reflection:**

This lab helped me better understand how unsupervised learning works and how it is different from supervised learning. Before this lab, I was more familiar with models that use labeled data to make predictions. Working with K-Means and PCA helped me see how machine learning can also find patterns in data without having the correct answers provided.

One part I found interesting was the Elbow Method. At first, I thought choosing more clusters would always give better results because the inertia keeps decreasing. However, after running the code and looking at the graph, I understood why we need to find a balance. In our results, K = 4 was a good choice because the inertia dropped significantly before that point and then started to level off.

I also enjoyed working with PCA because it showed me how we can simplify a dataset without losing most of its information. We reduced the Iris dataset from four features to two principal components and still kept about 95.81% of the variance. Seeing the different Iris species on the graph made the concept easier to understand.

Overall, this lab gave me more confidence in working with machine learning algorithms in Google Colab. I learned that understanding the results is just as important as getting the code to run successfully. I can see how these techniques could be useful in real-world situations such as customer segmentation, identifying patterns in large datasets, and simplifying complex information.

---

### Member 2: Saimi Manasiya
This lab was a valuable learning experience because it helped me understand how unsupervised learning can discover hidden patterns in data without using labeled information. I learned how K-Means Clustering separates similar data points into groups and how the Elbow Method helps determine a suitable number of clusters. I also gained a better understanding of PCA and how it simplifies a dataset by reducing the number of features while preserving important information. One thing I found interesting was visualizing the clusters and seeing how the Iris dataset could be represented using only two principal components instead of four. Although some parts of the coding and understanding the graphs required more attention, completing each task helped me become more comfortable with Python and machine learning concepts. Overall, this lab improved my practical knowledge and helped me understand how unsupervised learning techniques can be useful for analyzing larger datasets and identifying patterns.

---

### Member 3: Kenneth Kouokam

For Module 10, my role focuses on the Elbow Method and the meaning of the resulting clusters. The
main idea I take from this exercise is that grouping data involves a choice about how much detail is
useful. K-Means needs a value of K before it can produce the groups. That makes the elbow plot
important: it helps explain the choice instead of treating the number of clusters as an arbitrary setting.

Inertia gives that choice a numerical basis, but minimizing it without considering complexity would
miss the purpose of the exercise. Adding more cluster centers generally lets observations sit closer to
a center. At the extreme, giving every observation its own center would produce zero inertia, but it
would no longer provide a useful summary. I see the elbow as a compromise: it suggests a point
beyond which additional groups provide a smaller improvement. It is a guide for interpretation, not
proof that one value is always correct.

The group reported choosing four clusters, and the supplied setup generated data around four
centers. That agreement makes sense for this controlled example. It also reminds me that a synthetic
dataset is easier to interpret because its construction is known. In a real customer dataset, I would
not know the correct number of groups in advance. I would want to examine whether the groups
make sense for the intended use, as well as whether the plot has a clear bend.

The reported counts of 75 observations in each cluster are another useful detail to interpret carefully.
They add up to all 300 observations, but equal sizes are not a rule of K-Means. The algorithm assigns
points according to distance rather than filling groups to a fixed size. A centroid summarizes the
average position of its group, so it need not represent a customer who actually exists. Likewise, a
cluster numbered three is not more valuable than a cluster numbered zero; the numbers simply
distinguish the groups.

This exercise connects to the earlier labs by showing that a numerical result still needs an
explanation. There is no target label used to train this clustering model, so I should not describe its
result as classification accuracy. My takeaway is to ask what the groups represent, why that number
of groups was chosen, and what the data allows us to conclude. A question I would like to explore is
whether increasing the noise would make the elbow less clear and change the resulting group sizes.


---

### Member 4: Anavictoria Cavazos

After working through Lab 10, I learned more about how K-Means clustering works and how it functions for unsupervised learning. In short, 
K-Means clustering helps group unlabeled data points based on similarities. However, before that was put into use, the elbow method had 
to be used first, which helped determine the number of groups that would be used.

During the elbow method, it was seen that k = 4 was the 
best number, which just showed how the elbow method in the lab helped figure out the ideal number of clusters. It was seen how the 
inertia would drop sharply as the number of clusters went up, but once the number passed 4, it would just split the existing groups, 
which showed why 4 was the best number of clusters. 

Overall, this lab helped me understand what can be used for unsupervised learning and 
how to apply it by practicing first how it was used for the customer dataset and comparing this lab to prior labs where supervised 
learning was in use. 


---

### Member 5: [Enter Full Name]
**Reflection:**



---
