🎯 Objective

To build an interactive student interface and admin panel inside a Jupyter Notebook with real-time database connectivity for logging study activities, managing records, and integrating recommendations into a functional workflow.

📊 Dataset / Database Description

This milestone uses a SQLite database created inside the notebook containing the following tables:

study_logs – stores student name, subject, duration, and date

admin – stores admin login credentials

Additional fields added during integration: recommendations and related metadata

The database is updated in real-time from the student panel and admin panel.

🧱 Steps Followed
1️⃣ Section 1 – Student Interface

Created an interactive input form for students using Python functions.

Students enter:

Name

Subject studied

Duration

Study date

Data is directly inserted into the database.

Confirmations are displayed after each submission.

2️⃣ Section 2 – Admin Panel

Built a secure login system for admins.

Admin functionalities include:

View all study logs

Add new study logs

Update existing logs

Delete logs

All operations perform real-time CRUD actions on the database.

3️⃣ Section 3 – Testing & Observations

Verified that:

New entries appear immediately in the database.

Updated logs show correct modified values.

Deleted logs are removed instantly.

A count plot visualization was created to observe subject-wise study distribution.

🛠️ Tools Used

Google Colaboratory

Python

sqlite3 (database)

pandas

matplotlib

seaborn

Jupyter Notebook UI elements (input-based interfaces)

💡 Key Insights

The student interface successfully logs real-time study data and supports repeated usage.

The admin panel enables smooth database management through CRUD operations.

The system can be expanded to integrate recommendation logic from earlier milestones.

Visualization helps identify which subjects students study most frequently.
