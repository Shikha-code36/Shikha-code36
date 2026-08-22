<h1 align="center">Hi 👋 I'm Shikha Pandey</h1>

<p align="center">
  <strong>Software Engineer II @ American Express</strong><br>
  Distributed Systems • Databases • Caching • AI Infrastructure
</p>

<p align="center">
  <a href="https://pandeyshikha.me/">Portfolio</a> •
  <a href="https://www.linkedin.com/in/36-shikha-pandey/">LinkedIn</a> •
  <a href="https://pandeyshikha075.medium.com">Medium</a>
</p>

---

## About

I'm a software engineer focused on the infrastructure behind modern software systems — distributed systems, databases, caching, and AI infrastructure.

I like understanding systems from first principles: how they behave under load, why they fail, and how specific engineering decisions trade off performance against reliability. I explore these questions through hands-on open-source contribution, reproducible experiments, and writing.

---

## 🔧 Systems & Infra Contributions

*As of August 2026: 5 merged, 5 in review, across 4 repositories.*

I contribute correctness, crash-safety, and observability fixes to production cache, database, and search infrastructure.

**dragonflydb/dragonfly** — *5 merged*
Crash prevention, RSS/OOM test stability, cluster slot-migration correctness, RENAME data-loss prevention.

**valkey-io/valkey** — *in review*
Fixed replica full-resync failing after restart with AOF-only persistence. Fixed an O(class size × string length) DoS in glob pattern matching.

**valkey-io/valkey-search** — *in review*
Fixed stale RDB restore counters causing a permanently inflated index metric.

**facebook/rocksdb** — *in review*
Fixed a native memory leak in RocksJava's thread-local comparator buffer handling.

→ [All pull requests](https://github.com/search?q=author%3AShikha-code36+is%3Apr&type=pullrequests)

---

## 🚀 Current Work

### 🐛 SlimyBug
*An experimentation platform for distributed systems.*

SlimyBug makes distributed-systems failure modes — retry amplification, cascading failures, admission control, connection-pool saturation, overload behavior — observable through controlled, reproducible experiments, so they can be studied directly instead of learned from production incidents.

**Current research areas**
Database latency propagation • Retry amplification • Circuit breakers • Retry jitter • Connection pool capacity • Admission control • Signal freshness • Overload onset • Admission deferral • Connection pool self-locking

**Long-term direction**
Research-grade, reproducible experiment methodology; an experiment DSL & CLI; evidence-backed engineering findings; a learning platform for distributed systems.

**Stack:** Python • PostgreSQL • Docker • Prometheus • Grafana • OpenTelemetry

---

### 🧠 SmartEvict
*Learned semantic cache eviction for LLM applications.*

Investigates lightweight, learned eviction policies against classical heuristics (LRU, FIFO, GDSF) using reproducible experiments on real conversational workloads.

- 📦 [Repository](https://github.com/Shikha-code36/SmartEvict-Semantic-Cache-Eviction)
- 📖 [Research artifact (DOI)](https://zenodo.org/records/21643364)

---

## 🔬 Areas of Interest

Distributed Systems • Databases • Caching Systems • AI Infrastructure • Performance Engineering • Reliability Engineering • LLM Infrastructure • Developer Infrastructure

---

## ✍️ Writing

I write about the experiments, investigations, and findings behind my systems work — distributed systems, databases and caching, AI infrastructure, performance, reliability, and software engineering more broadly.

📚 [Medium](https://pandeyshikha075.medium.com)

---

## 🛠️ Technologies

**Languages:** Python • Go • C++ • JavaScript
**Backend:** FastAPI • Flask • PostgreSQL • Redis • Kafka • RabbitMQ
**Infrastructure:** Docker • AWS • GCP • Prometheus • Grafana • OpenTelemetry
**AI:** OpenAI • Claude • LangChain • Hugging Face • pgvector

---

## 🌱 Currently Exploring

Cache design & eviction algorithms • Consensus & replication protocols • Distributed systems internals • AI serving infrastructure • Experimentation frameworks

---

## 📫 Connect

🌐 [Portfolio](https://pandeyshikha.me/) • 💼 [LinkedIn](https://www.linkedin.com/in/36-shikha-pandey/) • 📝 [Medium](https://pandeyshikha075.medium.com) • 📧 [shikha.py36@gmail.com](mailto:shikha.py36@gmail.com)

---

<p align="center"><strong>Build systems. Run experiments. Produce evidence. Share findings.</strong></p>
