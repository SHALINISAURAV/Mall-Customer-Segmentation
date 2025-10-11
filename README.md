# 🛍️ Mall Customer Segmentation using Unsupervised Learning

### 🎯 Objective
Segment customers of a mall based on their **spending behavior and income** to help businesses understand their target audience and improve marketing strategies.

---

## 📊 Dataset
**Mall Customer Segmentation Dataset**

| Column | Description |
|:-------|:-------------|
| CustomerID | Unique ID |
| Gender | Male/Female |
| Age | Age of the customer |
| Annual Income (k$) | Income level |
| Spending Score (1–100) | Spending pattern (given by mall) |

---

## 🧠 Algorithms Used
- **K-Means Clustering** → for fixed, pre-defined `k`
- **Hierarchical Clustering** → for tree-based visualization (dendrogram)
- **DBSCAN** → for density-based outlier detection

---

## ⚙️ Steps Implemented
1. Data Cleaning & Preprocessing  
2. Exploratory Data Analysis (EDA)  
3. Feature Scaling  
4. K-Means Clustering (Elbow & Silhouette Methods)  
5. Hierarchical Clustering (Ward Linkage & Dendrogram)  
6. DBSCAN Clustering  
7. Cluster Profiling  
8. Visualizations & Insights  

---

## 🖼️ Visualizations
| K-Means | Hierarchical | DBSCAN |
|:--------:|:-------------:|:------:|
| ![KMeans](plots/kmeans_clusters.png) | ![Hierarchical](plots/hierarchical_dendrogram.png) | ![DBSCAN](plots/dbscan_clusters.png) |

---

## 🧩 Technologies Used
- Python 🐍  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn, Scipy  

---

## 🪄 Results & Insights
- Identified **3 main customer segments**:
  - 🎯 **High Income, High Spend** → Premium Target  
  - 💸 **Medium Income, Medium Spend** → Potential Growth Group  
  - 💤 **Low Income, Low Spend** → Low Engagement  

---

## 🚀 How to Run
```bash
git clone https://github.com/<yourusername>/mall-customer-segmentation.git
cd mall-customer-segmentation
pip install -r requirements.txt
jupyter notebook notebooks/Mall_Customer_Segmentation.ipynb

🧩 Requirements
pandas
numpy
matplotlib
seaborn
scikit-learn
scipy

💡 Future Improvements
Add PCA for dimensionality reduction
Build a dashboard (Streamlit / PowerBI)
Try Gaussian Mixture Models (GMM)

✨ Author

👩‍💻 Shalini Saurav 
📧 Email
 • 🌐 LinkedIn
 • 🐙 GitHub

🧼 4️⃣ .gitignore
__pycache__/
.ipynb_checkpoints/
*.csv
*.png
.env

![Banner](https://github.com/yourusername/mall-customer-segmentation/blob/main/plots/banner.png)
