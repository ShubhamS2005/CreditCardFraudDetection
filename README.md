# Credit Card Fraud Detection

A machine learning project to detect fraudulent credit card transactions using Python and supervised learning techniques. This project focuses on building, training, and evaluating models to predict fraud effectively.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Modeling](#modeling)
- [Evaluation](#evaluation)
- [Contributing](#contributing)
- [License](#license)

## Project Overview
Credit card fraud is a major concern for financial institutions. This project aims to create a predictive model that can identify potentially fraudulent transactions from a dataset of credit card transactions. It includes preprocessing, exploratory data analysis, model training, and evaluation.

## Dataset
The dataset used in this project is the [Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud) from Kaggle. It contains anonymized transaction data with features extracted via PCA, along with the `Class` label (`1` for fraud, `0` for legitimate transactions).

**Dataset Features:**
- `Time`: Seconds elapsed between each transaction and the first transaction in the dataset.
- `V1–V28`: PCA transformed features.
- `Amount`: Transaction amount.
- `Class`: Target label (0 = legitimate, 1 = fraud).

## Installation
Clone this repository and install the required dependencies using `pip` or `conda`:

```bash
git clone https://github.com/ShubhamS2005/CreditCardFraudDetection.git
cd CreditCardFraudDetection
pip install -r requirements.txt
```

```
conda create -n ccfraud python=3.11
conda activate ccfraud
pip install -r requirements.txt
```
## Usage
Run the main notebook or script to train and evaluate models:
```
jupyter notebook CreditCardFraudDetection.ipynb
```

## Modeling
Preprocessing includes scaling the Amount and Time features and handling class imbalance.

Models used:
1. Logistic Regression
2. Random Forest
3. XGBoost

## Evaluation
The models are evaluated using Accuracy, Precision, Recall, F1-score, and ROC-AUC curve.
Visualizations are included to analyze model performance and feature importance.

## Contributing
Contributions are welcome! If you want to improve the project:
1. Fork the repository
2. Create a new branch (git checkout -b feature-name)
3. Make your changes
4. Commit (git commit -m 'Add feature')
5. Push (git push origin feature-name)
5. Open a Pull Request

## 📜 License

This project is open-source and available under the **MIT License**.

---

## 👨‍💻 Author

Made with ❤️ by Shubham Srivastava (shubhamsrivastava12568@gmail.com)

⭐ If you find this project useful, consider giving it a star on GitHub!
