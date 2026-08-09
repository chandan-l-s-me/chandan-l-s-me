<h1 align="center">Hi, I'm Chandan 👋</h1>
<h3 align="center">Systems-minded Software Engineer | C++ & Distributed Systems | B.Tech CSE @ PES University</h3>

<p align="center">
  <a href="https://github.com/chandan-l-s-me"><img src="https://img.shields.io/badge/GitHub-chandan--l--s--me-181717?style=flat&logo=github" /></a>
  <img src="https://img.shields.io/badge/Focus-Systems%20Programming-orange" />
  <img src="https://img.shields.io/badge/Role-SWE%20Intern%20%40%20Fiserv-blue" />
</p>

---

### 🧭 About Me

I'm a Computer Science undergrad (2023–2027) at **PES University, Bengaluru** (CGPA 8.97/10.0, CNR Rao Scholarship awardee — top 20% of the CSE batch across 6 consecutive semesters), currently interning as a Software Engineer at **Fiserv**. My core strength is **Data Structures & Algorithms**, and my project work follows a clear pattern: I like taking well-known infrastructure primitives — storage engines, message brokers, CI pipelines, billing systems — and **rebuilding them from first principles** to actually understand how they work under the hood, rather than just using them as black boxes.

- 🔭 Currently building distributed systems and low-level storage primitives in C++
- 🌱 Deepening my systems programming and backend engineering skills
- 🎯 Preparing for placements/internships at top product and infra-focused companies
- 💬 Ask me about B-trees, WALs, LSM-trees, sparse indexes, or bloom filters
- 📄 Published: *"LLM-Driven Resume Matching with Preference Re-Ranking and Skill Recommendations"* — SMARTGENCON 2025

---

### 💼 Work Experience

**Software Engineer Intern — Fiserv, Bengaluru** *(Jun 2026 – Present)*
- Designed a desktop **XML Search Engine** (Python, PyQt6) with custom XML parsing and indexing, serving as the core schema-setting finder across enterprise financial institution workflows
- Architected an internal **Jira Hygiene Tracker** (REST APIs + JQL) consolidating engineering metrics across 50+ cross-functional teams for real-time release/project visibility to PMs and VPs
- Automated executive reporting via centralized dashboards, cutting analysis time from 30–40 minutes to under 60 seconds

---

### 🗂️ Featured Projects

| Project | What it is | Why it's interesting | Stack |
|---|---|---|---|
| **[KVStore](https://github.com/chandan-l-s-me/KVStore)** | A persistent, Bitcask-inspired key-value storage engine | Custom WAL for durability, in-memory KeyDir + memTable, SSTable flushing, sparse index with binary search, and a double-hashing bloom filter bounding disk scans to ~100 records. Multithreaded TCP server using `std::shared_mutex` for read-write concurrency. Benchmarked with YCSB across 50 concurrent clients: 53.7K ops/sec (read-heavy, 4.54ms p99) and 45.7K ops/sec (50/50 R/W, 7.12ms p99), zero errors over 1.5M+ ops | C++17 |
| **[Yet_Another_kafka](https://github.com/chandan-l-s-me/Yet_Another_kafka)** | A Kafka-inspired distributed message broker | Implements leader election, synchronous replication, and automatic failover — the hard parts of a real message queue, not just pub/sub | Python (FastAPI + Redis) |
| **[ai-powered-job-skill-recommender](https://github.com/chandan-l-s-me/ai-powered-job-skill-recommender)** | Resume-to-job matching using semantic similarity | Dense vector embeddings outperform TF-IDF/keyword baselines; automated skill-gap analysis and interactive upskilling workflow via Gradio. Published as a paper at SMARTGENCON 2025 | Python, Gradio |
| **[VyaparaBilling](https://github.com/chandan-l-s-me/VyaparaBilling)** | GST-compliant, offline-first retail POS & inventory system | Real client project — barcode scanning, billing, purchases, role-based admin/cashier access, and native-language support. Cut billing time by ~50% | TypeScript, React, Express, SQLite |
| **[Finsphere](https://github.com/chandan-l-s-me/Finsphere)** | AI-powered personal finance analysis platform | Parses transaction data from CSV/PDF, runs an agent-based pipeline for financial metrics, generates AI insights (Gemini API), computes a FairScore-like credit score, and outputs PDF reports | Python, FastAPI, React, Tailwind |
| **[ReleaseMind](https://github.com/chandan-l-s-me/ReleaseMind)** | A multi-agent intelligence layer for CI/CD | Predicts release risk and optimizes test selection to ship faster | TypeScript |

---

### 🛠️ Tech Stack

**Languages:** ![C++](https://img.shields.io/badge/-C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white) ![C](https://img.shields.io/badge/-C-A8B9CC?style=flat-square&logo=c&logoColor=white) ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Java](https://img.shields.io/badge/-Java-007396?style=flat-square&logo=openjdk&logoColor=white) ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![SQL](https://img.shields.io/badge/-SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**Systems & Architecture:** Distributed Systems · Operating Systems · Computer Networks · Data Structures & Algorithms · WAL & LSM-tree storage design

**Frameworks & Infrastructure:** Node.js · Express.js · React · FastAPI · Apache Kafka · Apache Spark · Docker · Git · Linux

**Databases:** MySQL · MongoDB · SQLite

**Other:** REST APIs · Competitive Programming (LeetCode / contests)

---

### 📊 A Quick Read on My Portfolio

- **~50% systems/infra** (KVStore, Yet_Another_kafka) — building the primitives other software depends on
- **~33% applied AI** (job-skill-recommender, Finsphere) — using ML/LLMs for practical, user-facing problems
- **~17% product engineering** (VyaparaBilling, ReleaseMind) — full-stack, client-facing, developer-tooling work

This spread signals a systems-first engineer who can also ship end-to-end products — which is exactly the story worth telling to interviewers.

---

### 📫 Connect

<p align="center">
  <a href="mailto:chandanlsofficial@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white" /></a>
  <a href="https://github.com/chandan-l-s-me"><img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" /></a>
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" />
</p>

<p align="center"><i>Open to opportunities in backend, infra, and systems engineering.</i></p>
