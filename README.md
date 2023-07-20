#Supermarket Customer Segmentation

This repository contains a Python project for supermarket customer segmentation. The goal of this project is to cluster supermarket customers based on their shopping behavior, purchase history, and other features. This can help the supermarket to understand different customer segments and tailor their marketing strategies accordingly.
Data

The data used in this project consists of three main datasets:

    supermarket_purchases: This dataset contains information about customer purchases, including customer ID, product ID, quantity, and price.

    supermarket_prices: This dataset contains information about the prices of different products.

    supermarket_distances: This dataset contains distances between different shops and customers.

The data has been preprocessed and merged into a single DataFrame for further analysis.
Data Preprocessing

The data preprocessing steps include merging the three datasets, calculating the total purchase amount for each customer, and extracting relevant features for clustering.
Feature Extraction

Several features are extracted from the data, including the total purchase amount, average purchase amount, total quantity, average quantity, average price, and distance-related features.
Clustering

The main part of this project is the customer segmentation using the K-Means clustering algorithm. The optimal number of clusters is determined using the Elbow method and silhouette analysis.
Results

The final results include a segmentation of customers into different clusters based on their shopping behavior. The clustering results are visualized using radar charts and other visualizations to gain insights into the characteristics of each customer segment.
How to Run

To run this project, follow these steps:

    Clone the repository to your local machine.

    Download the dataset files from the following links and place them in the same directory as the code:
        supermarket_purchases
        supermarket_prices
        supermarket_distances

    Install the required dependencies by running: pip install -r requirements.txt

    Run the supermarket_segmentation.ipynb Jupyter Notebook to execute the code and perform customer segmentation.

Dependencies

    Python 3.x
    Pandas
    NumPy
    Matplotlib
    Seaborn
    Scikit-learn


