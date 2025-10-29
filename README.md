#  Projects Portfolio

A collection of my major software engineering projects showcasing full-stack, distributed systems, and AI-driven application design. Each project link includes source code, architecture notes, and setup instructions.

---

##  AI-Powered Fitness Microservices Platform
**Stack:** Spring Boot • RabbitMQ • Keycloak • React (Vite + MUI) • MongoDB • Gemini-compatible LLM  
**Description:**  
Cloud-native fitness tracking and recommendation platform. Captures user activity events, publishes them via RabbitMQ, and generates AI-driven recommendations.  
- Event-driven architecture with async ingestion and structured recommendation generation.  
- Spring Cloud Gateway with OAuth2 resource-server enforcement and Keycloak-based identity sync.  
- React SPA using PKCE OAuth2 flow and centralized config-server for reproducible local setup.  

🔗 [Repository](https://github.com/yourusername/fitness-microservices)

---

##  Distributed eCommerce Platform
**Stack:** Next.js • Node.js • Kafka • Redis • PostgreSQL • MongoDB  
**Description:**  
Full-stack eCommerce system built with event-driven microservices. Designed a Kafka-based backend to decouple workflows, reducing latency by ~46% and redundant DB reads by ~30%. Integrated Clerk auth, Stripe payments, and transactional pipelines.  

🔗 [Repository](https://github.com/yourusername/ecommerce-platform)

---

##  Real-Time Financial Data Streaming System
**Stack:** Apache Kafka • AWS EC2/S3 • Python  
**Description:**  
Real-time data pipeline for financial datasets. Streams historical market data into Kafka topics for event-driven processing and persists to AWS S3 for durable cloud analytics. Includes automated Kafka deployment scripts and an EC2 operational runbook.  

🔗 [Repository](https://github.com/yourusername/financial-data-pipeline)

---

## 🔗 Summary Links
- [Distributed eCommerce Platform](https://github.com/yourusername/ecommerce-platform)  
- [Intelligent Document QA Platform](https://github.com/yourusername/document-qa-platform)  
- [Real-Time Financial Data Streaming System](https://github.com/yourusername/financial-data-pipeline)  
- [AI-Powered Fitness Microservices Platform](https://github.com/yourusername/fitness-microservices)
