# Anomaly Detection in Credit Card Transactions

## Overview
This project implements anomaly detection techniques to identify fraudulent credit card transactions. It leverages machine learning models such as **Isolation Forest** and **Autoencoder Neural Networks** to detect anomalies in transaction data.

## Features
- **Data Preprocessing**: Handles skewness in features and normalizes data.
- **Visualization**: Histograms and pie charts for data distribution.
- **Machine Learning Models**:
  - **Isolation Forest** for unsupervised anomaly detection.
  - **Autoencoder Neural Network** for reconstructing normal transaction patterns and identifying fraud.
- **Performance Metrics**: Includes ROC-AUC scores and confusion matrices.

## Dataset
This project uses a credit card transactions dataset. Due to its large size, you can download it from the following link:

[Dataset Download](<https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud>)

## Installation
To run this project, install the required dependencies:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn tensorflow
```

## Usage
1. Clone this repository:
   ```bash
   git clone <https://github.com/hmankar01/Ecommerce-Fraud-Detection>
   cd <Ecommerce-Fraud-Detection>
   ```
2. Ensure the dataset is placed correctly or downloaded via the provided link.
3. Run the script:
   ```bash
   python anomoly_detection.py
   ```

## Results
- The model outputs classification reports, ROC-AUC scores, and confusion matrices to assess performance.
- Visualizes fraud vs. non-fraud transaction distributions.

## Future Improvements
- Experiment with additional anomaly detection techniques.
- Tune hyperparameters for better model accuracy.
- Deploy the model as a web API for real-time fraud detection.

## License
This project is licensed under the MIT License.

---
**Author:** Harsh Mankar
**Contact:** harshrajendramankar@gmail.com

