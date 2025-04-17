# 🧠 Customer Segmentation using Clustering

This project uses **unsupervised learning** to segment customers based on **age**, **annual income**, and **spending score** to enable **targeted marketing strategies**.

---

## 📊 Dataset

- 200 customer records  
- Features: `CustomerID`, `Gender`, `Age`, `Annual Income`, `Spending Score`  
- No missing values  

---

## 🎯 Objective

To cluster customers into meaningful groups and provide business insights using:

- **K-Means Clustering**
- **Hierarchical Clustering**
- **Gaussian Mixture Models (GMM)**

---

## 🔍 Clustering Summary

| Cluster | Segment Name                              | Avg Age | Income | Score | Recommendation                             |
|--------:|-------------------------------------------|--------:|--------:|-------:|---------------------------------------------|
| 0       | Senior Middle-income Moderate Spenders    | 56.3    | $54.3k  | 49.1   | Comfort & reliability                       |
| 1       | Young Middle-income Moderate Spenders     | 26.8    | $57.1k  | 48.1   | Value-for-money                             |
| 2       | Affluent Conservative Spenders            | 41.9    | $88.9k  | 17.0   | Quality & durability                        |
| 3       | Affluent Big Spenders                     | 32.7    | $86.5k  | 82.1   | Luxury & premium products                   |
| 4       | Budget-conscious Big Spenders             | 25.0    | $25.3k  | 77.6   | Affordable luxury & deals                   |
| 5       | Budget-conscious Conservative Spenders    | 45.5    | $26.3k  | 19.4   | Essentials & price-sensitive offerings      |

---

## 🛠 Tech Stack

- Python, Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn, SciPy  

---

## 🚀 How to Run

```bash
git clone https://github.com/yourusername/customer-segmentation.git
cd customer-segmentation
pip install -r requirements.txt
