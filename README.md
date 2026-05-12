# Mini-Project
Mini Project for Semester 2


# Quantum-Safe Federated Learning for Cyber Threat Detection in 5G IoT

A mini project implementing a **Quantum-Safe Federated Learning Framework** for detecting cyber threats in **5G-enabled IoT ecosystems** using **MobileNet-V1 + BiGRU**, **Federated Learning**, and **LWE (Learning With Errors) cryptography**.

## Overview

Traditional centralized intrusion detection systems require sharing sensitive network data, leading to privacy and security concerns.

This project proposes a **privacy-preserving and quantum-safe cyber threat detection framework** where multiple IoT clients collaboratively train a model using **Federated Learning (FL)** without sharing raw data. To secure communication, **LWE-based post-quantum cryptography** is integrated.

The system is capable of detecting attacks such as:

- ICMP Flood
- UDP Flood
- SYN Scan
- Port Scan
- DDoS attacks

---

## Features

1. Federated Learning for decentralized training  
2. Quantum-safe secure aggregation using LWE encryption  
3. Hybrid **MobileNet-V1 + BiGRU** deep learning model  
4. Privacy-preserving cyber threat detection  
5. Evaluation on **5G-NIDD dataset**

---

## Architecture

The system consists of:

### 1. Trusted Authority (TA)
- Generates cryptographic keys
- Establishes secure communication

### 2. IoT Clients
- Train locally on private datasets
- Encrypt model updates

### 3. Cloud Server
- Aggregates encrypted updates
- Updates global model

---

## Workflow

1. Dataset preprocessing using **5G-NIDD dataset**
2. Distribution of local data among IoT clients
3. Initialization of **MobileNet-V1 + BiGRU** global model
4. Local client-side training
5. Encryption of model updates using **LWE**
6. Secure aggregation using **Federated Averaging (FedAvg)**
7. Global model update and redistribution

---

## Model Used

### MobileNet-V1
Used for lightweight feature extraction in resource-constrained IoT environments.

### BiGRU (Bidirectional GRU)
Used for sequential traffic analysis and temporal dependency learning.

---

## Results

### Best Results Achieved

| Metric | Value |
|--------|--------|
| Accuracy | **97.77%** |
| Precision | **0.9777** |
| F1 Score | **0.9772** |

**Best configuration:**  
- K = 5  
- 13 Federated Learning rounds

---

## Tech Stack

- Python
- TensorFlow / Keras
- Federated Learning
- MobileNet-V1
- BiGRU
- LWE Cryptography
- Google Colab

---

## Dataset

**Dataset Used:** 5G-NIDD Dataset

The dataset contains network traffic samples for cyber threat detection in **5G-enabled IoT environments**.

---

## 👨‍💻 Author

**Vidit Gala**  
Mini Project – Quantum-Safe Federated Learning for Cyber Threat Detection in 5G IoT
