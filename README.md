# Fire Safety Analytics – Fault Prediction & Escalation Risk

This project was completed as part of my Bachelor of Information Technology (AI Major) at Macquarie University in collaboration with Fiftyfive Group.

The goal was to analyze ~1M historical fire detector logs and build a predictive model to reduce false alarms, detect risky detectors early, and assess the likelihood of escalation from Fault → Alarm → Brigade Callout.

# Key Features

* Built a supervised machine learning model to predict detector faults.
* Engineered rolling window features (14-day fault counts, average durations, etc.).
* Developed a fault → alarm → brigade escalation pipeline to identify risky detectors.
* Created a PowerBI dashboard to visualize fault trends and escalation insights.

# Insights

* Only 7.44% of faults progressed into alarms.
* Only 1.59% of alarms escalated into brigade callouts.
* Certain detectors repeatedly showed high escalation risk → candidates for proactive maintenance.

# Tech Stack

* Python (Pandas, Scikit-learn, Matplotlib)
* SQL Server for log storage and preprocessing
* Jupyter Notebooks for feature engineering & model training
* PowerBI for dashboards

# Note

Due to data privacy, raw datasets are not included.
Instead, this repo focuses on the code pipeline and analysis logic, along with visuals from the dashboard.
