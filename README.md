# Scalable E-Commerce Microservices Platform 🛒

A production-ready e-commerce backend system built using microservices architecture. Designed for scalability, modularity, and performance — perfect for real-world deployment and portfolio showcase.

## 🧠 Key Features

- **Microservices Architecture**: Auth, Product, Order, and Payment services
- **RESTful APIs**: Built with Express.js
- **MongoDB**: NoSQL storage for each microservice
- **RabbitMQ**: Message broker for async service communication
- **NGINX**: Acts as reverse proxy and API Gateway
- **Dockerized**: Each service containerized with Docker & managed via Compose
- **AWS EC2 Ready**: Deployment-ready for cloud environments

## 🛠 Tech Stack

- **Backend**: Node.js, Express.js
- **Database**: MongoDB, Mongoose
- **Messaging**: RabbitMQ (AMQP)
- **Infrastructure**: Docker, Docker Compose
- **Proxy/Gateway**: NGINX
- **Cloud Deployment**: AWS EC2
- **Optional**: Redis, Stripe, Prometheus/Grafana

## 📦 Microservices Overview

| Service   | Description                          |
|-----------|--------------------------------------|
| Auth      | User signup/login, JWT authentication |
| Product   | Product catalog & inventory management |
| Order     | Place orders, track history           |
| Payment   | Simulated payment processing (Stripe/PayPal ready) |

## 🚀 Getting Started

```bash
# Clone the repo
git clone https://github.com/prathamesh-git9/ecommerce-microservices.git

# Navigate into the folder
cd ecommerce-microservices

# Spin up all services
docker-compose up --build
