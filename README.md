
---

# Customer Segmentation Using K-Means Algorithm Python Project

## Overview

This project focuses on customer segmentation using the Mall Customers dataset. The goal is to understand customer behavior through exploratory data analysis (EDA) and unsupervised learning techniques like K-Means clustering.

## Dataset

The dataset used in this project is the `Mall_Customers.csv`, which contains the following columns:
- **CustomerID**: Unique ID assigned to each customer.
- **Gen**: Gender of the customer.
- **Age**: Age of the customer.
- **Annual Income (k$)**: Annual income of the customer in thousand dollars.
- **Spending Score (1-100)**: A score assigned to customers based on their behavior and spending nature.

## Prerequisites

The following Python libraries are required to run this project:
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`
  
You can install these dependencies using pip:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

## Exploratory Data Analysis (EDA)

1. **Loading the Data:**
    - The dataset is loaded using `pandas` and the first few rows are displayed to understand its structure.
    - Columns are renamed as necessary for ease of use.

2. **Data Inspection:**
    - `df.shape` shows the number of rows and columns.
    - `df.describe()` provides summary statistics for numerical columns.
    - `df.dtypes` reveals the data types of each column.
    - `df.isnull().sum()` checks for missing values.
    - The `CustomerID` column is dropped as it is not needed for analysis.

3. **Visualizations:**
    - **Distribution Plots:** Visualizing the distribution of Age, Annual Income, and Spending Score.
    - **Count Plot:** Visualizing the count of customers by gender.
    - **Violin Plots:** Showing the distribution of Age, Annual Income, and Spending Score with respect to Gender.
    - **Bar Plots:** Analyzing customer distribution by age groups, spending scores, and annual income brackets.

## Clustering with K-Means

### 1. **K-Means with Age and Spending Score:**
    - **Objective:** Group customers based on their age and spending score.
    - **Elbow Method:** The Within-Cluster Sum of Squares (WCSS) is plotted to determine the optimal number of clusters (k).
    - **Visualization:** Scatter plot showing the clusters along with cluster centroids.

### 2. **K-Means with Annual Income and Spending Score:**
    - **Objective:** Segment customers based on their annual income and spending score.
    - **Elbow Method:** WCSS is used again to determine the optimal k.
    - **Visualization:** Scatter plot showing customer clusters.

### 3. **K-Means with All Features:**
    - **Objective:** Use all features (Age, Annual Income, Spending Score) for clustering.
    - **3D Visualization:** A 3D scatter plot is used to visualize the clusters in three dimensions.

## Results

The K-Means clustering algorithm successfully segmented customers into different groups based on the features provided. The visualizations help in understanding the distinct characteristics of each cluster.

## Conclusion

This project demonstrates the power of K-Means clustering in identifying distinct customer segments based on their demographics and spending behavior. This segmentation can be valuable for targeted marketing strategies.

## Files

- `Mall_Customers.csv`: The dataset used for analysis.
- `customer_segmentation.ipynb`: The Jupyter notebook containing all the code.
- `README.md`: Project documentation.

## How to Run

1. Clone the repository.
2. Ensure all dependencies are installed.
3. Run the Jupyter notebook to see the analysis and visualizations.

---
---
---
### Some Basic Prerequisites Knowladge as_ . 
![image](https://github.com/user-attachments/assets/539157ce-7ee3-442a-a492-f67fc493d209)
![image](https://github.com/user-attachments/assets/1bc7ddcf-4272-4844-a46b-9014398daa6d)
![image](https://github.com/user-attachments/assets/61a0470b-7c97-48c6-8ce1-ffe8e22839cf)
![image](https://github.com/user-attachments/assets/25aef425-eda7-447c-89a6-cad6c4bf1469)
![image](https://github.com/user-attachments/assets/b1ae73ca-a59c-461a-b3bc-f93faeca7ed1)
![image](https://github.com/user-attachments/assets/0bbe4e82-6f83-4597-adaf-0aa548b55ea3)
![image](https://github.com/user-attachments/assets/d76645fd-4651-4f8e-95be-139f5076e598)
![image](https://github.com/user-attachments/assets/d3a05a3d-f4ad-451b-b786-2b489d5e3036)
![image](https://github.com/user-attachments/assets/c71e12dc-755a-4e54-bb25-13ceffc2eaae)
![image](https://github.com/user-attachments/assets/73a630c3-226c-433c-91dd-da72dd170186)

## Contact Us Here :->

For any questions or feedback, Please reach out to [https://insightsalpha.github.io/Portfolio/] Contact Us Section.
---


