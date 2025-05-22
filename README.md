# Facebook Posts EDA and Clustering

This project performs an **Exploratory Data Analysis (EDA)** and **unsupervised clustering** on a dataset of Facebook page posts to uncover patterns in user engagement metrics such as reactions, comments, and shares.

## 📊 Project Objectives

- Clean and preprocess Facebook post data.
- Perform exploratory data analysis (EDA) to identify trends and relationships.
- Engineer meaningful features to represent user engagement.
- Apply K-Means clustering to group posts based on engagement metrics.
- Visualize and interpret clusters to gain actionable insights.

## 🧰 Tools and Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn


## 📈 EDA Highlights

- Analyzed distribution of post types.
- Identified `video` posts as generating the highest average engagement.
- Visualized time trends and relationships between likes, comments, and shares.

## 🤖 Clustering

- Used **MinMaxScaler** to normalize features.
- Selected features: `num_reactions`, `num_comments`, `num_shares`, `positive_reactions`, `negative_reactions`.
- Applied **K-Means clustering**:
  - Used the **elbow method** to determine optimal clusters.
  - Final model used **3 clusters** with a silhouette score of **0.736**.

## 📊 Cluster Interpretation

Each cluster represents a group of Facebook posts with similar engagement patterns. Future analysis may reveal:
- What type of content each cluster corresponds to.
- Optimal post strategies for higher engagement.



## 📎 Author

Developed by Malebo Phosa  

