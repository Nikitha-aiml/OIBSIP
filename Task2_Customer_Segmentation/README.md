# 👥 Customer Segmentation using K-Means Clustering

> **Oasis Infobyte Data Analytics Internship – Level 1 | Task 2**

## 📖 Project Overview

Customer segmentation is the process of dividing customers into groups based on similar characteristics and purchasing behavior. In this project, the **K-Means Clustering** algorithm was used to identify distinct customer segments from mall customer data.

The resulting clusters help businesses better understand their customers and create targeted marketing strategies.

---

## 🎯 Objective

The objective of this project is to segment customers into different groups based on their **Annual Income** and **Spending Score** using the K-Means clustering algorithm.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## 📂 Dataset

**Dataset Name:** Mall Customer Segmentation Dataset

The dataset contains customer information including:

- Customer ID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1–100)

---

## 🔍 Project Workflow

### 1. Data Loading
- Imported the dataset using Pandas
- Displayed the first few records

### 2. Data Exploration
- Checked dataset shape
- Verified data types
- Examined summary statistics
- Checked for missing values

### 3. Feature Selection
The following features were selected for clustering:

- Annual Income (k$)
- Spending Score (1–100)

### 4. Finding the Optimal Number of Clusters

The **Elbow Method** was used to determine the optimal number of clusters for the K-Means algorithm.

### 5. Model Building

Applied the **K-Means Clustering** algorithm to group customers based on similar spending behavior.

### 6. Cluster Visualization

Visualized the customer segments using a scatter plot with different colors representing each cluster.

---

## 📊 Results

The customers were successfully divided into meaningful clusters based on their income and spending behavior.

These clusters can help businesses:

- Identify high-value customers
- Develop targeted marketing campaigns
- Improve customer retention
- Understand purchasing patterns

---

## 📁 Project Structure

```
Task2_Customer_Segmentation/
│
├── Customer_Segmentation.ipynb
├── Mall_Customers.csv
├── README.md
└── screenshots/
    ├── dataset_preview.png
    ├── dataset_info.png
    ├── missing_values.png
    ├── elbow_method.png
    └── customer_segments.png
```

---

## 📸 Project Screenshots

The `screenshots` folder contains:

- Dataset Preview
- Dataset Information
- Missing Value Check
- Elbow Method Graph
- Final Customer Segmentation Visualization

---

## 📈 Key Outcomes

- Successfully explored and understood the dataset.
- Selected appropriate features for clustering.
- Determined the optimal number of clusters using the Elbow Method.
- Applied K-Means clustering.
- Visualized customer groups for business insights.

---

## 🎓 Learning Outcomes

Through this project, I gained practical experience in:

- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Selection
- Unsupervised Machine Learning
- K-Means Clustering
- Elbow Method
- Cluster Visualization
- Business Data Interpretation

---

## 🚀 Future Scope

The customer segmentation model can be extended by:

- Including additional customer features
- Using Hierarchical Clustering or DBSCAN
- Applying Principal Component Analysis (PCA)
- Building personalized recommendation systems

---

## 👩‍💻 Author

**Nikitha Ashok**

B.Sc. Computer Science (Artificial Intelligence & Machine Learning)

Data Analytics Intern – Oasis Infobyte

GitHub: https://github.com/Nikitha-aiml
