# Hi, I'm Pranshu 👋

Platform Engineer at [Leegality](https://leegality.com) · Building at the intersection of cloud infrastructure, distributed systems, and developer tooling.

Career switcher. Physics grad. Former teacher. Now I architect systems for a living — and I love every bit of it.

---

## 🔧 What I Work With

**Cloud & Infrastructure**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonaws&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)

**Backend & Data**

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=springboot&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=flat&logo=apachekafka&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat&logo=elasticsearch&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)

**CI/CD & DevSecOps**

![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat&logo=jenkins&logoColor=white)
![GitLab](https://img.shields.io/badge/GitLab-FC6D26?style=flat&logo=gitlab&logoColor=white)
![CycloneDX](https://img.shields.io/badge/CycloneDX-0057A8?style=flat)
![Dependency Track](https://img.shields.io/badge/Dependency_Track-4A90D9?style=flat)

**Frontend**

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)

---

## 🏆 Certifications

| Certification | Issued |
|---|---|
| ☁️ AWS Certified Solutions Architect – Associate | Sep 2023 |
| ☁️ AWS Certified Developer – Associate | Oct 2023 |
| ☁️ AWS Certified SysOps Administrator – Associate | Nov 2023 |
| 🚢 CKA / CKAD / CKS *(in progress)* | 2026 |

---

## 🚀 Projects

### [CueCoLab](https://github.com/PranshuBarar/CueCoLab-Backend) — Collaborative Video Platform (SaaS)
A full-stack SaaS platform for content creators to collaborate on videos before publishing.

**What's under the hood:**
- HLS video streaming via AWS CloudFront signed URLs
- Async video transcoding pipeline: S3 → EventBridge → Lambda → SQS → ECS Fargate (ffmpeg)
- YouTube Data API v3 OAuth2 integration for direct channel uploads
- JWT + Google OAuth2 auth, Spring Security, SSE for real-time updates
- Full AWS infra: ECS Fargate, RDS, DynamoDB, SQS, CloudFront, Secrets Manager

`Java` `Spring Boot` `Next.js` `AWS ECS` `S3` `CloudFront` `SQS` `EventBridge` `Lambda` `DynamoDB`

---

### [Leegality Search Optimization](https://github.com/PranshuBarar/Search-Optimization-Architecture-V2) — Real-Time CDC Search Pipeline
Designed and implemented a real-time data synchronization architecture from MySQL to Elasticsearch using Change Data Capture.

**The problem solved:**
- Iterated from an initial [polling-based V1 architecture](https://github.com/PranshuBarar/Search-Optimization-Architecture) to this final event-driven V2.
- MySQL full-text search: ~34 seconds per query
- Elasticsearch (after migration): 400–500ms (cached: 50ms)
- 68× performance improvement at 10,000 concurrent users (JMeter tested)

**Architecture:**
- Debezium Source Connector reads MySQL binlog (CDC)
- Kafka topics per table (zero custom consumer code)
- Elasticsearch Sink Connectors write directly to indices
- Dynamic recursive Elasticsearch DSL query builder

`Debezium` `Apache Kafka` `Kafka Connect` `Elasticsearch` `MySQL` `Docker Compose` `JMeter`

---

## 🌱 Currently

- Going deep on Kubernetes — unwrapping it to bare Linux primitives (namespaces, cgroups, eBPF, CNI)
- Preparing for CKA → CKAD → CKS
- Exploring OpenTelemetry and observability tooling

---

## 📫 Let's Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/pranshubarar)
[![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?style=flat&logo=twitter&logoColor=white)](https://twitter.com/PranshuBarar1)
