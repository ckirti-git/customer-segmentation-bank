# 🏦 Customer Segmentation for a Bank  

## 📌 Project Overview  
Customer segmentation is a crucial task for banks to tailor their marketing strategies and improve customer service. This project employs **K-Means Clustering** and **DBSCAN Clustering** to analyze bank customers based on their demographics and financial behavior. By identifying distinct customer groups, banks can personalize their offerings and optimize engagement.  

We explore different clustering techniques and dimensionality reduction methods to extract meaningful patterns from the data. The project also includes insightful visualizations and **interactive dashboards** to interpret the results effectively.  

---

## 🚀 Key Features  
✔ **Customer Clustering** – Using unsupervised learning to segment customers based on their financial attributes  
✔ **K-Means Clustering** – Implemented and visualized for pattern recognition  
✔ **DBSCAN Clustering** – Planned for exploring density-based clustering  
✔ **Dimensionality Reduction** – **PCA** to reduce feature complexity  
✔ **Interactive Dashboards** – **Pre-Clustering Dashboard Created**, **Post-Clustering Dashboard Planned**  
✔ **Data Visualization** – Using **Matplotlib** & **Seaborn** for exploratory analysis  

---

## 📊 Customer Segmentation Dashboard (Before Clustering)  

Before applying clustering techniques, a **dashboard was created** to analyze customer demographics, job roles, loan status, and campaign effectiveness.  

### **Dashboard Insights**  
🔹 **Most customers have secondary education**, followed by tertiary and primary education.  
🔹 **39% of customers are in their 30s**, while 24% are in their 40s.  
🔹 **57% of customers are married**, 32% are single, and 12% are divorced.  
🔹 The highest number of customers are **managers, technicians, and blue-collar workers**.  
🔹 **Campaign effectiveness is low**, as most customers did not subscribe to the deposit scheme.  

📌 **Interactive Dashboard:**  
Click on -> [Customer Segmentation Dashboard](https://public.tableau.com/views/BankCustomerSegmentationProject/BanksCustomerSegmentationDashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)  

📌 **Next Steps:**  
✅ **Create a post-clustering dashboard** to visualize customer segments after applying **K-Means & DBSCAN**.  

---

## 🛠 Techniques Used  
🔹 **K-Means Clustering** – Finds customer segments based on predefined clusters  
🔹 **DBSCAN Clustering** – Will explore non-linear patterns in customer data  
🔹 **Principal Component Analysis (PCA)** – Reducing dimensionality for better visualization  
🔹 **Visualization Tools** – Seaborn, Matplotlib, and Power BI (planned)  

---

## 📂 Dataset  
- **Source:** [Bank Marketing Dataset (Kaggle)](https://www.kaggle.com/datasets/janiobachmann/bank-marketing-dataset)  
- **Features:** Age, Income, Loan Status, Credit Score, Balance, and more  

### 📊 Clustered Dataset with Pivot Table  

You can also see the clustered dataset with a pivot table by clicking on the link below:  

[View Dataset](https://docs.google.com/spreadsheets/d/1Z0LudCOb6FSKdBv-UeVnsxKGgsLk-dIW/edit?usp=sharing&ouid=102919673180469139167&rtpof=true&sd=true)  

---

## 📊 Current Progress  
✅ **K-Means Clustering Implementation** (Completed)  
✅ **Pre-Clustering Dashboard** *(Uploaded: `Customer_Segmentation_Dashboard.png`)*  
✅ **Cluster Visualization:** *Uploaded* `Cluster_visualization_age_balance(KMeans).png`  
✅ **Elbow Method Graph:** *Uploaded* `elbow_method_graph.png`  

📌 **Next Steps:**  
⬜ Implement **DBSCAN Clustering**  
⬜ Apply **PCA** for feature reduction  
⬜ **Build a post-clustering Power BI/Tableau Dashboard**  
⬜ Compare results from different clustering techniques  

---

## 📁 Repository Structure  

📂 Customer Segmentation  
│── 📜 README.md                # Project Documentation  
│── 📊 Customer_Segmentation.ipynb  # Jupyter Notebook Implementation  
│── 🖼 Bank_Customer_Segmentation_Dashboard.png  # Dashboard (Before Clustering)  
│── 🖼 elbow_method_graph.png    # Elbow Method for optimal K selection  
│── 🖼 Cluster_visualization_age_balance(KMeans).png # Clustering Results  
│── 💻 customer_segmentation.py  # Python Script for Clustering  

---

## 🎯 Future Enhancements  
✨ Implement **Hierarchical Clustering** for better comparison  
✨ Integrate **Tableau/Power BI Dashboards** (Pre & Post Clustering)  
✨ Deploy a **Customer Segmentation Web App**  

Stay tuned for more updates! 🚀📈  
