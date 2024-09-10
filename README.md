# Customer Purchase Behavior Analysis

This project aims to analyze customer purchasing behavior using a dataset of online retail transactions. By preprocessing the data and performing customer segmentation, the goal is to identify patterns and provide actionable insights for better understanding customer behavior.

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Project Workflow](#project-workflow)
- [Key Features](#key-features)
- [Results](#results)
- [Future Enhancements](#future-enhancements)

## Overview

The **Customer Purchase Behavior Analysis** project analyzes an online retail dataset to:
- Clean and preprocess raw data.
- Perform exploratory data analysis (EDA).
- Engineer new features such as Recency, Frequency, and Monetary (RFM) metrics.
- Apply clustering algorithms (K-means) to segment customers.
- Provide insights into customer segments that can be used for targeted marketing strategies.

## Dataset

The dataset used in this project is the **Online Retail Dataset** from the UCI Machine Learning Repository. The dataset contains transactions from a UK-based online retailer from December 2010 to December 2011.

- Dataset URL: [Online Retail Dataset - UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Online+Retail)

### Key Columns:
- `InvoiceNo`: Invoice number, uniquely assigned to each transaction.
- `StockCode`: Unique product code.
- `Description`: Description of the product.
- `Quantity`: Quantity of each product per transaction.
- `InvoiceDate`: Date of the transaction.
- `UnitPrice`: Price per unit of product.
- `CustomerID`: Unique identifier for each customer.
- `Country`: Country where the customer resides.

## Installation

### Prerequisites

To run this project, ensure you have the following installed:
- Python 3.x
- Jupyter Notebook
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `datetime`

### Install Dependencies

You can install the necessary libraries using pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### Running the Project

1. Clone this repository:

   ```bash
   git clone https://github.com/Mahdiyeh-Asgharpour/Customer-Purchase-Behavior-Analysis
   ```

2. Navigate to the project directory:

   ```bash
   cd customer-purchase-behavior-analysis
   ```

3. Open the Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

4. Open the notebook `CPBA.ipynb` and run the cells step by step.

## Project Workflow

1. **Data Collection**: 
   - Load the dataset from a public source (UCI or Kaggle).
2. **Data Preprocessing**: 
   - Handle missing values and duplicates.
   - Convert data types.
   - Perform Exploratory Data Analysis (EDA).
3. **Feature Engineering**: 
   - Calculate RFM (Recency, Frequency, Monetary) metrics.
   - Analyze customer behavior using these features.
4. **Customer Segmentation**:
   - Apply the K-means clustering algorithm to group customers into segments.
   - Visualize the clusters and analyze the characteristics of each segment.
5. **Insights & Reporting**:
   - Summarize the insights and recommendations based on customer segmentation.

## Key Features

- **Data Cleaning**: Handles missing values and removes duplicates.
- **Feature Engineering**: Generates RFM features to evaluate customer value.
- **Clustering Analysis**: Uses K-means to segment customers based on purchasing behavior.
- **Visualization**: Provides visualizations such as pairplots and cluster diagrams to help understand the data.

## Results

The project segments customers into distinct groups based on their purchasing behavior. The results can help businesses identify:
- **High-value customers**: Customers who purchase frequently and spend a lot.
- **Potential churners**: Customers who haven't made a purchase recently.
- **Segment-wise marketing strategies**: Targeted approaches for different customer segments.

## Future Enhancements

- Use additional machine learning models for customer segmentation (e.g., DBSCAN, Hierarchical Clustering).
- Add predictive models to forecast customer lifetime value (CLV).
- Perform more in-depth analysis on product-specific trends.