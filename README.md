# Neural Network for Credit Risk Scoring

This project implements a deep learning approach to predict credit risk using a neural network built in PyTorch. It includes data preprocessing, model training, evaluation, and explainability using SHAP (SHapley Additive exPlanations).

---

## 📌 Project Summary
Credit risk scoring helps financial institutions identify which customers are likely to default on loans. This project builds a binary classifier that predicts whether a borrower is a credit risk based on historical loan data.

---

## 🧠 Key Features
- PyTorch-based neural network with ReLU and Dropout layers
- Binary classification with Sigmoid activation
- Accuracy evaluation on test data
- Model interpretability using SHAP

---

## 📁 Project Structure
```
├── credit_risk_nn.py         # Main Python file with model and SHAP code
├── credit_risk_data.csv      # (You should replace this with your dataset)
├── README.md                 # Project documentation
└── requirements.txt          # Dependencies
```

---

## 🚀 How to Run
1. Clone the repository
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Add your dataset to the project as `credit_risk_data.csv`
4. Run the script:
   ```bash
   python credit_risk_nn.py
   ```

---

## ⚙️ Model Details
- **Input:** Numerical features from loan data
- **Hidden Layers:** Two fully connected layers with ReLU
- **Dropout:** 0.3 to reduce overfitting
- **Output:** Sigmoid-activated prediction (default or not)
- **Loss Function:** Binary Cross-Entropy
- **Optimizer:** Adam

---

## 📊 SHAP Explainability
- SHAP is used to understand feature impact on predictions
- Summary plot visualizes feature contributions

---

## 🧪 Evaluation
- Threshold = 0.5 for binary classification
- Accuracy calculated as proportion of correct predictions

---

## 🔧 Requirements
```
pandas
numpy
torch
sklearn
shap
matplotlib
```

---

## 🧠 Author
**Nuthan Reddy**  
Data Science Graduate | PyTorch & ML Enthusiast  
[LinkedIn](https://www.linkedin.com/in/nuthan-reddy-vaddi-reddy-ba4976250) • [GitHub](https://github.com/Nuthanreddy05)

---

## 📌 License
This project is for educational and portfolio use. Contact for commercial licensing.

---

Feel free to fork, modify, and use this project as a foundation for more advanced financial risk models!
