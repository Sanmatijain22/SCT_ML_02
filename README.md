# SCT_ML_02
This project uses K-Means clustering to segment retail store customers based on their annual income and spending score. It helps identify distinct customer groups for targeted marketing strategies, improving customer engagement and sales. The model visualizes clusters to better understand purchasing behavior and optimize business decisions.
🛍️ Customer Segmentation Using K-Means Clustering
📌 Project Overview
This project implements K-Means clustering to segment customers of a retail store based on their Annual Income and Spending Score. The dataset includes demographic and purchase behavior data such as Customer ID, Gender, Age, Income, and Spending Score. The goal is to identify distinct customer groups to support targeted marketing, personalized services, and strategic business decisions.

🔍 Objectives
Group customers into clusters based on purchasing behavior.

Understand which customers are high-value, low-value, or price-sensitive.

Use insights to tailor marketing campaigns for each segment.

Improve customer satisfaction and increase business revenue.

🧠 Techniques Used
Label Encoding for categorical features (Gender).

K-Means Clustering for unsupervised customer segmentation.

Elbow Method to determine the optimal number of clusters.

Matplotlib and Seaborn for insightful visualizations.

📊 Features Used for Clustering
Annual Income (k$)

Spending Score (1-100)

These features help differentiate customers who spend more or less despite similar incomes.

📈 Results & Insights
The model groups customers into distinct clusters such as:

High Income, High Spending

Low Income, High Spending

High Income, Low Spending

Average Spenders

Low Income, Low Spending

These clusters enable businesses to focus marketing efforts more efficiently and improve customer retention.

🛠️ Tech Stack
Python

Pandas

Matplotlib

Seaborn

Scikit-learn (KMeans)

📁 Dataset
The dataset contains 200 records with the following fields:

CustomerID

Gender

Age

Annual Income (k$)

Spending Score (1–100)

📌 How to Run
Upload the dataset (Mall_Customers.csv) in Google Colab.

Run the notebook to preprocess data and apply K-Means.

Visualize customer segments using 2D scatter plots.

Analyze and interpret each cluster for marketing actions.

