# FastAPI Demo Project

🚗 A **Machine Learning based API** to predict the selling price of used cars based on their various features.

---

## 📦 Project Features

- 🔐 **Secure Authentication** – JWT token-based authentication with API key validation
- 🧠 **Smart ML Predictions** – Pre-trained model for accurate used car price estimation
- ⚡ **High-Speed Caching** – Redis-powered cache to skip repeated computations
- 📈 **Built-in Monitoring** – Prometheus metrics with Grafana dashboards
- 🐳 **Fully Dockerized** – Hassle-free setup using Docker Compose
- ☁️ **Cloud-Ready Deployment** – One-click deployable on [Render](https://render.com)

---

## 🧠 Model Input Variables

The prediction model expects the following input features:

| Feature         | Description                 | Example        |
| --------------- | --------------------------- | -------------- |
| `company`       | Brand of the car            | `"Maruti"`     |
| `year`          | Year of manufacturing       | `2015`         |
| `owner`         | Number of previous owners   | `"Second"`     |
| `fuel`          | Fuel type                   | `"Petrol"`     |
| `seller_type`   | Individual or Dealer        | `"Individual"` |
| `transmission`  | Transmission type           | `"Automatic"`  |
| `km_driven`     | Kilometers driven           | `200000`       |
| `mileage_mpg`   | Mileage in miles per gallon | `55`           |
| `engine_cc`     | Engine capacity in cc       | `1250`         |
| `max_power_bhp` | Maximum power in BHP        | `80`           |
| `torque_nm`     | Torque in Newton meters     | `200`          |
| `seats`         | Number of seats             | `5`            |

---

## 🚀 Getting Started (Local)

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/fastapi-project.git
cd fastapi-project
```

### 2. Set Environment Variables

```bash
API_KEY=demo-key
JWT_SECRET_KEY=your-secret
REDIS_URL=redis://localhost:6379
```

### 3. Build and Run via Docker

```bash
docker-compose up --build
```

### 4. Access Interfaces

- FastAPI Docs: http://localhost:8000/docs
- FastAPI Metrics: http://localhost:8000/metrics
- Prometheus UI: http://localhost:9090
- Grafana UI: http://localhost:3000

---

## 🚀 Deployment on Render (API only)

1. Push code to GitHub
2. Add render.yaml to the project root
3. Create a new Web Service on Render
4. Include environment variables

---

Test the Live Deployed API on **Render** - [FastAPI Deployed API](fastapi-ml-project.onrender.com/docs)

---

# **_Thank You_**
