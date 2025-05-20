🎯 Objective

Build a predictive classification model that determines whether a passenger survived based on various features like:

- 👨‍👩‍👧‍👦 Family size  
- 🧠 Gender  
- 💰 Fare paid  
- 🎟️ Ticket information  
- 🧳 Class and cabin  
- 👑 Extracted titles (Mr, Mrs, etc.)

---

🔍 Models Used & Results

 ✅ Random Forest
| Metric         | Value |
|----------------|-------|
| Initial Accuracy      | 0.8101 |
| Best CV Accuracy      | 0.8006 |
| Test Accuracy         | 0.8101 |
| Best Params           | `n_estimators=60`, `max_depth=40`, `max_samples=0.198`, `criterion='gini'` |

> ⚠️ **Note:** When rerunning the code later, results dropped slightly due to the randomness in train/test split and model initialization (new test acc: 0.6145). This shows the importance of controlling random states.

---
 
 ✅ AdaBoost
| Metric         | Value |
|----------------|-------|
| Initial Accuracy      | 0.8156 |
| Best CV Accuracy      | 0.8315 |
| Test Accuracy         | 0.8045 |
| Best Params           | `n_estimators=800`, `learning_rate=0.01` |

---

 🧪 Techniques Applied

- 🔄 Data Cleaning & Imputation (Age, Fare, Embarked, Cabin)
- 🧠 Feature Engineering (Title extraction, Age/Fare binning, Family size)
- 🧮 Label Encoding & One-Hot Encoding
- 🔍 Model Tuning with `GridSearchCV` and `RandomizedSearchCV`
- 📊 Accuracy comparison across models

---

 📌 Key Learnings

- Strengths & weaknesses of ensemble models
- The impact of hyperparameters on model performance
- Importance of reproducibility in ML projects
- Building a full ML pipeline from preprocessing to evaluation

---

🔗 Project Demo / LinkedIn Post

👉 [Add your LinkedIn post link here]

---

📬 Contact

Made with ❤️ by Omar Ezzat Ali (Mung)  
🔗Linkedin: [www.linkedin.com/in/omar-ezzat-ali-03b70628b]
🐙Github: [(https://github.com/omarudesuo)].

