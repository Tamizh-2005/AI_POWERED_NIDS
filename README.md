# ⚔️ Network Intrusion Detection System (NIDS) using IBM watsonx.ai

A machine learning solution to detect, classify, and analyze cybersecurity threats in real-time network traffic. This project leverages supervised learning techniques to monitor packets and identify potential intrusions.

---

## 📚 Problem Statement

Design a robust Network Intrusion Detection System (NIDS) that classifies network connections into **normal** or various **attack types** (e.g., DoS, Probe, R2L, U2R). The system must efficiently handle categorical and continuous features to ensure high accuracy and low false positives.

---

## 🔗 Dataset

**Kaggle**: [KDD Cup 99 / NSL-KDD Dataset](https://www.kaggle.com/datasets/ghazouaniabdellatif/nslkdd)  
- Used pre-processed Train and Test splits  
- Supports classification into multiple attack categories

---

## 🛠️ Technology Stack

- **Platform**: IBM watsonx.ai Studio
- **Runtime**: watsonx.ai + IBM Granite Model
- **Modeling**: Jupyter Notebooks (Manual + AutoAI integration)
- **Deployment**: IBM Cloud Lite
- **Tools**: watsonx.ai Agent Lab, AutoAI, Watson Pipelines
- **Datacenter Regions**: Chennai and Sydney

---

## 🧪 Features

- Attack type classification: **DoS**, **Probe**, **R2L**, **U2R**, **Normal**
- Label encoding and feature scaling pipeline
- Confusion matrix and performance visualizations
- Feature importance analysis using Random Forest
- Secure model deployment via IBM Cloud
- AutoAI pipeline integration with tunable hyperparameters
- Train/test split with robust evaluation metrics

---

## 🚀 Setup Instructions

1. Login to **IBM Cloud**
2. Open **watsonx.ai Studio** → Create New Project
3. Upload CSV datasets and Jupyter Notebook
4. Use **AutoAI** or manual ML pipeline to train and evaluate the model
5. Deploy model and connect REST API endpoint for inference
6. Visualize metrics and download evaluation reports

---

## 🏆 Certifications

- IBM SkillsBuild: **watsonx.ai Agent Lab**
- IBM: **AI Lifecycle & Deployment on Cloud**
- Edunet Foundation: **Cybersecurity Internship Completion Certificate**

---

## 🧠 Future Enhancements

- Integration with real-time packet capture (PCAP)
- Deep learning upgrade (CNN-LSTM hybrid model)
- Web-based dashboard for intrusion alerts
- Support for encrypted traffic analysis

---

## 👩‍💻 Credits

**Tamilkumar P**, CSE(Cyber Security) – J.J College Of Engineering And Technology
**Internship**: Cybernaut Programming Intern | IBM SkillsBuild | Edunet Foundation  
**Tools Used**: Python, IBM Watson, watsonx.ai, AutoAI, sklearn, seaborn
