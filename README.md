# Shield--AI
# 🛡️ AI-Powered SOC Threat Detection & Monitoring System

## 🚀 Overview

A real-time Security Operations Center (SOC) simulation platform that visualizes network activity, detects threats using AI/ML models, and automates defensive responses.

This project demonstrates practical skills in **cybersecurity, threat intelligence, and machine learning** by simulating enterprise-grade defense systems.

---

## 🧠 Features

### 🔴 Real-Time Monitoring

* Interactive network map with 22 nodes (firewalls, servers, databases, IDS sensors)
* Live packet flow visualization
* Nodes pulse red when under attack

### 🕵️ Threat Actor Intelligence

* Tracks real-world APT groups:

  * APT-29
  * Lazarus
  * FIN7
  * Sandworm
  * APT-41
* Displays ML confidence scores, IoC counts, and activity status
* Color-coded threat severity levels

### 🤖 AI/ML Behavior Engine

* Anomaly detection timeline with dynamic threshold

* Ensemble ML models:

  * LSTM
  * Isolation Forest
  * Graph Neural Network
  * Autoencoder
  * XGBoost

* Metrics tracked:

  * Anomalies detected
  * ML-flagged events
  * Auto-blocked threats
  * Escalations

* Prediction engine:

  * Next attack vectors
  * Probability scores
  * Estimated attack time (ETA)

### 📡 Live Event Feed

* Real-time logs including:

  * C2 beacon detections
  * Lateral movement alerts
  * Payload blocking
  * Policy updates
* Fully timestamped for analysis

### 🛡️ Defense Controls

* Auto-block deployment
* Deep scan trigger
* Simulation pause/resume
* Exportable security reports

---

## 🛠️ Tech Stack

| Layer               | Technology                         |
| ------------------- | ---------------------------------- |
| Backend             | Python                             |
| Machine Learning    | Scikit-learn, TensorFlow / PyTorch |
| Packet Analysis     | Scapy, Wireshark                   |
| Logging             | Elasticsearch                      |
| Threat Intelligence | MITRE ATT&CK Framework             |
| Frontend            | React / FastAPI                    |

---

## 📷 Screenshots

(Add screenshots in a `screenshots/` folder)

```
![Dashboard](screenshots/dashboard.png)
![Network Map](screenshots/network.png)
```

---

## ⚙️ Installation

```bash
git clone https://github.com/your-username/soc-ai-monitoring.git
cd soc-ai-monitoring
pip install -r requirements.txt
python app.py
```

---

## 🎯 Use Cases

* SOC analyst training
* Threat detection research
* Cybersecurity portfolio project
* AI-driven security experimentation

---

## 📈 Future Improvements

* SIEM integration (Splunk, Wazuh)
* Real-time threat intelligence APIs
* Cloud deployment (AWS / GCP)
* Role-based access control (RBAC)

---

## 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first.

---

## 📜 License

MIT License

