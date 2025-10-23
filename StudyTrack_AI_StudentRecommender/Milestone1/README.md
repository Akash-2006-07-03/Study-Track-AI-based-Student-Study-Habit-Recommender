<h3> 🎓 AI-Based Student Study Tracking (Milestone 1)</h3>

<h3> 📘 Objective</h3>
To perform data preprocessing and exploratory data analysis (EDA) on student performance datasets to identify factors influencing academic success.

---

<h3>📂 Dataset Source</h3>
The datasets are taken from the UCI Machine Learning Repository:
- `student-mat.csv` – Math performance data  
- `student-por.csv` – Portuguese performance data

Each dataset contains details about:
- Student demographics (age, gender, address)
- Parental education and job
- Study time, absences, and grades

---

<h3>⚙️ Steps Performed</h3>
1. Mounted Google Drive and imported libraries.
2. Loaded both CSV files into Pandas DataFrames.
3. Merged datasets on common columns.
4. Handled missing and duplicate values.
5. Encoded categorical variables.
6. Generated descriptive statistics and correlation matrix.
7. Visualized data distributions using Matplotlib and Seaborn.

---

<h3>🧰 Tools & Libraries Used</h3>
- Google Colab  
- Pandas  
- Matplotlib  
- Seaborn  

---

<h3>💡 Key Findings / Insights</h3>
- Students with higher study time achieve better grades.  
- Students with fewer absences perform better.  
- Grade distribution is right-skewed — most students score average.  
- Parental education moderately influences student outcomes.

---

<h3>📸 Visualizations</h3>
<h3>Boxplot for Final Grades</h3>
<img width="520" height="455" alt="image" src="https://github.com/user-attachments/assets/3253ee01-8211-4c04-901e-af2f6b46a929" />

<h3>Histogram of Grades</h3>
<img width="571" height="455" alt="image" src="https://github.com/user-attachments/assets/a5260d37-66af-4281-a4bf-86e3170b2f28" />

<h3>Study Time vs Final Grade</h3>
<img width="576" height="455" alt="image" src="https://github.com/user-attachments/assets/73b24f00-66c2-4a8f-9dd2-31beb4026f4b" />

<h3>Absences vs Final Grade</h3>
<img width="576" height="455" alt="image" src="https://github.com/user-attachments/assets/acf7b0f5-f375-4edf-8301-070ee9d8df12" />

<h3>Correlation Heatmap</h3>
<img width="1028" height="655" alt="image" src="https://github.com/user-attachments/assets/315a8526-ac14-436b-83a2-9f8803f537b2" />

---

<h3>💡 Key Insights</h3>

✅ Students with higher study time generally achieve better grades.  
✅ Students with fewer absences perform better academically.  
✅ Final grades show a right-skewed distribution — most students score in the mid-range.  
✅ Parental education and support show moderate correlation with academic performance.
