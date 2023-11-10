# CryptoClustering
Module 19 Challenge

In this challenge, I will use Python and unsupervised learning to predict if cryptocurrencies are affected by 24-hour or 7-day price changes.

Plot data to view: 

<img width="814" alt="Screenshot 2023-11-10 at 4 18 26 PM" src="https://github.com/anastasiaskr2000/CryptoClustering/assets/131491720/9e997e5c-605a-48c3-a552-9b752da6b29b">

Step 1: Prepare the Data

<img width="1363" alt="Screenshot 2023-11-10 at 4 17 47 PM" src="https://github.com/anastasiaskr2000/CryptoClustering/assets/131491720/00717226-f4fd-4f03-9ce3-43ff941ccdf8">

Step 2: Find the Best Value for k Using the Original Scaled DataFrame

<img width="913" alt="Screenshot 2023-11-10 at 4 15 13 PM" src="https://github.com/anastasiaskr2000/CryptoClustering/assets/131491720/75486b09-ec76-4d65-a2b3-cebbbe2a20e8">

<img width="530" alt="Screenshot 2023-11-10 at 4 15 29 PM" src="https://github.com/anastasiaskr2000/CryptoClustering/assets/131491720/6c845482-1062-418a-bb80-d6ff899097ab">

Step 3: Cluster Cryptocurrencies with K-means Using the Original Scaled Data

<img width="1359" alt="Screenshot 2023-11-10 at 4 16 31 PM" src="https://github.com/anastasiaskr2000/CryptoClustering/assets/131491720/8d9784c4-0267-4692-8c62-1f717265f963">

<img width="909" alt="Screenshot 2023-11-10 at 4 19 12 PM" src="https://github.com/anastasiaskr2000/CryptoClustering/assets/131491720/b89e1a80-82b2-46fd-bdfc-830aa1e1a817">

Step 4: Optimize Clusters with Principal Component Analysis

<img width="329" alt="Screenshot 2023-11-10 at 4 20 23 PM" src="https://github.com/anastasiaskr2000/CryptoClustering/assets/131491720/b54202c5-2d96-4070-bba6-57e48bb1d90e">

Step 5: Find the Best Value for k Using the PCA Data

<img width="912" alt="Screenshot 2023-11-10 at 4 20 53 PM" src="https://github.com/anastasiaskr2000/CryptoClustering/assets/131491720/af5e9eb2-c04c-4e20-8fee-9cd988cde056">

Step 6: Cluster Cryptocurrencies with K-means Using the PCA Data

<img width="437" alt="Screenshot 2023-11-10 at 4 21 37 PM" src="https://github.com/anastasiaskr2000/CryptoClustering/assets/131491720/4843f77f-039c-4806-8d0e-2513bcc9d378">

<img width="938" alt="Screenshot 2023-11-10 at 4 22 02 PM" src="https://github.com/anastasiaskr2000/CryptoClustering/assets/131491720/63741207-4be3-4531-8056-98268b87e9ef">

#### Answer the following question: 

After visually analyzing the cluster analysis results, what is the impact of using fewer features to cluster the data using K-means is the lower inertia in PCA clusters that allows for clearer and more easily distinguishable visualization. The eblow curve in the second graph using  fewer features more clearly illustrates the ideal k-value of 4 while the scatter plot using primary clusters better separates the outliers (celsuis-degree-token) in the collection, allowing us to visually determine which crypto currency to avoid (havven, ontology) and which to invest in (bitcoin, monero). 

