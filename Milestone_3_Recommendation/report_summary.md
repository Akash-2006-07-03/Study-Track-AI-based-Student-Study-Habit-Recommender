

## Objective
Generate actionable study recommendations for students based on behavioral clusters identified in previous analyses.

## Dataset Source
**UCI Student Performance Dataset**  
https://archive.ics.uci.edu/ml/datasets/Student+Performance

## Steps Followed
1. Loaded and cleaned the student dataset.
2. Applied clustering (K-Means) to group students by study habits and performance.
3. Mapped each cluster to meaningful study recommendations.
4. Implemented a Python recommendation engine that assigns guidance based on ClusterID.
5. Added two new columns to the dataset:
   - `Recommendation`
   - `Tool_or_Technique`
6. Visualized the distribution of recommendations using a count plot.

## Tools Used
- Google Colaboratory
- Python  
  - pandas  
  - scikit-learn  
  - seaborn  
  - matplotlib  

## Key Insights
**Cluster 0:**  
Students are consistent high performers. They are encouraged to maintain their current routine and may also lead peer study or tutoring sessions.

**Cluster 1:**  
Students benefit from increasing focused study hours, reducing absences, and using structured learning tools such as planners or online platforms.

**Cluster 2:**  
Students should add weekly review sessions and use digital flashcards or planning tools to strengthen moderate study habits.
