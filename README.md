# 🚀 5G Real-Time Anomaly Detection System

A production-grade AI pipeline that detects network anomalies in real-time using Isolation Forest and stream processing.

## 🏗️ Architecture
Simulator → Kafka → Spark → Isolation Forest → InfluxDB → Grafana

## 🛠️ Tech Stack
- Apache Spark (PySpark) — Stream Processing
- Apache Kafka — Message Broker
- Isolation Forest (scikit-learn) — ML Model
- InfluxDB 2.7 — Time-Series Database
- Grafana — Real-Time Dashboard
- Docker + Docker Compose — Infrastructure

## 🚀 Quick Start
1. Start infrastructure: docker-compose up -d
2. Run notebooks in order (1 → 2 → 3)
3. Open Grafana at http://localhost:3000
