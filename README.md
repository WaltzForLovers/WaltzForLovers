<div align="center">

# Anton Smyslov

**Backend & ML Engineer · Go · Python**

[![Email](https://img.shields.io/badge/Email-waltzforlovers%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:waltzforlovers@gmail.com)
[![Telegram](https://img.shields.io/badge/Telegram-waltzforlovers-2CA5E0?style=flat-square&logo=telegram&logoColor=white)](https://t.me/waltzforlovers)
![Open to work](https://img.shields.io/badge/Open_to_work-remote_·_relocation-00B37E?style=flat-square)

</div>

---

## About

I am a backend and ML engineer. I write production services in **Go** and **Python**, and I use **Rust** when the problem needs it — performance-critical or systems-level parts, not as a default.

On the backend I build APIs and data-heavy services: PostgreSQL, Redis, Kafka, RabbitMQ, gRPC, Docker, Kubernetes, with Prometheus and Grafana for observability.

On the ML side I work in **computer vision** and **NLP**: training and inference pipelines, retrieval, and grounding model output in source documents.

I am an MSc student at Saratov State University. My research is multi-agent visual analysis of anomalies in multivariate time series. My undergraduate thesis is a RAG system for question answering over company documentation.

Open to remote roles and relocation.

---

## Stack

**Languages**

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)

**Backend**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-244c5a?style=flat-square&logo=grpc&logoColor=white)

**Infra**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)

**Observability**

![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)

**ML · CV & NLP**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat-square&logo=qdrant&logoColor=white)

---

## Education

### MSc — Saratov State University *(in progress)*

**Thesis:** Multi-agent visual analysis of anomalies in multivariate time series

Multivariate time series are several aligned signals recorded over time — sensors, metrics, industrial or operational channels. A point that looks normal on one series can be an anomaly when all series are read together.

The work is not a single detector with one score. Several cooperating analysis agents look at the same window from different angles (detection, comparison across channels, explanation). Visual analysis is part of the method: the output is meant to be inspected, so a person can see *where* the series diverged and *why* it was flagged.

### BSc — Saratov State University

**Thesis:** RAG system for question answering over company documentation

A retrieval-augmented generation pipeline over an internal document corpus. Relevant passages are retrieved first; the answer is generated from those passages rather than from the model’s prior alone, so responses stay tied to company documentation.

---

## Public work

Backend sample, not the full work I do in production:

**[SSUbench](https://github.com/WaltzForLovers/_SSUbench)** — REST API in Go for a small task marketplace (customers, executors, bids, virtual-point payments). JWT and RBAC, raw SQL on pgx, transactional payments, chi, OpenAPI, Docker Compose, unit tests on the business rules.
