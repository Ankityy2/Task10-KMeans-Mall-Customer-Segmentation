# Mall Customer Segmentation using K-Means Clustering

## Project Overview

This project demonstrates the implementation of K-Means Clustering, an unsupervised machine learning algorithm, on the Mall Customers Dataset. The objective is to segment customers into distinct groups based on their annual income and spending score, enabling better customer understanding and targeted business strategies.

Unlike supervised learning algorithms, K-Means does not require labeled data. Instead, it identifies natural patterns and groups within the dataset.

---

## Dataset Information

### Dataset Name

Mall Customers Dataset

### Dataset Description

The dataset contains customer information collected from a shopping mall, including demographic details and purchasing behavior.

### Features

* CustomerID
* Gender
* Age
* Annual Income (k$)
* Spending Score (1–100)

### Features Used for Clustering

* Annual Income (k$)
* Spending Score (1–100)

These features were selected to identify customer spending patterns and income-based segmentation.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-Learn
* Google Colab

---

## Project Workflow

### 1. Data Loading

The Mall Customers dataset was imported using Pandas and examined to understand its structure and contents.

### 2. Data Exploration

Performed exploratory analysis using:

* Dataset shape
* Dataset information
* Statistical summary
* Feature inspection

### 3. Feature Selection

Selected:

* Annual Income (k$)
* Spending Score (1–100)

These features provide meaningful insights into customer purchasing behavior.

### 4. Elbow Method

The Elbow Method was applied to determine the optimal number of clusters.

WCSS (Within Cluster Sum of Squares) was calculated for different values of K ranging from 1 to 10.

The elbow point was used to identify the most appropriate number of clusters.

### 5. K-Means Clustering

A K-Means clustering model was trained using the optimal K value obtained from the Elbow Method.

The algorithm grouped customers into distinct clusters based on feature similarity.

### 6. Cluster Assignment

Each customer was assigned to a cluster representing a specific customer segment.

### 7. Cluster Visualization

Customer segments were visualized using scatter plots to understand grouping patterns.

### 8. Centroid Analysis

Cluster centroids were identified and visualized to represent the center of each customer segment.

---

## Deliverables

* Trained K-Means Clustering Model
* Cluster Labels
* Elbow Plot Visualization
* Customer Segmentation Plot
* Centroid Visualization

---

## Results

### Optimal Number of Clusters

* K = 5 (Based on Elbow Method)

### Customer Segments Identified

The algorithm successfully grouped customers into distinct segments such as:

* High Income – High Spending
* High Income – Low Spending
* Low Income – High Spending
* Low Income – Low Spending
* Average Income – Average Spending

### Business Insight

Customer segmentation helps businesses:

* Identify premium customers
* Design targeted marketing campaigns
* Improve customer retention
* Optimize product recommendations

---

## Visualizations

### Elbow Method Plot

Used to determine the optimal number of clusters by analyzing WCSS values.

### Customer Segmentation Plot

Visual representation of customer groups formed by K-Means clustering.

### Cluster Centroids Plot

Displays the center point of each cluster and helps understand cluster characteristics.

---

## Key Concepts Learned

* Unsupervised Learning
* K-Means Clustering
* Customer Segmentation
* Elbow Method
* Cluster Formation
* Centroids
* WCSS (Within Cluster Sum of Squares)
* Pattern Discovery

---

## Interview Questions

### What is K-Means Clustering?

K-Means is an unsupervised machine learning algorithm that groups similar data points into clusters based on distance from cluster centroids.

### How do you choose K?

The Elbow Method is commonly used to determine the optimal number of clusters. The value of K is selected where the decrease in WCSS starts slowing down significantly.

### What are Centroids?

Centroids are the central points of clusters. Each data point is assigned to the nearest centroid during clustering.

### What is WCSS?

WCSS (Within Cluster Sum of Squares) measures the total distance between data points and their respective cluster centroids. Lower WCSS indicates tighter clusters.

---

## Conclusion

K-Means Clustering was successfully implemented on the Mall Customers Dataset to perform customer segmentation.

The Elbow Method was used to determine the optimal number of clusters, and customers were grouped based on annual income and spending behavior. Cluster and centroid visualizations provided valuable insights into customer purchasing patterns.

This project demonstrates the practical application of unsupervised learning techniques for customer analytics and business decision-making.

---

## Repository Structure

Task10-KMeans-Mall-Customer-Segmentation/

├── Task10_KMeans_Clustering.ipynb

├── Mall_Customers.csv

├── elbow_plot.png

├── clusters.png

├── centroids.png

├── README.md

---

## Author

Ankit Yadav

