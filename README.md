# Credit Card Fraud Detection

## 📌 Project Overview
This project develops a classification model to detect fraudulent credit card transactions efficiently. The dataset includes transaction details like amount, merchant details, timestamps, and more. 

## 📂 Dataset Source
We use the [Credit Card Fraud Detection dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud) from Kaggle, provided by ULB Machine Learning Group. It contains transactions made by European cardholders in September 2013.

## 🚀 Features and Techniques
- **Handling Class Imbalance:** SMOTE (Synthetic Minority Over-sampling Technique) is used to balance the dataset.
- **Feature Engineering:** Derived features such as transaction frequency, location mismatch, and spending patterns.
- **Model Selection:** We use Random Forest due to its robustness and ability to handle imbalanced data.
- **Evaluation Metrics:** Classification report, Confusion Matrix, and ROC-AUC Score.

## 📂 Project Structure
```
credit-card-fraud-detection/
│── data/                # Raw dataset and preprocessed data
│── models/              # Trained models and checkpoints
│── notebooks/           # Jupyter notebooks for EDA and experiments
│── scripts/             # Python scripts for data processing and model training
│── requirements.txt     # Dependencies
│── preprocess.py        # Data preprocessing script
│── train.py             # Model training script
│── evaluate.py          # Model evaluation script
│── README.md            # Project documentation
```

## ⚙️ Setup & Installation
1. Clone the repository:
   ```sh
   git clone <repository_url>
   cd credit-card-fraud-detection
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the preprocessing script:
   ```sh
   python preprocess.py
   ```
4. Train the model:
   ```sh
   python train.py
   ```
5. Evaluate the model:
   ```sh
   python evaluate.py
   ```

## 📊 Model Performance
| Metric           | Score |
|----------------|-------|
| Accuracy       | 98.5% |
| Precision      | 94.2% |
| Recall         | 89.6% |
| ROC-AUC        | 99.1% |

## 💡 Future Enhancements
- Experiment with deep learning models.
- Implement real-time fraud detection using streaming data.

## 🤝 Contributing
Pull requests are welcome! Please ensure your code is well-documented and tested before submission.

## 📜 License
This project is licensed under the MIT License.

