# Topu Kumar Mondol

B.Sc. in Electrical & Computer Engineering, Rajshahi University of Engineering & Technology (RUET) — expected October 2028.

I build backend and AI systems in Python: agentic pipelines, retrieval, and the infrastructure around them.

**[Download my resume (PDF)](Topu_Kumar_Mondol_Resume.pdf)**

---

## Projects

### OpsIQ — AI-Powered Ops Intelligence Platform
`Python` `FastAPI` `LangGraph` `LangChain` `FAISS` `PostgreSQL`

A 5-node LangGraph service that ingests production logs and generates structured postmortems. Log analysis and timeline extraction run in parallel and join at root-cause inference, with FAISS retrieval grounding each step. Verified by replaying three documented production incidents (GitLab 2017, Cloudflare 2019, AWS 2020) through the pipeline and asserting category matches against the published postmortems. Deployed through a GitHub Actions pipeline that runs the full test suite on every push.

[Repository](https://github.com/topukumar538)

### ContentPlatform — Personalized Recommendation Engine
`FastAPI` `PostgreSQL` `SQLAlchemy 2.0` `Docker` `Pytest` `Locust`

A slot-based recommendation feed with softmax sampling and time-decayed interaction weights, built so pagination stays stable and no single category dominates. Load tested with Locust from 10 to 500 concurrent users; sustained a 99% success rate at 100 users (~800ms p95), with the failure at 500 root-caused to database connection pool exhaustion.

[Repository](https://github.com/topukumar538)

---

## Technical Skills

**Languages** — Python, C++, C, SQL

**AI / ML** — LangChain, LangGraph, RAG, retrieval systems, vector databases (FAISS), embeddings, LLM integration

**Backend & Databases** — FastAPI, SQLAlchemy 2.0, PostgreSQL, REST APIs, JWT auth, APScheduler

**Cloud & Infrastructure** — Docker, CI/CD (GitHub Actions), Hugging Face Spaces, Neon (managed PostgreSQL)

**Tools** — Git, GitHub, Pytest, Locust, Pydantic

---

## Certifications

- **Machine Learning Specialization** — DeepLearning.AI / Andrew Ng (Coursera), December 2025
- **CS50x: Introduction to Computer Science** — HarvardX (edX), October 2024
- **CS50P: Introduction to Programming with Python** — HarvardX (edX), 2024

---

## Contact

- Email — topukumar538@gmail.com
- LinkedIn — [topu-kumar-mondol](https://linkedin.com/in/topu-kumar-mondol)
- GitHub — [topukumar538](https://github.com/topukumar538)
