# ⚔️ Network Intrusion Detection System (NIDS) using IBM watsonx.ai

A machine learning-powered solution for detecting and classifying network intrusions in real-time using IBM watsonx.ai. This system utilizes supervised learning techniques to identify various types of network attacks based on structured traffic data.

---

## 📚 Project Objective

Build an intelligent **Network Intrusion Detection System** that can detect and classify network activity as either **normal** or **attack** (DoS, Probe, R2L, U2R) with high accuracy and low false positives using machine learning models trained in IBM watsonx.ai.

---

## 🔗 Dataset

**Source**: [NSL-KDD Dataset on Kaggle](https://www.kaggle.com/datasets/ghazouaniabdellatif/nslkdd)  
- Improved version of the KDD Cup 1999 dataset  
- Includes pre-split Train and Test sets  
- Labeled for multiclass classification

---

## 🛠️ Technology Stack

- **Platform**: IBM watsonx.ai Studio
- **Environment**: Jupyter Notebooks (Manual + AutoAI)
- **Modeling Tools**: sklearn, pandas, seaborn, matplotlib
- **Deployment**: IBM Cloud Lite (REST API)
- **Cloud Regions**: Chennai 🇮🇳, Sydney 🇦🇺
- **Additional Tools**: watsonx.ai Agent Lab, Watson Pipelines, AutoAI

---

## ⚙️ Features

- Classifies traffic as: `Normal`, `DoS`, `Probe`, `R2L`, `U2R`
- Label encoding and feature scaling pipeline
- Train/Test split and evaluation metrics
- Random Forest feature importance analysis
- Confusion matrix and classification report visualizations
- Model deployment with accessible REST API endpoint
- AutoAI pipeline integration with tunable hyperparameters

---

## 🚀 Setup Instructions

1. **Login to IBM Cloud**: [https://cloud.ibm.com](https://cloud.ibm.com)
2. Launch **watsonx.ai Studio** → Create a new project
3. Upload the dataset (`KDDTrain+`, `KDDTest+`) and `notebook.ipynb`
4. Use **AutoAI** or manual pipeline to train the model
5. Evaluate and deploy the model via **Watson ML Deployment**
6. Access the API endpoint for real-time intrusion detection
7. Optionally, visualize results and download evaluation reports

---

## 📊 Model Evaluation

- Accuracy: ~90%+
- Precision, Recall, F1-Score: Varies by attack category
- Confusion matrix analysis for model behavior
- Feature importance chart using Random Forest

---

## 🧠 Future Enhancements

- Real-time packet stream integration (PCAP)
- CNN-LSTM hybrid for sequential deep learning
- Interactive web dashboard with live alerts
- Support for encrypted (TLS/SSL) traffic analysis

---

## 🏅 Certifications

- 🎓 **IBM SkillsBuild** – watsonx.ai Agent Lab (Verified)
- 🧠 **IBM** – AI Lifecycle Management on IBM Cloud

---

## 👨‍💻 Author

**Tamilkumar P**  
CSE (Cyber Security), J.J College Of Engineering And Technology  
Intern | IBM SkillsBuild x Edunet Foundation  


---


## ⭐ Acknowledgements

- IBM watsonx.ai Team  
- Edunet Foundation  
- NSL-KDD Dataset Authors  

