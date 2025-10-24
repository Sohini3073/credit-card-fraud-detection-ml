# credit-card-fraud-detection-ml
# 💳 Credit Card Fraud Detection using Machine Learning

This project uses a Random Forest classifier and SMOTE to detect fraudulent transactions in a highly imbalanced dataset.

## 🚀 Features
- Handles imbalanced data using SMOTE
- Model trained with RandomForestClassifier
- Web app built using Streamlit for real-time fraud checks

## 📂 Project Structure
fraud_detection_project/
│
├── 📘 fraud_detection.ipynb          # Main Jupyter Notebook (EDA + ML training)
│
├── 💻 fraud_streamlit.py             # Streamlit web app for live fraud detection
│
├── 📂 models/
│   ├── fraud_model.pkl               # Trained ML model (Random Forest)
│   └── scaler.pkl                    # Saved scaler for input normalization
│
├── 📊 data/
│   └── creditcard.csv                # Dataset (optional to include in repo, large files can be ignored)
│
├── 📦 requirements.txt               # Dependencies (pandas, sklearn, streamlit, etc.)
│
├── 🧾 README.md                      # Project documentation for GitHub
│
├── 🧠 utils/
│   └── helper.py                     # (Optional) extra Python utilities or preprocessing functions
│
├── 📸 assets/
│   ├── fraud_demo.png                # Screenshot of your app output
│   └── logo.png                      # Project logo (optional)
│
└── .gitignore                        # To ignore unnecessary files (like .ipynb_checkpoints/, _pycache_/)
## 🧠 Tech Stack
- Python, Pandas, NumPy
- Scikit-learn, Imbalanced-learn
- Streamlit, Seaborn, Matplotlib




















