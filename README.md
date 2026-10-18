<div align="center">

# Adarsh V H

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=58A6FF&center=true&vCenter=true&width=700&lines=Systems+Engineer;Backend+Developer;Database+%26+Distributed+Systems" />

I build software at the intersection of systems, backend engineering, databases, and cloud infrastructure.

I care deeply about understanding what’s under the hood: how data moves, how systems fail, how databases execute, where latency comes from, and how software interacts with the hardware beneath it.

[LinkedIn](https://linkedin.com/in/adarsh-v-h-2005abc) · [Gmail](mailto:adarshvh2005@gmail.com) · [Portfolio](https://adarsh-v-h.github.io/)

</div>

---

## About me

- Third-year CSE student at JSS Bengaluru
- Interested in: systems programming, backend architecture, SQL and database internals, distributed systems, cloud, and performance engineering
- Passionate about building reliable, fast, and observably correct software

---

## Featured projects

### 1) Agentic-KSP
A deployed crime-intelligence platform for Karnataka State Police.

- Officers ask questions in English or Kannada
- LLM generates MySQL queries on AWS RDS with a self-correction loop
- Answers stream back over SSE
- Access is read-only and scoped using JWT, RBAC, and a C++20 SQL-AST filter

Tech: Python, FastAPI, gRPC, MySQL, AWS RDS, SSE, RAG

Repository: https://github.com/adarsh-v-h/AgenticAI-KSP

### 2) Universal Log Framework (ULPF)
A vendor-agnostic log platform for Syslog, CEF, LEEF, and JSON inputs.

- Preserves raw events and normalizes them into a single schema in ClickHouse
- Built the Java backend for batched writes, integrity checks, and schema mapping
- Includes SHA-256 Merkle-tree validation for event integrity
- Local ONNX embedding model for schema mapping
- Load-tested at ~995 events/sec with ~77 ms P95 latency

Tech: Java 21, Spring Boot, SQLite, ClickHouse, Podman

Repository: https://github.com/adarsh-v-h/ULPF

### 3) MeetInMin
Meeting assistant that records browser-tab audio without a bot joining the call.

- Produces transcript, summary, key decisions, and action items
- Uses Zoho Zia speech-to-text in 4-minute chunks
- Extracts decisions with Zoho GLM and confidence scores
- Maintains per-project memory from meetings and project docs
- Reads Gmail context for decisions and follow-ups

Tech: Python, FastAPI, React, Chrome Extension MV3, Gmail OAuth

Repository: https://github.com/adarsh-v-h/MeetInMin

### 4) High-Performance Limit Order Book
An evolving low-latency C++ matching engine.

- Focused on cache-aware structures, concurrency, deterministic hot paths, and memory layout
- Built to learn how latency is shaped by data structure and system design decisions

Tech: C++, low-level design, performance engineering

Repository: https://github.com/adarsh-v-h/Order_book

### 5) Themis's Domain — CRMS
A crime record management system centered on relational data and backend services.

- Authentication, authorization, indexing, connection pooling, and caching
- Strong hands-on exposure to backend service design and data management

Tech: Backend services, relational design, auth, indexing, pooling

Repository: https://github.com/adarsh-v-h/Crime_DB

### 6) Software-Defined FADEC Simulation
A fault-tolerant engine control simulation built in C++.

- Closed-loop engine dynamics
- Telemetry and safe-state failover logic
- Reliability-focused control architecture

Tech: C++, simulation, control systems, fault tolerance

Repository: https://github.com/adarsh-v-h/Software-Defined-FADEC-Simulation

---

## Stack & tools

### Backend
- Python
- FastAPI
- gRPC
- Java (Spring Boot)

### Databases
- MySQL
- ClickHouse
- SQLite
- PostgreSQL

### Systems & low-level
- C
- C++
- Linux
- Memory and low-level performance design
- Concurrency patterns

### Cloud & infra
- AWS
- GCP
- Docker
- Podman
- Kubernetes
- Terraform

### Security & auth
- JWT
- OAuth2 / OpenID Connect
- RBAC / IAM
- SSO
- TLS / PKI
- Secrets management (Vault, secret stores)
- Security auditing and logging

---

## Currently exploring

- Distributed systems fundamentals: replication, partitioning, consistency, and failure modes
- Database internals and query execution
- PostgreSQL internals and performance tuning
- Low-level design in C++
- Core Java and Spring Boot
- Cloud architecture beyond RDS
- Advanced FastAPI patterns
- Reinforcement learning for intelligent systems
- Performance-oriented systems programming

---

## A quick principle

> I don’t just want software that works — I want software that is efficient, understandable, resilient, and built on strong system-level intuition.

---
