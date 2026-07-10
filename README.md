# 💳 Credit Card Fraud Detection

A Machine Learning project that detects fraudulent credit card transactions using classification algorithms. The project focuses on data preprocessing, exploratory data analysis (EDA), model training, and performance evaluation to accurately classify fraudulent and legitimate transactions.

---

## 📌 Project Overview

Credit card fraud is a major challenge for financial institutions due to the large volume of daily transactions. This project aims to build a machine learning model capable of identifying fraudulent transactions while minimizing false positives.

The workflow includes:
- Data preprocessing
- Exploratory Data Analysis (EDA)
- Feature engineering
- Handling class imbalance
- Model training
- Model evaluation

---

## 🚀 Features

- Data Cleaning and Preprocessing
- Exploratory Data Analysis (EDA)
- Handling Missing Values
- Handling Imbalanced Dataset
- Feature Scaling
- Machine Learning Model Training
- Model Performance Evaluation
- Fraud Prediction

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📂 Project Structure

```
Credit-Card-Fraud-Detection/
│
├── dataset/
│   └── creditcard.csv
│
├── notebooks/
│   └── Credit_Card_Fraud_Detection.ipynb
│
├── models/
│
├── images/
│
├── requirements.txt
│
├── README.md
│
└── LICENSE
```

---

## 📊 Dataset

The project uses the **Credit Card Fraud Detection Dataset**, which contains anonymized credit card transactions labeled as:

- **0** → Legitimate Transaction
- **1** → Fraudulent Transaction

Dataset Features:
- Time
- Amount
- V1 to V28 (PCA-transformed features)
- Class (Target Variable)

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Credit-Card-Fraud-Detection.git
```

Navigate to the project folder:

```bash
cd Credit-Card-Fraud-Detection
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

---

## ▶️ Usage

Run the Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```
Credit_Card_Fraud_Detection.ipynb
```

Execute all cells to train the model and predict fraudulent transactions.

---

## 📈 Machine Learning Workflow

1. Load Dataset
2. Data Preprocessing
3. Exploratory Data Analysis (EDA)
4. Handle Class Imbalance
5. Split Training and Testing Data
6. Train Machine Learning Model
7. Evaluate Model Performance
8. Predict Fraudulent Transactions

---

## 📊 Evaluation Metrics

The model is evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- ROC-AUC Score

---

## 📷 Sample Output

Example Prediction:

```
Transaction Status: Legitimate
```

or

```
Transaction Status: Fraudulent
```

---

## 🔮 Future Improvements

- Deploy the model using Flask or FastAPI
- Build a Streamlit Web Application
- Improve accuracy using Ensemble Models
- Hyperparameter Tuning
- Real-time Fraud Detection

---

## 🤝 Contributing

Contributions are welcome!

If you'd like to improve this project:

1. Fork the repository
2. Create a new branch
3. Commit your changes
4. Push to your branch
5. Open a Pull Request

---

## 👩‍💻 Author

**Srija Manukonda**

- AI & Machine Learning Graduate
- Passionate about Data Science, Machine Learning, and Artificial Intelligence


---

## 📄 License

This project is licensed under the MIT License.
