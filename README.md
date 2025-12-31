# 📊 Customer Satisfaction Prediction System

An end-to-end **Machine Learning & NLP project** that predicts customer satisfaction from support tickets using structured data and textual descriptions.  
The project also includes an **interactive Streamlit dashboard** for Exploratory Data Analysis (EDA) and live predictions.

---

## 🔥 Project Highlights

- ✅ End-to-end Data Science project  
- ✅ NLP using **TF-IDF Vectorization**  
- ✅ Machine Learning with **Random Forest (class-balanced)**  
- ✅ Extensive **EDA with visualizations**  
- ✅ Interactive **Streamlit Web Application**  
- ✅ Live customer satisfaction prediction  
- ✅ Main-project / final-year-project ready  

---

## 🧠 Problem Statement

Customer satisfaction is a critical metric for any business.  
This project aims to **predict whether a customer is satisfied or not** based on:

- Support ticket description (text data)
- Ticket type, priority, and channel
- Customer demographic information

The goal is to help organizations:
- Identify unhappy customers early
- Improve support quality
- Optimize customer service operations

---

## 🗂 Dataset Overview

**Dataset:** Customer Support Ticket Dataset  

**Key Features:**
- `Ticket Description` – Customer issue (text)
- `Ticket Type` – Technical / Billing / Product inquiry
- `Ticket Priority` – Low / Medium / High / Critical
- `Ticket Channel` – Email / Chat / Phone / Social Media
- `Customer Age`
- `Customer Satisfaction Rating` (1–5)

**Target Variable:**
- `Satisfied`  
  - `1` → Rating ≥ 4  
  - `0` → Rating < 4  

---

## 🛠 Tech Stack

| Category | Tools |
|--------|------|
| Programming | Python |
| Data Analysis | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| NLP | TF-IDF Vectorizer |
| Machine Learning | Scikit-learn (Random Forest) |
| Web App | Streamlit |
| Version Control | Git, GitHub |

---

## 📊 Exploratory Data Analysis (EDA)

The Streamlit dashboard includes:

- Customer satisfaction distribution
- Ticket priority and channel analysis
- Ticket channel vs satisfaction
- Most common words in ticket descriptions
- Dataset viewer with download option

---

## 🤖 Machine Learning Pipeline

1. **Data Cleaning**
2. **Feature Engineering**
   - Binary target creation
   - Text preprocessing
3. **Preprocessing**
   - TF-IDF for text
   - One-Hot Encoding for categorical features
   - Standard Scaling for numerical features
4. **Model Training**
   - Random Forest with `class_weight='balanced'`
5. **Evaluation**
   - Confusion Matrix
   - ROC Curve & AUC
6. **Deployment**
   - Integrated into Streamlit app (no external model file)

---

## 🚀 Streamlit Application Pages

1. **Overview**
   - Project summary & key metrics
2. **EDA Dashboard**
   - Interactive visual analysis
3. **Model Performance**
   - Confusion matrix & ROC curve
4. **Live Prediction**
   - User inputs ticket details
   - Predicts satisfaction with probability
5. **Dataset Viewer**
   - View and download dataset

---

## ▶️ How to Run the Project

### 1️⃣ Clone the repository
```bash
git clone https://github.com/your-username/Customer-Satisfaction-Prediction.git
cd Customer-Satisfaction-Prediction
```
### 2️⃣ Install dependencies
``` bash
pip install -r requirements.txt
```
### 3️⃣ Run Streamlit app
``` bash
streamlit run app.py
```

---

### 📁 Project Structure

Customer-Satisfaction-Prediction/<br>
│<br>
├── app.py<br>
├── data/<br>
│   └── customer_support_tickets.csv<br>
├── requirements.txt<br>
├── README.md<br>
└── venv/ (ignored in GitHub)<br>

---

### 🎯 Results & Insights

- The model successfully identifies dissatisfied customers
- Textual ticket descriptions play a major role in prediction
- Ticket priority and channel strongly influence satisfaction
- Class imbalance is handled using balanced learning techniques

---

### 🔮 Future Enhancements

- Add XGBoost / LightGBM models
- Integrate SHAP explainability
- Deploy to Streamlit Cloud
- Add authentication & role-based access
- Build REST API using FastAPI

---

## 👤 Author  
**Pranuth HM**  
🔗 [GitHub Profile](https://github.com/PranuthHM)
🔗 [LinedIn Profile](https://www.linkedin.com/in/pranuth-hm)
🔗 [Portfolio Profile](https://pranuth.netlify.app/)
