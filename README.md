# 🚀 Fake Job Posting Prediction

## 📌 Project Overview
This project aims to build a machine learning model that predicts fraudulent job postings. Using various classification algorithms and data preprocessing techniques, the model identifies scams in job listings based on structured features. Aiming for Deep Learning after finishing machine learning tasks. Resuming project on April 8th 2025 after long gap due to examination.

## 📂 Dataset
The dataset used for this project consists of job postings with labels indicating whether the job is fraudulent (1) or legitimate (0). It contains structured attributes such as job title, company profile, location, salary range, and job description. 

**Key Challenges:**
- Highly imbalanced dataset (few fraudulent jobs compared to legitimate ones)
- Presence of textual data requiring feature engineering
- Need for careful handling of false negatives (missing fraudulent jobs)

## 🛠️ Methodology
### 1️⃣ **Exploratory Data Analysis (EDA)**
- Checked class distribution and feature importance
- Visualized missing values and handled them appropriately

### 2️⃣ **Data Preprocessing**
- Removed unnecessary text preprocessing to avoid information loss
- Applied **TF-IDF** vectorization for text features (if applicable)
- Handled class imbalance using **SMOTE and Hybrid Sampling**

### 3️⃣ **Model Training & Evaluation**
- **Logistic Regression**
- **Random Forest Classifier**
- **Support Vector Machine (SVM) – Best Performing Model**
- **XGBoost**
- **Deep Learning-NLP(going on)**

📊 **Best Model: Tuned SVM**
- **Accuracy:** 98.5%
- **Recall (Fraudulent Jobs):** 75%
- **Precision (Fraudulent Jobs):** 96%

## ⚡ Results & Findings
- **Class imbalance affected performance**: SMOTE and hybrid sampling helped improve recall.
- **Lowering decision threshold** increased fraud detection but reduced precision.
- **Tuned SVM with polynomial kernel performed best.**
- **Further tuning & threshold optimization could improve recall.**

## 🏗️ Installation & Usage
```bash
# Clone the repository
git clone https://github.com/your-username/Fake-Job-Posting-Prediction.git
cd Fake-Job-Posting-Prediction

# Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`

# Install dependencies
pip install -r requirements.txt
```

## 📌 Future Improvements
- Hyperparameter tuning for **XGBoost**
- Experimenting with **threshold optimization** to balance precision & recall
- Feature engineering to improve model interpretability

## 📜 License
This project is open-source and available under the MIT License.

---
👨‍💻 **Contributions are welcome!** If you have any suggestions, feel free to fork the repo and submit a PR. 🚀
