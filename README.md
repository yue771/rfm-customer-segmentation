# rfm-customer-segmentation
# 📊 Customer Segmentation using RFM & KMeans

## 📌 Project Overview
This project performs customer segmentation based on purchasing behavior using **RFM analysis (Recency, Frequency, Monetary)** and **KMeans clustering**.

The goal is to identify different customer groups and provide actionable insights for improving marketing strategies and customer retention.

---

## 📂 Dataset
The dataset contains transactional data with:
- Customer ID  
- Purchase date  
- Transaction amount  

These features are used to construct RFM metrics.

---

## 🧠 Methodology

### 1. Data Cleaning
- Removed missing values  
- Filtered invalid transactions  
- Converted data types  

### 2. Feature Engineering (RFM)
- **Recency:** Days since last purchase  
- **Frequency:** Number of purchases  
- **Monetary:** Total spending  

### 3. Feature Scaling
- Standardized RFM features using scaling techniques  

### 4. Clustering
- Applied **KMeans clustering**  
- Segmented customers into 4 groups  

### 5. Labeling
Assigned meaningful business labels:
- VIP Customers  
- High Value Customers  
- Regular Customers  
- Lost Customers  

---

## 📊 Results

The clustering results show clear behavioral differences:

| Segment | Characteristics |
|--------|----------------|
| VIP Customers | High frequency, highest spending, very recent activity |
| High Value Customers | High spending and engagement |
| Regular Customers | Moderate activity, largest group |
| Lost Customers | Low activity, long time since last purchase |

---

## 🔍 Key Findings

- Regular Customers form the largest segment, indicating a stable customer base  
- Lost Customers represent churn risk and require reactivation strategies  
- VIP Customers contribute disproportionately high revenue  
- Customer segmentation enables targeted and efficient marketing strategies  

---

## 💡 Business Recommendations

- 🎯 Retain VIP customers with loyalty programs  
- 🔁 Reactivate lost customers through promotions  
- 📈 Upsell regular customers to increase value  
- 🧠 Use segmentation for personalized marketing  

---

## 🛠️ Tech Stack

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Seaborn  

---

## 📈 Project Highlights

- End-to-end data analysis workflow  
- Feature engineering with RFM model  
- Unsupervised learning using KMeans  
- Business-oriented insights generation  

---

## 📁 Project Structure
