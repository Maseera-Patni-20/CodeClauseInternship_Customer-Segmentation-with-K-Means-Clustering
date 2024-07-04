# Customer Segmentation with K-Means Clustering

This project focuses on segmenting customers into distinct groups using the K-Means clustering algorithm. By analyzing customer data, including age, annual income, and spending score, the project aims to enhance targeted marketing strategies and improve customer relationship management.

## Features

- **Data Preprocessing**: Convert categorical data to numeric and calculate the correlation matrix.
- **Visualization**: Generate distribution plots for annual income, age, spending score, and gender distribution.
- **Clustering Analysis**: Identify optimal number of clusters using the Elbow method.
- **K-Means Clustering**: Apply K-Means clustering to segment customers.
- **3D Visualization**: Create 3D plots to visualize clusters.

## Technologies Used

- **Python**: Programming language for data analysis and clustering.
- **Pandas**: Data manipulation and analysis.
- **Matplotlib** and **Seaborn**: Data visualization.
- **Scikit-learn**: Machine learning library for K-Means clustering.

## Project Workflow

1. **Data Loading**:
    - Load and inspect the customer data.

2. **Data Preprocessing**:
    - Convert categorical 'Gender' to numeric values.
    - Calculate the correlation matrix for numeric data.

3. **Data Visualization**:
    - Plot distributions for annual income, age, and spending score.
    - Visualize gender distribution.

4. **Clustering Analysis**:
    - Use the Elbow method to find the optimal number of clusters.
    - Apply K-Means clustering to segment customers.

5. **Cluster Visualization**:
    - Create a 3D plot to visualize the clusters based on age, annual income, and spending score.
    - Print the number of customers in each cluster and their respective customer IDs.

## Evaluation Metric

- **WCSS** (Within-Cluster Sum of Squares): Used to determine the optimal number of clusters.

## Results

- Successfully segmented customers into distinct groups.
- Enhanced understanding of customer behavior for targeted marketing.

## Conclusion

Customer segmentation using K-Means clustering provides valuable insights into customer behavior, enabling businesses to tailor marketing strategies and improve customer relationship management.

## Future Work

- Further tuning of cluster parameters.
- Exploration of additional clustering algorithms.
- Integration with real-time data for dynamic segmentation.

