# **Customer Segmentation Using K-Means Clustering**

## **📌 Project Overview**

This project focuses on Customer Segmentation using the K-Means clustering algorithm. The goal is to group customers based on their Annual Income and Spending Score to identify patterns in customer behavior.

## **📂 Dataset Information**

The dataset contains the following features:

CustomerID: Unique identifier for each customer.

Gender: Categorical feature (0 or 1, representing Male/Female).

Age: Age of the customer.

Annual Income (k$): Customer's yearly income in thousands of dollars.

Spending Score (1-100): A score assigned based on customer spending behavior.

## **🔬 Data Preprocessing**

Handling Outliers: Outliers were removed using the Interquartile Range (IQR) method.

Feature Scaling: Used StandardScaler and RobustScaler to normalize the dataset.

Missing Value Handling: Used SimpleImputer to fill missing values with the mean.

## **🚀 Clustering Approach**

Elbow Method: Used to determine the optimal number of clusters (k). Based on the WCSS plot, k=5 was chosen.

K-Means Clustering: Applied the algorithm to segment customers into 5 clusters.

## **📊 Visualization**

The clusters were visualized using Matplotlib and Seaborn:

Boxplots to check for outliers in Age, Annual Income, and Spending Score.

Scatter plot to visualize the customer clusters based on Income & Spending Score.

## **🛠️ Installation & Requirements**

Make sure you have the following dependencies installed:

pip install pandas numpy matplotlib seaborn scikit-learn

## **📝 Usage**

Run the following Python script to execute the clustering analysis:

python customer_segmentation.py

## **🔍 Key Insights**

Customers are segmented into 5 different groups based on spending behavior and income.

Some clusters contain high-income, high-spending customers, while others consist of low-income, low-spending customers.

The insights can be used for targeted marketing strategies and personalized customer engagement.

## **📌 Future Improvements**

Use Hierarchical Clustering or DBSCAN for alternative segmentation approaches.

Incorporate additional customer features like purchase history for better segmentation.

Deploy as a web app using Flask or Streamlit for business use.

## **📜 License**

This project is open-source and free to use for learning purposes.
