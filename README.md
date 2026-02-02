# 📊 Customer Churn Prediction – StreamWorks Media

**📌 Project Overview**

StreamWorks Media is a UK-based video streaming platform operating in a highly competitive market. With rising customer acquisition costs and increasing competition, understanding and reducing customer churn is critical to sustaining revenue and long-term growth.

This project analyses customer behaviour to identify churn drivers, predict churn risk, and deliver actionable retention insights using statistical analysis and machine learning.

⸻

**🎯 Project Goal**

	•	Understand who is churning and why
	•	Identify early churn risk signals
	•	Build predictive models to flag high-risk users
	•	Translate analytical findings into business-ready retention strategies

⸻

**🌍 Real-World Business Impact**

The outcomes of this project help StreamWorks Media to:

	•	Proactively identify users at high risk of cancellation
	•	Target retention campaigns more effectively
	•	Reduce revenue leakage and improve customer lifetime value (CLV)
	•	Focus product and content strategies on engagement-driven retention

Business Value:

	•	Lower churn → higher recurring revenue
	•	More efficient marketing and promotion spend
	•	Improved customer loyalty and competitive positioning

⸻

📂 Dataset Summary

	•	1,500 users with demographic, behavioural, subscription, and churn data
	•	Features include watch behaviour, tenure, pricing, promotions, and referrals
	•	Churn rate ≈ 23%, indicating a meaningful retention challenge

⸻

**🔍 Analysis & Methodology**

1. Data Cleaning & Preparation
   
	•	Corrected data types (dates, categorical, numeric, target variable)

	•	Handled missing values using business-aware logic (e.g. plan-based pricing)

	•	Standardised text fields and removed non-informative features

3. Feature Engineering

Created meaningful behavioural and lifecycle features, including:

	•	tenure_days, is_loyal
	
	•	watch_per_fee_ratio (perceived value)
	
	•	low_watch_time, high_engagement
	
	•	low_value_user, heavy_mobile_user

These features capture engagement intensity, perceived value, and lifecycle risk.

3. Exploratory Data Analysis (EDA)
   
	•	Churn rate analysis across demographics, plans, and behaviour

	•	Cohort analysis using signup dates

	•	Statistical tests

	•	Chi-square for categorical relationships

	•	t-test for watch-time differences

	•	Correlation & Phi tests for feature relationships


5. Predictive Modelling
   
	•	Logistic Regression (with L1 regularisation & hyperparameter tuning)
	•	Random Forest to capture non-linear behaviour
	•	Addressed class imbalance using class weighting
	•	Model evaluation using
	•	Precision, Recall, F1-score
	•	Confusion Matrix
	•	ROC-AUC

⸻

**📈 Key Findings & Business Insights**

🔴 Strongest Churn Drivers

	•	Low watch time → strongest and clearest churn signal
	•	Low perceived value-for-money
	•	Lifecycle effects: both early disengagement and long-tenure fatigue

🟢 Retention Signals

	•	High engagement users churn significantly less
	•	Promotions and referrals modestly reduce churn risk
	•	Pricing tier alone does not drive churn — value perception does

🧠 Strategic Insight

Churn is driven by silent disengagement, not complaints or demographics.

⸻

**📌 Final Recommendations**

	•	Trigger early engagement nudges for low watch-time users (first 30–60 days)
	•	Launch re-engagement programs for long-tenure users (content refresh, loyalty rewards)
	•	Focus promotions on low-engagement, low-value-perception users
	•	Invest in personalised recommendations and usage-based messaging

⸻

**🛠️ Tools & Technologies**

	•	Python, Pandas, NumPy
	•	scikit-learn (Logistic Regression, Random Forest, GridSearchCV)
	•	Matplotlib & Seaborn for visualisation
	•	Statistical testing with SciPy

⸻

**📎 Outcome**

This project demonstrates how data-driven churn analysis can move a business from reactive retention to proactive, insight-led decision making, directly supporting revenue protection and customer experience improvement.
