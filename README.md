# 💧 AquaSense — Smart Water Leakage Detection & Monitoring System

> **An IoT-based smart water pipeline monitoring system for detecting leaks, tracking water flow, monitoring pressure, and providing actionable insights through a modern web dashboard.**

AquaSense is a **Smart Water Leakage Detection & Predictive Monitoring System** developed as a Project-Based Learning (PBL) project.

The system combines **IoT sensors, real-time monitoring, data visualization, and intelligent anomaly detection** to help identify abnormal water usage and potential pipeline leakage.

---

## 🚀 Project Overview

Water leakage is one of the major causes of water wastage in residential buildings, societies, and pipeline networks. Traditional leakage detection methods often depend on manual inspection, which can result in delayed detection and unnecessary water loss.

**AquaSense** aims to provide a smarter approach by continuously monitoring pipeline parameters such as:

* 💧 Water Flow Rate
* 📊 Pipeline Pressure
* 🚰 Water Usage
* ⚠️ Leakage Conditions
* 📈 Historical Sensor Data
* 🔔 Abnormal Activity & Alerts

The collected sensor data can be visualized through an interactive dashboard, allowing users to monitor the health of the water pipeline system.

---

## ✨ Key Features

### 📊 Real-Time Dashboard

A centralized dashboard provides an overview of the complete water pipeline system.

It includes:

* Current flow rate
* Pipeline pressure
* Water consumption
* Leakage status
* System health
* Recent alerts

### 💧 Live Monitoring

Monitor pipeline parameters in real time and observe changes in:

* Flow rate
* Pressure
* Water consumption
* Leakage conditions

### 🕐 Historical Data

View previously recorded sensor data to identify:

* Usage patterns
* Abnormal readings
* Sudden pressure drops
* Unusual flow behavior
* Potential leakage events

### ⚠️ Leakage Detection

The system analyzes flow and pressure readings to identify unusual patterns that may indicate a pipeline leak.

Potential leakage events can be presented through visual alerts on the dashboard.

### 📈 Data Visualization

Interactive charts make it easier to understand pipeline behavior over time.

The dashboard provides visualizations for:

* Flow Rate
* Pipeline Pressure
* Water Usage
* Sensor Performance

### 🔔 Alert System

The system can highlight abnormal pipeline conditions and provide alerts when readings exceed defined thresholds or unusual patterns are detected.

---

## 🏗️ System Architecture

```text
┌──────────────────────┐
│      Water Pipe      │
└──────────┬───────────┘
           │
           ▼
┌──────────────────────┐
│   Flow Sensor        │
│   Pressure Sensor    │
└──────────┬───────────┘
           │
           ▼
┌──────────────────────┐
│       ESP32          │
│  Data Acquisition    │
└──────────┬───────────┘
           │
           │ Wi-Fi
           ▼
┌──────────────────────┐
│   Cloud / Backend    │
│   Data Processing    │
└──────────┬───────────┘
           │
           ▼
┌──────────────────────┐
│     AquaSense        │
│   Web Dashboard      │
└──────────┬───────────┘
           │
           ▼
┌──────────────────────┐
│ Monitoring & Alerts  │
│ Analytics & Reports  │
└──────────────────────┘
```

---

## 🖥️ Dashboard

The AquaSense dashboard is designed to provide a clean and intuitive monitoring experience.

### Main Sections

* **Dashboard** — System overview and key metrics
* **Live Monitoring** — Real-time pipeline data
* **Pipeline Network** — Pipeline infrastructure overview
* **Alerts** — Leakage and abnormal-condition alerts
* **Analytics** — Data analysis and trends
* **Sensor Performance** — Sensor monitoring
* **Reports** — Historical and system reports
* **Settings** — Application configuration

---

## 🛠️ Technology Stack

### Frontend

| Technology   | Purpose                     |
| ------------ | --------------------------- |
| React        | Frontend application        |
| Vite         | Development & build tooling |
| Recharts     | Data visualization          |
| Lucide React | Icons                       |
| JavaScript   | Application logic           |
| CSS          | UI styling                  |

The current repository is configured as a React + Vite application and includes React, Recharts, and Lucide React dependencies.

### Hardware

The prototype is designed around:

* **ESP32 DevKit V1**
* **YF-S201 Water Flow Sensor**
* **0–0.5 MPa Pressure Sensor**
* **12V DC Water Pump**
* **12V 2A Adapter**
* **5V 1-Channel Relay**
* **Breadboard**
* **Jumper Wires**
* **USB Cable**

### Planned / Extended Technologies

* IoT connectivity
* Cloud data storage
* Real-time sensor communication
* Anomaly detection
* Predictive monitoring

---

## 📁 Project Structure

```text
PBL/
│
├── public/
│
├── src/
│   ├── components/
│   ├── pages/
│   ├── assets/
│   └── ...
│
├── index.html
├── package.json
├── package-lock.json
├── vite.config.js
├── eslint.config.js
├── .gitignore
└── README.md
```

> The exact source structure may evolve as new dashboard modules and IoT functionality are added.

---

## ⚙️ Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/omkailasmore/PBL.git
```

### 2. Navigate to the Project

```bash
cd PBL
```

### 3. Install Dependencies

```bash
npm install
```

### 4. Start the Development Server

```bash
npm run dev
```

The Vite development server will provide a local URL, typically:

```text
http://localhost:5173
```

### 5. Build for Production

```bash
npm run build
```

### 6. Preview Production Build

```bash
npm run preview
```

### 7. Run ESLint

```bash
npm run lint
```

These commands correspond to the scripts currently defined in the repository's `package.json`.

---

## 🔮 Future Scope

AquaSense can be extended with several advanced capabilities:

* 🤖 AI-based leakage prediction
* 📡 Real-time ESP32 connectivity
* ☁️ Cloud-based sensor data storage
* 📱 Mobile application
* 🗺️ Pipeline network visualization
* 📊 Advanced analytics
* 🔔 SMS / Email notifications
* 🧠 Machine-learning-based anomaly detection
* 💰 Water wastage and cost estimation
* 🏢 Multi-building / multi-pipeline monitoring
* 📄 Automated reports

---

## 🎯 Objectives

The primary objectives of AquaSense are:

1. Detect water leakage at an early stage.
2. Reduce unnecessary water wastage.
3. Monitor pipeline flow and pressure continuously.
4. Provide an easy-to-understand monitoring interface.
5. Store and analyze historical pipeline data.
6. Enable data-driven maintenance decisions.
7. Explore predictive monitoring using AI/ML techniques.

---

## 📌 Project Status

**🚧 Under Development**

AquaSense is currently being developed as a PBL project. The frontend dashboard and monitoring interface are being built first, with hardware integration, real-time communication, and intelligent leakage detection planned as the project progresses.

---

## 📷 Screenshots

Screenshots of the AquaSense dashboard will be added here as the interface develops.

```text
Dashboard
├── System Overview
├── Live Sensor Data
├── Flow Rate Graph
├── Pipeline Pressure Graph
├── Water Usage
└── Leakage Alerts
```

---

## 🤝 Contributing

This project is currently maintained as an academic PBL project.

Suggestions, improvements, and technical contributions are welcome.

1. Fork the repository
2. Create a new branch

```bash
git checkout -b feature/your-feature
```

3. Commit your changes

```bash
git commit -m "Add: your feature"
```

4. Push the branch

```bash
git push origin feature/your-feature
```

5. Open a Pull Request

---

## 📄 License

This project is developed for **academic and educational purposes**.

---

## ⭐ Support

If you find the project interesting, consider giving the repository a ⭐ on GitHub.

**Repository:**
https://github.com/omkailasmore/PBL

---

### 💧 AquaSense

**Smart monitoring. Early detection. Less water wasted.**
