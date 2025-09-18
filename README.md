 1. Problem Statement
 The goal of this project is to segment mall customers into meaningful groups using the K-Means
 clustering algorithm. The segmentation helps the business understand customer behavior and
 create targeted marketing strategies.
 2. Dataset Description
 Dataset: Mall Customers Dataset (from Kaggle).
 Features:- CustomerID: Unique ID (dropped during preprocessing).- Gender: Male/Female.- Age: Customer age.- Annual Income (k$): Annual income in thousands.- Spending Score (1–100): A score assigned by the mall based on customer spending behavior.
 3. Methodology
 The project was carried out in the following steps:
 1. Data Preprocessing: Dropped CustomerID, encoded Gender, and scaled numerical features.
 2. Finding Optimal Clusters: Used Elbow Method and Silhouette Score.
 3. Model Training: Applied K-Means clustering with k=5.
 4. Visualization: Plotted income vs. spending score to show clusters.
 5. Analysis: Interpreted clusters based on age, income, and spending behavior.
 4. Results & Insights
 Cluster
 Cluster 0
 Cluster 1
 Cluster 2
 Cluster 3
 Cluster 4
 Characteristics
 Premium Customers - High income, high spending (Avg Age ~32).
 Cautious Rich - High income, low spending (Avg Age ~36).
 Older Low Spenders - Avg income, low spending (Avg Age ~50, mostly female).
 Young Enthusiastic - Low income, medium-high spending (Avg Age ~25).
 Older Men - Moderate income, low spending (Avg Age ~56, all male).
 5. Conclusion
 The K-Means algorithm successfully divided mall customers into 5 distinct groups. This
 segmentation allows the mall to design targeted marketing campaigns. For example, Premium
 Customers (Cluster 0) can be offered loyalty programs, while Cautious Rich (Cluster 1) may need
 attractive discounts to increase spending. This project demonstrates how unsupervised machine
 learning can provide valuable business insights.
 6. Future Work
Possible extensions of this project include:- Using other clustering algorithms like DBSCAN or Hierarchical clustering.- Adding more customer features (e.g., frequency of visits, product categories purchased).- Deploying the model in a dashboard for real-time customer segmentation
Clone the repository:

git clone https://github.com/Bhanuprakashbondhala/k-means-clustering-Mall-Customer-Segmentation.git

Install dependencies:

pip install -r requirements.txt

Run the Jupyter Notebook:

jupyter notebook Titanic_Project.ipynb

🙌 Author

BUNNY (Bhanu Prakash Bondhala) 📧 [mr.bunny3696@gmail.com] 💼 [https://www.linkedin.com/in/bhanu-prakash-bondhala-a4a695255/]
