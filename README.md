# Customer Segmentation using K-Means Clustering

## Overview
This project applies K-Means Clustering to segment mall customers based on customer behavior and purchasing patterns.  
The analysis helps identify different customer groups using features such as:
- Age
- Annual Income
- Spending Score

The project includes:
- Data preprocessing
- Exploratory Data Analysis (EDA)
- Customer segmentation using machine learning
- 2D and 3D visualizations


## Objective
The goal of this project is to group customers into meaningful segments that can help businesses:
- understand customer behavior
- improve targeted marketing
- identify high-value customers
- optimize promotional strategies


## Dataset
The dataset used is the Mall Customers Dataset.


### Features
Column	               Description
CustomerID	           Unique customer identifier
Gender	               Customer gender
Age	                   Customer age
Annual Income (k$)     Annual income in thousand dollars
Spending Score (1-100) Spending behavior score
---


## Technologies Used
- Python
- Jupyter Notebook
- pandas
- NumPy
- matplotlib
- seaborn
- Plotly
- scikit-learn


## Machine Learning Technique
### K-Means Clustering
K-Means clustering is an unsupervised machine learning algorithm used to group similar data points into clusters.

The model was trained using:
- Age
- Annual Income
- Spending Score


## Project Workflow
1. Data Loading
2. Data Cleaning and Exploration
3. Statistical Analysis
4. Data Visualization
5. Feature Selection
6. Data Scaling
7. K-Means Model Training
8. Cluster Prediction
9. 3D Cluster Visualization


## Visualizations Included
- Scatter plots
- Correlation heatmap
- 3D interactive cluster visualization
- Cluster distribution analysis


## Key Insights
- High-income customers do not always have high spending scores.
- Distinct customer groups can be identified based on purchasing behavior.
- Some customer segments represent potential premium customers for targeted marketing.


## How to Run the Project
1. Clone the Repository
git clone https://github.com/dhanvi28/customer-segmentation.git

2. Navigate to the Project Folder
cd customer-segmentation

3. Install Required Libraries
pip install -r requirements.txt

4. Launch Jupyter Notebook
jupyter notebook

5. Open the Notebook
Open:
segmentation.ipynb

6. Run the Cells
Run all notebook cells sequentially to:
preprocess the dataset
train the K-Means clustering model
visualize customer segments

## Project Structure
customer-segmentation/
│
├── Mall_Customers.csv
├── segmentation.ipynb
├── requirements.txt
└── README.md


## Future Improvements

- Streamlit dashboard deployment
- Dynamic cluster selection
- Real-time customer prediction
- Advanced clustering comparison
- Customer recommendation system


## Author
**Dhanvi**
