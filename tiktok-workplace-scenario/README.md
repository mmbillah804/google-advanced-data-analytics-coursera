# TikTok Workplace Scenario: Statistical Analysis & Machine Learning Classification

This repository presents two complementary data science notebooks developed during a certification program. The project simulates a real-world workplace scenario at TikTok, where user-generated reports require automated moderation support. The goal is to analyze video data and help build a predictive model that classifies content as either a **claim** or an **opinion** to assist TikTok moderators.


## 📘 Project 1: Hypothesis Test – Verified vs. Unverified Accounts

**Objective:**  
Explore whether **verified status** of TikTok accounts influences **video view count** using statistical hypothesis testing.

**Key Steps:**
- Cleaned and explored the dataset.
- Compared mean view counts between verified and unverified users.
- Conducted a two-sample **t-test**.
- **Rejected the null hypothesis**: Verified and unverified accounts show a statistically significant difference in average video view counts.

**Insight:**  
Verified accounts consistently receive more views, implying behavioral or algorithmic differences between account types. This insight could inform further user-behavior modeling.

📄 Notebook: [`tiktok_hypothesis_testing.ipynb`](./tiktok_hypothesis_testing.ipynb)


## 🤖 Project 2: Machine Learning Model – Claim vs. Opinion Classification

**Objective:**  
Build a machine learning model to classify TikTok video content as **claim** or **opinion**, helping prioritize moderation efforts.

**Workflow Highlights:**
- Target variable: `claim_status` (binary classification)
- Preprocessing: Handled missing values, performed feature engineering (e.g., text length, n-grams)
- Model: Trained a **Random Forest** classifier with hyperparameter tuning via `GridSearchCV`
- Metric of interest: **Recall** (to reduce false negatives)
- Achieved high accuracy and excellent recall, minimizing the risk of missing harmful claim content.

**Key Insight:**  
Engagement metrics (views, likes, shares) and text characteristics are strong indicators of whether a video is likely to be a claim.

📄 Notebook: [`tiktok_modeling.ipynb`](./tiktok_modeling.ipynb)


## ✅ Key Takeaways

- Demonstrated end-to-end data science skills: data cleaning, EDA, statistical testing, feature engineering, model building, evaluation.
- Addressed a real-world content moderation challenge with both statistical and machine learning approaches.
- Prioritized ethical model design by emphasizing **recall** to reduce risk of harmful content going undetected.


## 🛠 Tech Stack

- **Language:** Python 3
- **Libraries:** `pandas`, `numpy`, `scipy`, `matplotlib`, `seaborn`, `scikit-learn`, `xgboost`


## 📌 Notes

- Data used in these notebooks is a simulated TikTok dataset from the certification coursework.
- All models and tests are designed for educational and demonstration purposes.


## 📬 Contact

For feedback, collaboration, or questions:

🔗 [LinkedIn](https://www.linkedin.com/in/mmbillah804/)  
🔗 [GitHub](https://github.com/mmbillah804)
