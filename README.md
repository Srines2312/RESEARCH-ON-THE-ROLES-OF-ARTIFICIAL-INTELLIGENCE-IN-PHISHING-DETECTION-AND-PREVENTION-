# 🛡️ AI-Powered Phishing URL Detector
**Research on the Roles of Artificial Intelligence in Phishing Detection and Prevention**

![Python](https://img.shields.io/badge/Python-3.13-blue?style=for-the-badge&logo=python)
![Flask](https://img.shields.io/badge/Flask-2.2-white?style=for-the-badge&logo=flask)
![Machine Learning](https://img.shields.io/badge/ML-XGBoost-green?style=for-the-badge&logo=scikitlearn)
![Status](https://img.shields.io/badge/Status-Complete-success?style=for-the-badge)

> [cite_start]**"One of the most persistent cybersecurity dangers is phishing, which is becoming more sophisticated and frequent while evading traditional security safeguards."** [cite: 73]

## 🌟 Overview
[cite_start]Traditional security solutions, such as blacklists and heuristic-based filters, frequently fail to keep up with ever-evolving hacker strategies[cite: 150]. [cite_start]This project presents an intelligent, adaptive detection system that leverages **Machine Learning (XGBoost)** to analyze URL structures and identify malicious intent in real-time[cite: 190, 230].

### 🚀 Key Performance Highlights
* [cite_start]**High Training Accuracy:** Achieved approximately **98.6% accuracy** during the model training phase[cite: 946, 952].
* [cite_start]**Feature Engineering:** Utilizes a comprehensive set of **48 unique features**, covering lexical, structural, and behavioral markers[cite: 641, 730].
* [cite_start]**Real-Time Detection:** Features a functional **Flask Dashboard** for immediate URL classification and proactive threat monitoring[cite: 76, 730].

---

## 🛠️ Features
* [cite_start]**Granular URL Analysis:** Extracts critical data points such as IP address usage, URL length, and the presence of suspicious symbols like "@" or "-"[cite: 441, 442, 443].
* [cite_start]**In-Depth Security Scrutiny:** Evaluates SSL certificate usage, subdomain levels, and web-based triggers like iframes or JavaScript redirects[cite: 445, 447, 643].
* [cite_start]**Intuitive Dashboard:** A user-friendly web interface designed to provide immediate feedback on URL legitimacy for both technical and non-technical users[cite: 507, 716].
* [cite_start]**Adaptive Defense:** Unlike static blacklists, this AI-driven approach can analyze minute patterns and irregularities to identify new phishing threats[cite: 154, 156].

---

## 🏗️ System Architecture
[cite_start]The system utilizes a design science methodology focused on solving real-world problems through technological artifacts[cite: 410, 411]:

1.  [cite_start]**User Input:** Users enter a suspicious URL into the web-based dashboard[cite: 687].
2.  [cite_start]**Feature Extraction:** The backend performs real-time extraction of 48 security features[cite: 693, 813].
3.  [cite_start]**Model Prediction:** Extracted features are passed into a pre-trained **XGBoost model**[cite: 694, 695].
4.  [cite_start]**Result Display:** The dashboard returns the classification (Phishing vs. Legitimate) along with a confidence score[cite: 700, 702].

---

## 💻 Tech Stack
| Component | Technology | Purpose |
| :--- | :--- | :--- |
| **Language** | Python 3.13.3 | [cite_start]Core development [cite: 800] |
| **ML Framework** | XGBoost & Scikit-learn | [cite_start]Model training and evaluation [cite: 803] |
| **Web Backend** | Flask 2.2 | [cite_start]Hosting the dashboard and API [cite: 800] |
| **Data Parsing** | BeautifulSoup4, tldextract, re | [cite_start]Feature extraction from URLs [cite: 803] |
| **Environment** | VS Code & Anaconda | [cite_start]Development and dependency management [cite: 568, 803] |

---

## 🚦 Getting Started

### 📋 Prerequisites
Ensure you have Python installed. [cite_start]You will need the libraries listed in the `requirements.txt` file[cite: 1502]:
* `xgboost`
* `scikit-learn`
* `flask`
* `pandas`
* `beautifulsoup4`

### 🏃 Running the App
1.  [cite_start]**Clone the project** and navigate to the directory[cite: 1546, 1547].
2.  **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```
3.  [cite_start]**Run the Flask application**[cite: 1282]:
    ```bash
    py app.py
    ```
4.  **Access the Dashboard**: Open your browser and go to `http://127.0.0.1:5000/`[cite: 1292].

---

## 📊 Experimental Results
The system underwent rigorous testing to ensure reliability:
* [cite_start]**Functionality Testing:** Achieved **90% accuracy** (18/20 correct) during manual verification of diverse sample URLs[cite: 1113, 1161].
* [cite_start]**Large-Scale Evaluation:** Tested against 20,000 URLs, demonstrating effectiveness in identifying legitimate sites with high precision[cite: 1124, 1125].
* [cite_start]**Model Comparison:** XGBoost was selected over Logistic Regression, SVM, and Random Forest due to its superior balance of accuracy and speed[cite: 472, 563].

---

## 🎓 Author
[cite_start]**Srineswaran S/O Kanesh** [cite: 3]
[cite_start]Bachelor of Computer Science (Computer Security) with Honours [cite: 33]
[cite_start]**Universiti Teknikal Malaysia Melaka (UTeM)** [cite: 34]

**Supervisor:** TS. [cite_start]Mohd Nazrien Bin Zaraini [cite: 27]

---

## 📜 License
[cite_start]This project report was submitted in partial fulfillment of degree requirements and is the property of **Universiti Teknikal Malaysia Melaka**[cite: 11, 33].

---
*If this research helps your work, please consider giving it a ⭐!*
