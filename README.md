# A Federated LSTM-Autoencoder Framework with Differential Privacy for Secure Healthcare IoT Anomaly Detection

This repository contains the official source code and reproducibility package for our research paper: **"[Yahan Apne Paper Ka Mukammal Title Likhain]"**. 

Our proposed framework implements a Federated LSTM-Autoencoder (with and without Differential Privacy) to detect anomalies in healthcare IoT environments while preserving patient data privacy.

## 📂 Repository Structure

The code is divided into three main experimental setups:
1. **Centralized Learning Model:** Baseline LSTM-Autoencoder trained on centralized data.
2. **Federated Learning (FL) Model:** Decentralized training using Federated Learning.
3. **Federated Learning with Differential Privacy (FL+DP):** Enhanced privacy-preserving model. 
   - *Note on FL+DP Experiments:* To manage heavy computational loads and prevent Out of Memory (OOM) errors, the FL+DP experiments were systematically split into 25 separate files. These files represent individual execution runs combining 5 different random seeds and 5 distinct privacy values.

## ⚙️ Requirements & Installation

To run this code, you need Python 3.10 or higher (Tested on Python 3.12 in Kaggle environment installed. You can install all the required libraries using the provided `requirements.txt` file.

Run the following command in your terminal:
```bash
pip install -r requirements.txt
