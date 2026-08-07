# 👥 Customer Segmentation using RFM Analysis and K-Means Clustering

## 📌 Project Overview

Customer segmentation is a data-driven approach used to group customers based on their purchasing behavior. In this project, customers are segmented using **RFM (Recency, Frequency, Monetary) Analysis** and **K-Means Clustering** to identify meaningful customer groups for targeted marketing strategies.

---

## 🎯 Objective

- Analyze customer purchasing behavior.
- Create RFM features (Recency, Frequency, Monetary).
- Standardize the dataset for clustering.
- Determine the optimal number of clusters using the Elbow Method.
- Apply K-Means Clustering.
- Visualize customer segments and interpret the results.

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📂 Dataset

**Dataset:** `Mall_Customers_Data.csv`

The dataset contains customer information such as:

- Customer ID
- Purchase Date
- Product Category
- Quantity Purchased
- Total Purchase Amount
- Payment Method
- Customer Age
- Gender
- Churn Status

---

## 📁 Project Structure

```
Task2_Customer_Segmentation/
│
├── OIBSIP_Task2_Customer_Segmentation.ipynb
├── Mall_Customers_Data.csv
├── README.md
└── Screenshots/
    ├── elbow_method.png
    ├── cluster_visualization.png
    ├── pairplot.png
    └── ...
```

---

## 📊 Workflow

### Data Preprocessing
- Imported dataset
- Checked missing values
- Removed duplicate records
- Converted Purchase Date to datetime format

### Feature Engineering
Created RFM features:

- **Recency:** Days since the customer's last purchase
- **Frequency:** Number of purchases made
- **Monetary:** Total spending by each customer

### Feature Scaling
- Standardized RFM values using StandardScaler

### K-Means Clustering
- Determined optimal clusters using the Elbow Method
- Applied K-Means algorithm
- Assigned customers to clusters

### Data Visualization
- Elbow Method Plot
- Customer Cluster Scatter Plot
- Pairwise Relationship Plots

---

## 📈 Key Insights

- Customers were successfully grouped based on purchasing behavior.
- High-value customers were identified through high frequency and monetary values.
- Some customer groups showed low engagement and could benefit from promotional campaigns.
- Customer segmentation enables businesses to design personalized marketing strategies.

---

## 📌 Conclusion

RFM Analysis combined with K-Means Clustering effectively segments customers into meaningful groups. These insights help businesses improve customer retention, optimize marketing campaigns, and enhance customer relationship management.

---

## 📷 Screenshots

Project visualizations are available in the **Screenshots** folder.

Examples include:

- Elbow Method
- Customer Segments
- Pair Plot
- Cluster Distribution

---

## 🚀 How to Run

Clone the repository

```bash
git clone https://github.com/Nikitha-aiml/OIBSIP.git
```

Navigate to the project folder

```bash
cd Task2_Customer_Segmentation
```

Install dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

Launch Jupyter Notebook

```bash
jupyter notebook OIBSIP_Task2_Customer_Segmentation.ipynb
```

---

## 👩‍💻 Author

**Nikitha.S**

Data Analytics Intern — Oasis Infobyte
