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
| **K-Means Clustering** | **Hierarchical Clustering** | **DBSCAN Clustering** |
|:----------------------:|:---------------------------:|:---------------------:|
| <img src="https://github.com/user-attachments/assets/80a68c4e-3cbb-4232-94a5-7cfb69f506db" width="300"/> | <img width="1980" height="1499" alt="hierarchical_dendrogram" src="https://github.com/user-attachments/assets/86677306-7b73-414a-a614-e630e02f23b1" />
 | <img src="plots/dbscan_clusters.png" width="300"/> |

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
git clone https://github.com/<SHALINSAURAV>/mall-customer-segmentation.git
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

![Banner](https://github.com/SHALINISAURAV/mall-customer-segmentation/blob/main/plots/banner.png)
