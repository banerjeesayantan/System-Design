# 🚀 SYSTEM DESIGN: COMPLETE STUDY & PRACTICE ROADMAP
**(Industry-standard | Real-world focused | Interview-ready)**

---

## 🧭 How to Use This Repo

For each topic:

1. 📺 **Watch** (YouTube)  
2. 📖 **Read** (Book / Blog)  
3. 🛠 **Practice** (Implement a system)  
4. 📝 **Document trade-offs** in this repo  

---

## 🏗 CLAN 1: Architecture Foundations
**Topics to Study**  
- Client–Server, 3-Tier  
- Monolith, Modular Monolith  
- Microservices  
- Serverless  
- Event-Driven  
- Distributed Systems  
- Cloud-Native Architecture  

**YouTube Links**  
- [ByteByteGo – System Architecture Basics](https://www.youtube.com/watch?v=7G1Wz9aZK4k)  
- [Gaurav Sen – Monolith vs Microservices](https://www.youtube.com/watch?v=4uKpJ1y6GxY)  

**Books**  
- [Building Microservices – Sam Newman](https://www.amazon.in/Building-Microservices-Sam-Newman/dp/1491950358/)  
- [Software Architecture: The Hard Parts – Ford et al.](https://www.amazon.in/Software-Architecture-Hard-Parts-Practical/dp/0321880689/)  

**Practice Projects**  
- Design a Monolith → Microservices migration  
- Event-Driven Order Processing System  

---

## 📈 CLAN 2: Scaling & Growth
**Topics to Study**  
- Vertical & Horizontal Scaling  
- Auto-Scaling  
- Stateless vs Stateful Services  
- Capacity Planning  

**YouTube Links**  
- [Gaurav Sen – Scaling Systems](https://www.youtube.com/watch?v=9b3m2r1m0g0)  
- [ByteByteGo – Scaling to Millions](https://www.youtube.com/@ByteByteGo)  

**Books**  
- [Designing Data-Intensive Applications – Martin Kleppmann (Ch 1–3)](https://www.amazon.in/Designing-Data-Intensive-Applications-Reliable-Maintainable/dp/9352135245/)  

**Practice Projects**  
- Scale URL Shortener from 1K → 100M users  
- Estimate traffic & capacity for Twitter-like system  

---

## 🌐 CLAN 3: Traffic Management
**Topics to Study**  
- Load Balancer, Reverse Proxy  
- API Gateway, DNS, CDN  
- Rate Limiting, Throttling, DDoS Protection  

**YouTube Links**  
- [ByteByteGo – Load Balancer & CDN](https://www.youtube.com/@ByteByteGo)  
- [Gaurav Sen – Rate Limiter Deep Dive](https://www.youtube.com/@GauravSen)  

**Books**  
- [System Design Interview – Alex Xu Vol 1](https://www.amazon.com/System-Design-Interview-insiders-Guide/dp/1736049119/)  

**Practice Projects**  
- Design API Gateway + Rate Limiter  
- Design Global CDN-based website  

---

## 🗄 CLAN 4: Data Storage & Databases
**Topics to Study**  
- SQL Databases, NoSQL Databases  
- Sharding, Partitioning, Replication  
- Indexing, Query Optimization, Read Replicas  
- Backups, Data Consistency Models  

**YouTube Links**  
- [ByteByteGo – SQL vs NoSQL](https://www.youtube.com/@ByteByteGo)  
- [Gaurav Sen – Sharding vs Replication](https://www.youtube.com/@GauravSen)  

**Books**  
- [Designing Data-Intensive Applications – Martin Kleppmann](https://www.amazon.in/Designing-Data-Intensive-Applications-Reliable-Maintainable/dp/9352135245/)  

**Practice Projects**  
- Design User DB for 100M users  
- Design Distributed Key-Value Store  

---

## ⚡ CLAN 5: Caching & Performance
**Topics to Study**  
- Client & Server-Side Caching  
- CDN Caching, Redis, Memcached  
- Cache Invalidation, Write-Through, Write-Back  

**YouTube Links**  
- [ByteByteGo – Caching Strategies](https://www.youtube.com/@ByteByteGo)  
- [Redis Explained – Gaurav Sen](https://www.youtube.com/@GauravSen)  

**Books**  
- [Designing Data-Intensive Applications – Caching Chapters](https://www.amazon.in/Designing-Data-Intensive-Applications-Reliable-Maintainable/dp/9352135245/)  

**Practice Projects**  
- Redis-based cache for feeds  
- LRU Cache implementation  

---

## 🔌 CLAN 6: Communication & APIs
**Topics to Study**  
- REST APIs, gRPC, GraphQL, WebSockets  
- Long Polling, API Versioning, Serialization (JSON/Protobuf)  

**YouTube Links**  
- [ByteByteGo – REST vs gRPC](https://www.youtube.com/@ByteByteGo)  

**Books**  
- [API Design Patterns – JJ Geewax](https://www.amazon.in/API-Design-Patterns-JJ-Geewax/dp/1492052586/)  

**Practice Projects**  
- Design Chat API  
- Public REST API with versioning  

---

## 📨 CLAN 7: Async Processing & Messaging
**Topics to Study**  
- Message Queues, Kafka, RabbitMQ, Pub/Sub  
- Event Streaming, Background Jobs, Task Scheduling  

**YouTube Links**  
- [ByteByteGo – Kafka Architecture](https://www.youtube.com/@ByteByteGo)  
- [Gaurav Sen – Messaging Systems](https://www.youtube.com/@GauravSen)  

**Books**  
- [Kafka: The Definitive Guide](https://www.amazon.in/Kafka-Definitive-Guide-Real-Time-Stream/dp/1491936169/)  

**Practice Projects**  
- Notification System  
- Event streaming for orders  

---

## 🔐 CLAN 8: Security
**Topics to Study**  
- HTTPS/TLS, Authentication, Authorization  
- JWT, OAuth2, RBAC, ABAC  
- Encryption, Secrets Management, WAF, Zero Trust  

**YouTube Links**  
- [ByteByteGo – JWT & Auth](https://www.youtube.com/@ByteByteGo)  
- [OAuth2 Explained](https://www.youtube.com/@GauravSen)  

**Books**  
- [Web Application Security – Andrew Hoffman](https://www.amazon.in/Web-Application-Security-Exploitation-Prevention/dp/1492053117/)  

**Practice Projects**  
- Secure Auth System  
- RBAC for admin panel  

---

## 🛡 CLAN 9: Reliability & Availability
**Topics to Study**  
- High Availability, Fault Tolerance  
- Failover, Circuit Breaker, Retry & Backoff  
- Disaster Recovery  

**YouTube Links**  
- [Gaurav Sen – Why Systems Fail](https://www.youtube.com/@GauravSen)  
- [ByteByteGo – High Availability](https://www.youtube.com/@ByteByteGo)  

**Books**  
- [Site Reliability Engineering – Google](https://sre.google/sre-book/table-of-contents/)  

**Practice Projects**  
- HA Payment System  
- Add failover to previous designs  

---

## 🔭 CLAN 10: Observability
**Topics to Study**  
- Logging, Metrics, Monitoring, Alerting  
- Distributed Tracing, Prometheus, Grafana, OpenTelemetry  

**YouTube Links**  
- [ByteByteGo – Observability](https://www.youtube.com/@ByteByteGo)  

**Books**  
- [Observability Engineering – Charity Majors](https://www.amazon.in/Observability-Engineering-Charity-Majors/dp/1098106229/)  

**Practice Projects**  
- Add monitoring + alerting to a system  

---

## 🚢 CLAN 11: DevOps & Deployment
**Topics to Study**  
- CI/CD, Docker, Kubernetes  
- Container Orchestration, Terraform  
- Blue-Green Deployment, Canary, Rollbacks  

**YouTube Links**  
- [TechWorld with Nana – Docker/K8s](https://www.youtube.com/@TechWorldwithNana)  
- [ByteByteGo – Deployment](https://www.youtube.com/@ByteByteGo)  

**Books**  
- [The DevOps Handbook](https://www.amazon.in/DevOps-Handbook-World-Class-Reliability-Organizations/dp/1942788002/)  

**Practice Projects**  
- Deploy Microservices with Docker & K8s  
- Setup CI/CD pipeline  

---

## 🧠 CLAN 12: Advanced Patterns
**Topics to Study**  
- CAP Theorem, ACID vs BASE, Eventual Consistency  
- CQRS, Event Sourcing, Saga Pattern  
- Idempotency, Load Shedding, Queue-Based Load Leveling  

**YouTube Links**  
- [Gaurav Sen – CAP & Consistency](https://www.youtube.com/@GauravSen)  
- [ByteByteGo – CQRS & Saga](https://www.youtube.com/@ByteByteGo)  

**Books**  
- [Microservices Patterns – Chris Richardson](https://www.amazon.in/Microservices-Patterns-Implementation-Management-Distributed/dp/1617294543/)  

**Practice Projects**  
- E-commerce System using Saga & CQRS  
- Design CQRS-based Order System  

---

## 🏆 Master Practice Projects (End-to-End)

- URL Shortener  
- Pastebin  
- WhatsApp / Chat App  
- Twitter Feed  
- Instagram  
- YouTube  
- Dropbox / Drive  
- Uber / Ola  
- Payment System  
- Notification System  
- Search Autocomplete  
- Rate Limiter  
- Web Crawler  
- Booking System  
- Stock Trading System  

> For each project: design **API, DB schema, scaling, bottlenecks, trade-offs**  

---

## 📚 Recommended Books (Industry Standard)

| Level | Book | Link |
|-------|------|------|
| Beginner | System Design Interview Vol 1 & 2 – Alex Xu | [Amazon](https://www.amazon.com/System-Design-Interview-insiders-Guide/dp/1736049119/) |
| Intermediate | Designing Data-Intensive Applications – Kleppmann | [Amazon](https://www.amazon.in/Designing-Data-Intensive-Applications-Reliable-Maintainable/dp/9352135245/) |
| Architecture | Building Microservices – Sam Newman | [Amazon](https://www.amazon.in/Building-Microservices-Sam-Newman/dp/1491950358/) |
| Patterns | Microservices Patterns – Chris Richardson | [Amazon](https://www.amazon.in/Microservices-Patterns-Implementation-Management-Distributed/dp/1617294543/) |
| Reliability | Site Reliability Engineering – Google | [SRE Book](https://sre.google/sre-book/table-of-contents/) |
| DevOps | The DevOps Handbook | [Amazon](https://www.amazon.in/DevOps-Handbook-World-Class-Reliability-Organizations/dp/1942788002/) |

---

## 🌟 Why Follow This Repo?

✔ Covers **what to study → how to study → practice**  
✔ Mirrors **real production systems**  
✔ Trusted by engineers preparing for **FAANG / Big Tech interviews**  
✔ Constantly evolving with **notes, YouTube & book references**  

---

**Happy Learning & Building Efficient, Scalable, and Reliable Systems! 🚀**
