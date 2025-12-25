# 🧠 Analyze and Predict Potential Customers Based on Customer Clustering

Customer segmentation plays a vital role in designing effective marketing strategies to drive business growth and maximize revenue. This project presents a full machine learning pipeline combining **dimensionality reduction**, **unsupervised clustering**, and **supervised classification** to understand customer behavior and predict potential high-value customers.

## 📌 Abstract

We propose a comprehensive approach that leverages **Principal Component Analysis (PCA)** and **Autoencoders** to extract meaningful features from customer data, reducing complexity while preserving essential information. To enhance clustering accuracy, **DBSCAN** is used to detect and eliminate noise before applying the **K-Means algorithm** for customer segmentation.

After identifying distinct customer segments, we perform a focused analysis on **loyal customers** to detect those with the **potential to be upgraded to VIP status** based on behavioral similarity. In parallel, we build a **Random Forest Classifier** to predict **new potential customers** using basic demographic and behavioral attributes. These insights enable proactive marketing, personalized promotions, and better customer lifetime value (CLV) forecasting.

---

## 📊 Project Highlights

| Step | Technique | Purpose |
|------|-----------|---------|
| 1️⃣ | PCA & Autoencoder | Dimensionality reduction |
| 2️⃣ | DBSCAN | Noise/outlier detection |
| 3️⃣ | K-Means Clustering | Segment customers into behavior groups |
| 4️⃣ | Cluster Profiling | Understand and label customer types (e.g., VIP, Loyal, Budget) |
| 5️⃣ | VIP Upgrade Analysis | Find loyal customers with potential to become VIP |
| 6️⃣ | Random Forest | Predict new potential customers for acquisition campaigns |

---

## 📈 Results

- Reduced dimensionality while preserving customer behavior patterns
- Removed noise (≈8%) via DBSCAN, improving cluster clarity
- Identified 3 customer clusters, including:
  - **VIPs** – High spending & frequency
  - **Loyal customers** – Moderate spending, high consistency
  - **Normally** – Low spending, infrequent visits
- Discovered a subset of loyal customers with VIP-like profiles
- Built classifier to predict **new high-potential customers**
  
---

## 💡 Business Value

✅ Gain deep insights into diverse customer segments

✅ Identify loyal customers with potential to become VIPs

✅ Predict emerging high-value customer prospects early

✅ Optimize retention and acquisition strategies effectively

🎯 Enhance marketing efficiency, reduce costs, and drive long-term revenue growth

---

## 📚 Technologies Used

- Python (Pandas, Scikit-learn, TensorFlow/Keras)
- PCA, Autoencoder
- DBSCAN, KMeans
- Random Forest
- Matplotlib, Seaborn

---

## 🔗 Demo & Publication

- 📄 ICCSA 2025 Conference Paper: Analyze and Predict Potential Customers based on Customer Clustering
- 🧾 DOI / Citation: https://doi.org/10.1007/978-3-031-97596-7_5

---

## 👤 Author
Ta Cong Binh, Ngo Chi Trung, Hoang Anh Tu & Phan Duy Hung(corresponding author)  
