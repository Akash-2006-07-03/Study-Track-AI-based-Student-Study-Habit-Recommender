Milestone 2 – Behavior Clustering & Pattern Detection

🎯 Objective
Perform clustering on student behavioral data to identify groups of students with similar study habits and academic performance.

---

🧩 Dataset Source
- Dataset: `student-mat.csv`
- Source: UCI Machine Learning Repository – Student Performance Data
- This dataset contains attributes such as study time, absences, and grades (G1, G2, G3).

---

⚙️ Steps Performed
1. Imported and cleaned the dataset.  
2. Selected relevant numeric features: `studytime`, `absences`, and `G3`.  
3. Standardized features using **StandardScaler**.  
4. Applied **PCA** for dimensionality reduction and visualization.  
5. Used **K-Means Clustering** to group students into 3 clusters.  
6. Evaluated the model using **Elbow Method** and **Silhouette Score**.  
7. Visualized the clusters and analyzed behavioral patterns.

---

🛠️ Tools & Libraries Used
- Python (pandas, numpy, scikit-learn, matplotlib, seaborn)

---

📊 Key Insights
✅ Students with **higher study time** generally achieve **better grades**.  
✅ Students with **more absences** often fall into **lower performance clusters**.  
✅ The dataset reveals **three clear behavioral groups** — high performers, average students, and low performers.  
✅ Final grade (`G3`) is the strongest differentiator between clusters.
