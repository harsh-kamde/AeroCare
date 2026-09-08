# AeroCare: AI Aircraft Maintenance System ✈️🤖        

A production-oriented Generative AI application that analyzes aircraft flight sensor data and generates AI-powered maintenance recommendations using **Amazon Bedrock**. The application follows a cloud-native microservices architecture with **React**, **FastAPI**, **Docker**, **Kubernetes (Amazon EKS)**, and **GitHub Actions**.

<img width="1280" height="614" alt="image" src="https://github.com/user-attachments/assets/0d3536c3-b88d-4829-b454-f564251301a0" />

## 🚀 Features

- Upload aircraft flight sensor data (Excel)
- Engineering analytics and trend analysis
- Historical metric calculation
- AI-powered maintenance recommendations
- Flight readiness assessment
- Maintenance checklist generation
- Work order recommendations
- Modern responsive dashboard
- Containerized microservices
- Cloud-ready deployment architecture

---

## 🏗️ Architecture

```
Flight Sensor Data (Excel)
            │
            ▼
    Engineering Analytics
            │
            ▼
     Amazon Bedrock (LLM)
            │
            ▼
 AI Maintenance Recommendation
            │
            ▼
      React Dashboard
```

Deployment Architecture

```
User
 │
 ▼
Application Load Balancer
 │
 ▼
Amazon EKS Cluster
 ├── React Frontend
 └── FastAPI Backend
        │
        ▼
 Amazon Bedrock
```

---

## 🛠️ Tech Stack

### Frontend
- React 18
- Vite
- JavaScript
- CSS

### Backend
- FastAPI
- Python 3.12
- Pandas
- Boto3
- OpenPyXL

### AI
- Amazon Bedrock
- Amazon Nova Pro

### Cloud & DevOps
- AWS
- Docker
- Amazon EKS
- Amazon ECR
- Kubernetes
- GitHub Actions
- AWS CLI
- kubectl

---

## 📂 Project Structure

```
.
├── frontend/
│   ├── src/
│   ├── components/
│   ├── api/
│   ├── Dockerfile
│   └── package.json
│
├── backend/
│   ├── src/
│   ├── app.py
│   ├── Dockerfile
│   └── pyproject.toml
│
├── kubernetes/
│
├── .github/
│   └── workflows/
│
└── README.md
```

---

## ⚙️ Workflow

1. Upload aircraft telemetry data
2. Validate and process Excel data
3. Calculate engineering analytics
4. Generate historical metrics
5. Send analytics to Amazon Bedrock
6. Generate AI maintenance recommendations
7. Display results on the dashboard

---

## 📊 Engineering Analytics

The application computes:

- Historical Average
- Historical Median
- Standard Deviation
- Trend Analysis
- Percentage Change
- Threshold Comparison
- Flight Readiness Indicators

---

## 🤖 AI Capabilities

Using Amazon Bedrock, the system generates:

- Aircraft Health Status
- Maintenance Recommendations
- Risk Assessment
- Inspection Checklist
- Work Order
- Fly / No-Fly Decision

---

## 🐳 Deployment

- Dockerized Frontend
- Dockerized Backend
- Amazon ECR Image Registry
- Amazon EKS Deployment
- Kubernetes Services
- Application Load Balancer
- GitHub Actions CI/CD

---

## 📸 Dashboard

The dashboard provides:

- Flight Analytics
- Engineering Metrics
- Trend Visualization
- Risk Indicators
- AI Recommendations
- Maintenance Checklist
- Flight Readiness Status

---

## 🔮 Future Improvements

- User Authentication
- Role-Based Access Control (RBAC)
- Real-time Flight Data
- Multi-Aircraft Support
- Monitoring & Logging
- Auto Scaling
- LLM Guardrails
- Cost Optimization
- Observability

---

## 👨‍💻 Author

**Harsh Kamde**

---

## ⭐ If you found this project useful, consider giving it a star!
