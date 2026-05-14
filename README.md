# Lab-11
# Credit Card Customer Segmentation using K-Means

**Student Name:** Jadi Fahad  
**Student ID:** 2240004698  

## Dataset
Dataset used: **CC_GENERAL.csv**

This dataset contains credit card customer information such as balance, purchases, cash advance, credit limit, and payment behavior.

## Lab Summary
In this lab, I applied the K-Means clustering algorithm to segment credit card customers based on their spending behavior.

### Tasks Completed:
- Imported and explored the dataset
- Removed unnecessary column (`CUST_ID`)
- Identified missing values in `CREDIT_LIMIT` and `MINIMUM_PAYMENTS`
- Handled missing values using mean imputation
- Scaled the dataset using StandardScaler
- Applied the Elbow Method to determine the optimal number of clusters
- Used Silhouette Score for evaluation
- Built the final K-Means model with **K = 4**
- Analyzed customer segments
- Visualized clusters using PCA

## Results
The model grouped customers into four segments:
- Moderate spending customers
- High-value customers
- Cash advance users
- Low spending customers

This segmentation helps companies create personalized marketing strategies for different customer groups.
