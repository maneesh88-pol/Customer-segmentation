# Customer Segmentation Using K-Means Clustering

## Project Overview
This project uses **RFM Analysis** and **K-Means Clustering** to segment e-commerce customers based on their purchasing behavior.

## Objectives
- Understand customer purchasing patterns using Recency, Frequency, and Monetary (RFM) values.
- Segment customers into meaningful groups for targeted marketing.

## Steps:
1. **Data Collection**:  
   A sample e-commerce dataset with the following columns:  
   - InvoiceNo  
   - CustomerID  
   - InvoiceDate  
   - Amount  
   - Country  

2. **Data Preprocessing**:
   - Handling missing values.
   - Aggregating data to calculate RFM metrics.

3. **Exploratory Data Analysis**:
   - Analyzing spending, frequency, and recency distributions.

4. **Customer Segmentation**:
   - Using K-Means clustering to group customers into 3 segments.

5. **Visualization**:
   - Scatter plot for Frequency vs. Monetary to visualize clusters.

## Results
The customers were segmented into 3 clusters:
- **Cluster 0**: Moderate spending and occasional purchases.
- **Cluster 1**: High-value customers with frequent and recent purchases.
- **Cluster 2**: Customers with low spending and long recency.

## Files Included:
- `customer_segments_with_clusters.csv`: Final RFM table with cluster labels.
- `customer_segmentation.ipynb`: Jupyter notebook with the full analysis.

## Tools Used:
- **Python**: Pandas, Matplotlib, Seaborn, Scikit-learn
- **Google Colab**: For code execution

## Visualizations:
![Scatter Plot](Add Link to Your Screenshot Here)

## Conclusion:
This project demonstrates customer segmentation using machine learning and provides insights for personalized marketing strategies.

---
