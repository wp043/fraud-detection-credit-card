# Credit Card Fraud Detection
A full-scale dashboard for fraud detection that allows us to:
* toggle a threshold so we can compare a baseline model to an improved machine learning model with an updated threshold
* apply a total cost of fraud formula to attach a cost to our different misclassifications and correct classifications

## Dataset
Download from [here](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/wp043/fraud-detection-credit-card.git
   ```
2. Navigate to the project directory:
   ```bash
   cd credit-card-fraud-detection
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. To run the Streamlit dashboard, use the following command:
   ```bash
   streamlit run app.py
   ```