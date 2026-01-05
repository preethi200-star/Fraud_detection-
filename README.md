# Fraud Detection System using Anomaly Detection

## 📌 Problem Statement
Financial fraud causes huge losses. The challenge is detecting rare fraudulent transactions among millions of legitimate ones.

## 📊 Dataset
Credit card transaction dataset where:
- Class 0 = Normal
- Class 1 = Fraud

## ⚙️ Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn

## 🧠 ML Model Used
- Isolation Forest (Unsupervised Learning)

## 🔄 Workflow
1. Data preprocessing
2. Feature scaling
3. Train Isolation Forest
4. Detect anomalies
5. Evaluate using precision, recall, confusion matrix

## 📈 Key Insight
Precision and Recall are more important than accuracy due to data imbalance.

## 🚀 Future Enhancements
- Try Autoencoders
- Use hybrid supervised + unsupervised models
- Real-time fraud detection pipeline

## 🧪 How to Run
'''bash
pip install -r requirements.txt
python fraud_detection.py
