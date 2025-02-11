
# Credit Card Fraud Detection
Author - Adithya Ramachar

This project aims to develop a machine learning model to detect fraudulent credit card transactions. We use a dataset from Kaggle containing credit card transactions, some of which are fraudulent.

## Dataset

The dataset used in this project is the "Credit Card Fraud Detection" dataset from Kaggle. You can download it from the following link:

[Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/kumarpabhat/creditcard-dataset)

To use this dataset, you'll need to:

1. Create a Kaggle account if you don't have one
2. Download the dataset from the link above
3. Place the downloaded CSV file in the `data` directory of this project

## Project Structure

```
credit-card-fraud-detection/
│
├── data/
│   └── creditcard.csv
│
├── notebooks/
│   └── credit-card-fraud-detection.ipynb
│
├── src/
│   ├── __init__.py
│   ├── data_preprocessing.py
│   ├── model.py
│   └── evaluation.py
│
├── requirements.txt
├── README.md
└── .gitignore
```

## Setup

1. Clone this repository:
   ```
   git clone https://github.com/AdithyaRamachar/Credit-Card_Fraud-detection.git
   cd Credit-Card_Fraud-detection
   ```

2. Create a virtual environment and activate it:
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

4. Download the dataset from Kaggle and place it in the `data` directory.

## Usage

1. Open and run the Jupyter notebook in the `notebooks` directory:
   ```
   jupyter notebook notebooks/credit_card_fraud_detection.ipynb
   ```

2. Follow the steps in the notebook to preprocess the data, train the model, and evaluate its performance.

## Model

We use various machine learning algorithms to detect fraudulent transactions, including:

- Logistic Regression
- Random Forest
- XGBoost

The models are implemented in the `src/model.py` file.

## Evaluation

We evaluate our models using the following metrics:

- Accuracy
- Precision
- Recall
- F1-score
- ROC AUC

The evaluation code can be found in `src/evaluation.py`.

## Contributing

Contributions to this project are welcome. Please fork the repository and submit a pull request with your changes.
