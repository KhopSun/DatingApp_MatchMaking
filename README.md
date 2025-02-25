# 💘 Dating Algorithm Using Unsupervised Machine Learning

An ongoing project aimed at developing a dating algorithm using **Unsupervised Machine Learning** techniques, including **Hierarchical Agglomerative Clustering (HAC)** and **Principal Component Analysis (PCA)**, to cluster user profiles and identify similar profiles.

---

## 🚀 **Project Overview**
This project aims to improve the dating experience by clustering user profiles and recommending similar profiles based on feature and text similarity. The algorithm uses **Unsupervised Machine Learning** techniques to optimize matchmaking by calculating correlations within clusters. 

---

## 🚨 **Disclaimer**
- The **CSV files** containing user profile data used in this project are **generated** for the purpose of algorithm development and testing. They do not represent real user data or any real-world dating profiles. The data has been created partly to avoid violating the privacy of real users.

- This specific implementation of the algorithm **is not intended for direct use in any dating application**. Instead, it serves as a proof-of-concept to demonstrate the development and refinement of matchmaking techniques using **Unsupervised Machine Learning**.

---

## 🎯 **Key Features**
- **Clustering:** Profiles are grouped using **Hierarchical Agglomerative Clustering** to identify similar users.
- **Dimensionality Reduction:** **PCA** is used to reduce data complexity while preserving key features.
- **Similarity Calculation:** Identifies the **top 15 most similar profiles** by calculating correlations within clusters.
- **Evaluation:** Uses **Silhouette Coefficient** and **Davies-Bouldin Score** to evaluate clustering performance and determine the optimal number of clusters.

---

## 🧠 **Machine Learning Approach**
The algorithm applies **Hierarchical Agglomerative Clustering** to group profiles and **PCA** to reduce dimensionality, enabling the system to find similar profiles based on both **feature-based** and **text-based** similarities.

---

## 🧰 **Technologies Used**
- **Clustering & Dimensionality Reduction:** Hierarchical Agglomerative Clustering (HAC), Principal Component Analysis (PCA)
- **Machine Learning Framework:** Scikit-learn
- **Data Handling:** Pandas
- **Data Scaling & Vectorization:** StandardScaler, CountVectorizer
- **Text Preprocessing:** WordNetLemmatizer
- **Feature Engineering:** MultiLabelBinarizer
- **Evaluation Metrics:** Silhouette Score, Davies-Bouldin Score

---

## 🌟 **Acknowledgements**
Special thanks to my seniors and colleagues for their ongoing support and collaboration in developing this dating algorithm!
Also, thanks to Marco Santos for insightful Medium articles on dating algorithms using Machine Learning. The articles provided valuable resources for building the algorithm and understanding the key machine learning techniques involved.

