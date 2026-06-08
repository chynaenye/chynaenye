# Hi, I'm Chinenye 👋

I'm a Machine Learning Engineer building AI systems that work in the real world — not just in notebooks.

I'm drawn to problems where getting it wrong has real consequences — dropped connections, missed risks, systems that fail the people depending on them. That's what drives how I build.

---

## 🚀 Projects

### 📡 Cellular Network Handover Prediction
A machine learning project predicting when a mobile device will switch from one cell tower to another, using real network signal logs.

- Trained and compared Logistic Regression, Decision Tree, Random Forest, and XGBoost on imbalanced time-series data
- Used SMOTE and class weighting to address a 97:3 class imbalance
- Engineered rate-of-change features (RSRP_diff, RSRQ_diff, SINR_diff) that pushed recall from near zero to 97% — feature engineering mattered more than model choice
- Selected XGBoost at threshold 0.2 — optimised for recall, since a missed handover means a dropped call
- Applied chronological splitting to prevent temporal data leakage
- Built a modular codebase with separated data loading, preprocessing, feature engineering, training, evaluation, and prediction

👉 [Repository](https://github.com/chynaenye/network-handover-prediction)

---

### 🧠 Microinsurance Risk Predictor & Dashboard
A classification model and interactive dashboard for predicting customer dropout risk in a microinsurance setting.

- Built with emphasis on recall — a missed high-risk customer is more costly than a false alarm
- Visualises dropout trends and risk signals to support data-driven decisions
- Deployed as two interactive tools using Streamlit

👉 [Predictor Demo](https://microinsurance-predictor.streamlit.app/) | [Predictor Repo](https://github.com/chynaenye/microinsurance-predictor)  
👉 [Dashboard Demo](https://microinsurance-risk-dashboard.streamlit.app/) | [Dashboard Repo](https://github.com/chynaenye/Microinsurance-dashboard)

---

## ⚙️ Tech Stack

**Languages:** Python, R, SQL  
**Data & ML:** Pandas, NumPy, scikit-learn, XGBoost, imbalanced-learn  
**Visualization:** Matplotlib, Seaborn  
**Apps & Deployment:** Streamlit  
**Workflow:** Git, modular Python project structure

---

## 📈 Current Focus

Building depth in the ML fundamentals — model evaluation, feature engineering, handling real-world data — and moving toward systems that can actually be deployed and maintained.

The skills I'm developing next, in sequence:

- **MLOps** — how models are deployed, monitored, versioned, and improved over time
- **Deep Learning** — neural networks and what they make possible beyond classical ML
- **Computer Vision** — applying AI to image and sensor data for detection and classification problems
- **AI Engineering** — building systems where models are one component of something larger
- **Generative AI** — building practical applications on top of large language models

The goal isn't to be everything at once. It's to build depth that compounds.

---

## 🔗 Connect

- LinkedIn: [chinenye-onwugamba](https://www.linkedin.com/in/chinenye-onwugamba)
