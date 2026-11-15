
# Lab 10 – Unsupervised Learning
## Group 4 – Individual Contribution Journal
**Course:** ITAI 1371 – Introduction to Machine Learning

---

### Member 1: Patrick Rostand Gandjouon Tchassem
**Contribution:**

For this lab, I worked on completing and testing the Google Colab notebook. I went through the different coding tasks, ran the cells, and checked the outputs to make sure the results were correct.

I worked on the K-Means clustering section, including the Elbow Method, where we tested different numbers of clusters to find a suitable value of K. I also completed the clustering visualization using K = 4 and verified that the 300 data points were divided into four clusters of 75 points each.

I also worked on the PCA section using the Iris dataset. I ran the code to reduce the original four features to two principal components and checked the explained variance results, which showed that about 95.81% of the variance was preserved.

In addition, I reviewed the results and prepared answers for the Knowledge Check questions based on the code and outputs. I also helped organize the group's GitHub repository by preparing separate reflection and contribution files so every member could document their own work.

My main contribution was working through the notebook, checking the results, and helping organize the project files for the group submission.

---

### Member 2: Saimi Manasiya
I contributed to completing this lab by working through the different tasks related to unsupervised learning. I used Google Colab and Python to understand and apply K-Means Clustering and Principal Component Analysis (PCA). First, I worked with a synthetic customer dataset containing 300 data points and used the Elbow Method to calculate inertia values for different numbers of clusters, from 1 to 10. After analyzing the elbow graph, I identified four as the optimal number of clusters and applied the K-Means algorithm to group the data points. I also created scatter plots to display the clusters and their centroids and checked the number of data points in each group. In the second part, I worked with the Iris dataset, standardized its four features, and used PCA to reduce them to two principal components. I also created a visualization and reviewed the explained variance results to understand how much information was retained after reducing the dimensions. By completing these activities, I practiced using Python libraries, writing code, interpreting graphs, and understanding how machine learning algorithms work with different datasets.


---

### Member 3: Kenneth Kouokam

My contribution to Lab 10 focuses on explaining the Elbow Method and interpreting the clustering
results reported by the group. The experiment compares inertia for K values from 1 to 10. Inertia
measures the sum of squared distances between the observations and their nearest cluster centers.
My explanation describes why we look for a noticeable slowdown in the decrease rather than simply
choosing the largest K. The group selected K=4, which also matches the four centers used to
generate the synthetic dataset.

My section also explains the reported result of four clusters containing 75 observations each.
Together, these groups account for all 300 observations. Each centroid represents the mean position
of the points assigned to that cluster, rather than necessarily being an actual customer. Equal group
sizes are a result of this example, not a requirement of K-Means. The interpretation distinguishes
compact groups in synthetic data from proven customer categories and explains why the cluster
labels are identifiers, not rankings.


---

### Member 4: Anavictoria Cavazos

 My contribution to this assignment was to ensure that the completed PCA code used standardized iris features, as seen by using 
 StandardScaler() (X_scaled) before running PCA(n_components=2). These two components preserved 95.81% of the total data variance, 
 indicating that the four original flower measurements were still captured. They also preserved visual cluster separation, which helps 
 project 4D flowers onto the 2D scatter plot where the iris are still separated clearly. The losses that occurred because of the two 
 components were 41.9% of minor variance and not being able to work with specific measurements or direct feature interpretability. 





---

### Member 5: [Enter Full Name]
**Contribution:**


---
