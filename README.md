# Intelligent Traceroute: Identifying Latency & IP Anomalies

![Banner](https://github.com/sarthakpriyadarshi/Traceroute-Based-Network-Mapping-and-Visualization/blob/main/images/banner.png?raw=true)

## 📌 Overview
Intelligent Traceroute is a network mapping and anomaly detection system designed to identify suspicious IP addresses and latency spikes in network paths. The project leverages modern technologies to provide an efficient and intelligent network monitoring solution.

### **Key Features**
- **AI-Powered Anomaly Detection**: Uses **Isolation Forest** to identify abnormal network behavior.
- **Cross-Platform Support**: Works on **Windows, Linux, and macOS**.
- **Real-Time Traceroute Analysis**: Performs **traceroute (Linux/macOS)** or **tracert (Windows)** to analyze network hops.
- **JSON Output**: Provides structured data for easy integration.
- **Secure API Communication**: Uses **FastAPI with CORS Middleware**.
- **User-Friendly Web Interface**: Frontend built with modern web technologies.

##  Deployment
The project is deployed and available at:
🔗 **[Traceroute (Vercel)](https://traceroute.cyberol.codes/)**

## 🛠️ Tech Stack
- **Backend:** FastAPI, Python, NumPy, Scikit-learn
- **Frontend:** JavaScript, React, TailwindCSS
- **Networking Tools:** Traceroute, Tracert
- **Deployment:** Vercel (Frontend), Python (Backend)

## Installation & Setup
### **Clone the Repository**
```sh
git clone https://github.com/Yusuf611/Traceroute-Visualization.git
cd Traceroute-Visualization
```

### **Backend Setup**
```sh
cd backend
pip install -r requirements.txt
python app/main.py
```
_Backend will run on `http://localhost:8000`_

### **Frontend Setup**
```sh
cd frontend
npm install
npm run build
npm start dev
```
_Frontend will run on `http://localhost:3000`_

## How It Works
1. User enters a URL/IP in the web interface.
2. The backend executes **traceroute/tracert** to collect network path data.
3. AI model processes the data to detect anomalies.
