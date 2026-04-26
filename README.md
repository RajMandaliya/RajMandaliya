# Hey, I'm Raj 👋

**Software Engineer** specializing in **Rust, low-level systems, and distributed infrastructure**.

I build systems from the ground up — from custom CPU emulators and cache simulators to
Rust-based edge services processing 10M+ requests daily and event-driven fintech pipelines.

- 🦀 High-performance systems in Rust (Tokio, Actix Web, lock-free data structures)
- ⚙️ CPU architecture — ISA design, pipeline simulation, cache modeling
- 📡 Event-driven architecture with Apache Kafka at production scale
- ☁️ Cloud-native infrastructure — Docker, Kubernetes, AWS

---

## 🚀 Featured Projects

### 🖥️ cpu16 — Custom 16-bit CPU Emulator
A complete CPU built from first principles in Rust. Every design decision — instruction
encoding, memory layout, interrupt handling — made deliberately and documented.

- Custom 35-instruction ISA with 16-bit fixed-width encoding and 5-bit FLAGS register
- Two-pass assembler with forward-reference resolution compiling `.asm` → binary
- 5-stage in-order pipeline (IF → ID → EX → MEM → WB) with RAW data hazard stall
  detection, flag hazard detection for conditional branches, and 2-cycle branch flush
- Direct-mapped write-through L1 cache classifying misses as cold vs conflict;
  demonstrates cache thrashing on bubble sort's non-sequential access pattern
- 6 assembly programs: bubble sort, binary search, Sieve of Eratosthenes, RPN
  stack calculator, Fibonacci, Factorial
- 49 integration tests · 5 versioned releases · CI: fmt + clippy + test on every push

> **Stack:** Rust · Custom ISA · Pipeline Simulation · Cache Modeling · Systems Programming

---

### 🦀 Mini-Agent: Rust AI Agent Framework
Rust-based AI agent implementing the full plan → act → observe execution loop.

- Modular tool system with dynamic tool registration and extensibility
- Async architecture with Tokio for scalable multi-step task execution
- Memory-safe by design using Rust ownership model
- Published as a reusable library on [crates.io](https://crates.io)
- ⭐ 12 stars — organic traction from the Rust community

> **Stack:** Rust · Tokio · LLM APIs · Async

---

### 🚨 Anomaly Detection System
Real-time detection pipeline across three live Kafka streams.

- PyOD ensemble (IForest + LOF + HBOS) with majority voting
- Automatic concept drift re-fitting every 500 events
- FastAPI REST + WebSocket live alert feed · 44 pytest tests · Fully Dockerized

> **Stack:** Kafka · PyOD · FastAPI · PostgreSQL · Docker · Python

---

## 🛠 Tech Stack

**Languages**
Rust • Python • Java • Go • C++ • TypeScript

**Backend**
Tokio • Actix Web • Spring Boot • FastAPI • JAX-RS • Hibernate

**Infrastructure**
Kafka • Redis • Docker • Kubernetes • Terraform • AWS • GitHub Actions

**Databases**
PostgreSQL • MySQL • Amazon S3 • Redshift • Snowflake

**Concepts**
CPU architecture • Cache simulation • Pipeline hazard detection • Distributed systems •
Memory safety • Concurrency • Event-driven architecture • CI/CD

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=RajMandaliya&show_icons=true&theme=chartreuse-dark&hide_border=true" height="165"/>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=RajMandaliya&theme=chartreuse-dark&hide_border=true" height="165"/>
</p>
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=RajMandaliya&layout=compact&theme=chartreuse-dark&hide_border=true"/>
</p>

---

## 📈 Activity Graph

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=RajMandaliya&theme=react-dark&hide_border=true"/>
</p>

---

## 🤝 Connect

- 💼 LinkedIn: [linkedin.com/in/raj-mandaliya-78a622249](https://www.linkedin.com/in/raj-mandaliya-78a622249)
- 🌐 Portfolio: [rajmandaliya-portfolio.vercel.app](https://rajmandaliya-portfolio.vercel.app)
- ✉️ Email: [rajmandaliyasurvey@gmail.com](mailto:rajmandaliyasurvey@gmail.com)

---

💡 *Open to SDE II / SDE III roles in systems and backend infrastructure.*
