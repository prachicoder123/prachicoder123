# AI-Based Network Monitoring and Intrusion Detection System

An AI-powered Intrusion Detection System (IDS) that monitors live network traffic and detects suspicious activities using Machine Learning. The system captures network packets, analyzes traffic patterns, predicts potential attacks, and displays alerts through a web dashboard.

## 🚀 Features

- Real-time network packet capture
- Live traffic monitoring
- AI-based attack detection
- Suspicious activity alerts
- Interactive Flask dashboard
- Traffic analysis and visualization
- Machine Learning using Random Forest

## 🛠️ Tech Stack

- Python
- Flask
- Scapy
- Pandas
- Scikit-learn
- Random Forest
- Matplotlib
- HTML, CSS
- NSL-KDD Dataset

## 📂 Project Structure

```
AI_IDS_Project/
│── app.py
│── packet_sniffer.py
│── traffic_analyzer.py
│── attack_detector.py
│── ml_model.py
│── alerts.py
│
├── data/
│   ├── traffic.csv
│   └── alerts.csv
│
├── model/
│   └── random_forest.pkl
│
├── templates/
│   ├── dashboard.html
│   └── alerts.html
│
├── static/
│   └── graphs/
│
└── requirements.txt
```

## ⚙️ Installation

1. Clone the repository

```bash
git clone https://github.com/your-username/AI_IDS_Project.git
```

2. Navigate to the project folder

```bash
cd AI_IDS_Project
```

3. Install dependencies

```bash
pip install -r requirements.txt
```

4. Run the application

```bash
python app.py
```

5. Open your browser and visit

```
http://127.0.0.1:5000
```

## 📊 How It Works

1. Captures live network packets using Scapy.
2. Extracts packet information such as source IP, destination IP, protocol, and packet size.
3. Stores traffic data for analysis.
4. Uses a trained Random Forest model to classify normal and malicious traffic.
5. Displays detected threats and network statistics on the Flask dashboard.

## 📁 Dataset

- NSL-KDD Dataset

## 📌 Future Improvements

- Deep Learning-based attack detection
- Real-time email notifications
- Multi-class attack classification
- Database integration
- Docker deployment
- Cloud deployment
- User authentication

## 👩‍💻 Author

**Prachi Khutarkar**

- Email: prachivk30@gmail.com
- LinkedIn: https://linkedin.com/in/prachi-khutarkar-6a402b2b7

## 📄 License

This project is created for educational and learning purposes.
