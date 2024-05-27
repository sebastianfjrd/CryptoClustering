# CryptoClustering - Module 11 

In this project, the goal was to uderstand the K-means algorithm and principal component analysis (PCA) to classify cryptocurrencies according to their price fluctuations across various timeframes (24hrs, 7 days, 30 days, 60 days, 200 days and 1 year). 
This project was broken down in the following tasks:

Finding the Best Value for k Using the Original Scaled DataFrame:

Utilized the elbow method algorithm to determine the optimal value for k within a range of 1 to 11.
Employed visualizations to identify the optimal value for k by plotting inertia values.
Concluded that the best value for k was 4.
Clustered Cryptocurrencies with K-Means Using the Original Scaled Data:

Initialized a K-means model with four clusters based on the determined optimal value for k.
Fitted the K-means model with the original scaled data.
Predicted clusters to categorize cryptocurrencies and generated a scatter plot for visualization.
Optimized Clusters with Principal Component Analysis (PCA):

Established a PCA model to reduce feature dimensions to three principal components.
Calculated the total explained variance of these components, revealing approximately 89.5% explanatory power.
Constructed a new DataFrame containing PCA data with the "coin_id" index set.
Found the Best Value for k Using the PCA Data:

Applied the elbow method algorithm to identify the optimal value for k using PCA-transformed data.
Visualized the inertia values to determine that the best value for k remained 4, consistent with the original data.
Clustered Cryptocurrencies with K-Means Using the PCA Data:

Initialized a K-means model with four clusters based on the determined optimal value for k.
Fitted the K-means model with PCA-transformed data and predicted clusters for cryptocurrency grouping.
Generated a scatter plot using PCA components PC1 and PC2 for visualization.
Determined the Weights of Each Feature on Each Principal Component:

Created a DataFrame to illustrate the weights of each feature for each principal component.
Identified features with significant positive or negative influence on each component.
Overall, this project effectively applied K-means clustering and PCA techniques to classify cryptocurrencies based on their price fluctuations. By optimizing clusters and identifying feature weights on principal components, valuable insights into the underlying structure of the cryptocurrency market were obtained. This project serves as a practical demonstration of leveraging unsupervised learning techniques to gain insights from complex financial datasets.
