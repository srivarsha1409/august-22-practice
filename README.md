**📊 LOGISTIC REGRESSION & k-NN PRACTICE**
**🚀 OVERVIEW**

This project has 5 practice tasks to learn Logistic Regression and k-Nearest Neighbors (k-NN) on real datasets.
You will:

Predict spam emails, customer churn, disease stages.

Classify flowers using k-NN.

Predict Airbnb prices with k-NN regression.



📂 DATASETS
Dataset	Task	**Target**

Email Spam	Binary Classification	is_spam

Customer Churn	Binary Classification	churn

Disease Stage	Multiclass Classification	stage

Flowers	Classification	species

Airbnb Prices	Regression	price




**🛠 REQUIREMENTS**

Python 3.9+

Libraries: numpy, pandas, scikit-learn, matplotlib, seaborn

Install with:

pip install numpy pandas scikit-learn matplotlib seaborn



**📌 TASKS**
**1️⃣ Email Spam (Logistic Regression)**

Features: word_free, word_offer, word_click, num_links, num_caps, sender_reputation

Predict: is_spam

Metrics: Accuracy, Precision, Recall, F1, ROC-AUC, Confusion Matrix



**2️⃣ Customer Churn (Logistic Regression)**

Features: tenure_months, monthly_charges, support_tickets, is_premium, avg_usage_hours

Predict: churn

Metrics: Same as above



**3️⃣ Disease Stage (Multiclass Logistic Regression)**

Features: age, b1, b2, b3, b4

Predict: stage (0,1,2)

Metrics: Accuracy, Macro-F1, Weighted-F1, Confusion Matrix



**4️⃣ Flowers (k-NN Classification)**

Features: sepal_length, sepal_width, petal_length, petal_width

Use 5-fold CV to pick best k (1,3,...25)

Report: Best k, CV score, Test Accuracy, Confusion Matrix



**5️⃣ Airbnb Prices (k-NN Regression)**

Features: size_m2, distance_center_km, rating, num_reviews

Use 5-fold CV to pick best k

Report: CV RMSE, Test RMSE, Test R²



**📈 NOTES**

🔹 Scale features for k-NN

🔹 Use stratified split for classification

🔹 Evaluate all metrics to compare models
