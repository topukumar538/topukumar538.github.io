# Topu Kumar Mondol

**ECE undergraduate at RUET | Backend development & AI-powered applications**

I build Python backend services and AI-powered applications, combining FastAPI and PostgreSQL with retrieval and LLM workflows. I enjoy working on the engineering around these systems: authentication, session persistence, automated testing, Docker, and CI/CD.

I am pursuing a **B.Sc. in Electrical & Computer Engineering** at **Rajshahi University of Engineering & Technology (RUET), Bangladesh**, with expected graduation in **October 2028**.

[Resume (PDF)](Topu_Kumar_Mondol_Resume.pdf) · [Portfolio](https://topukumar538.github.io/) · [LinkedIn](https://linkedin.com/in/topu-kumar-mondol) · [Email](mailto:topukumar538@gmail.com)

---

## About Me

- Focused on software engineering, particularly backend systems and applied AI integration.
- Building projects that connect APIs, databases, retrieval, and multi-step LLM workflows.
- Practicing data structures and algorithms, with 400+ problems solved across LeetCode and other platforms.
- Interested in open-source contributions involving Python, developer tools, and AI-powered software.
- Seeking software engineering internship opportunities for 2027.

## Featured Projects

### OpsIQ — AI Assistant for Chat, Document Q&A & Incident Analysis

`Python` `FastAPI` `LangGraph` `LangChain` `FAISS` `PostgreSQL` `SQLAlchemy` `Docker`

OpsIQ is a session-based AI assistant with three modes: general chat, document question answering, and log-triggered incident analysis. It combines retrieval, workflow orchestration, persistent conversation state, and streamed responses.

#### Core features

- **General chat:** Maintains conversational context using summaries and recent messages.
- **Document Q&A:** Retrieves relevant document chunks through FAISS and SentenceTransformer embeddings to provide context for LLM responses.
- **Incident analysis:** Processes uploaded logs through a 5-node LangGraph pipeline to generate a structured postmortem.
- **Parallel analysis:** Runs log analysis and timeline extraction in parallel before combining their outputs for root-cause synthesis and remediation suggestions.
- **Follow-up questions:** Supports report-grounded chat after postmortem generation.
- **Streaming:** Delivers responses through Server-Sent Events (SSE).

#### Backend and reliability

- Uses asynchronous FastAPI endpoints and PostgreSQL persistence with SQLAlchemy.
- Stores conversation summaries and recent messages for session recovery.
- Uses three LLM instances configured with temperatures of 0.7, 0.3, and 0.1 for different workflow tasks.
- Applies upload size checks, file-type validation, duplicate detection, and pipeline timeouts.
- Includes session locking, cleanup of inactive sessions, cookie-based JWT authentication, and request rate limits.
- Packages the application with Docker and deploys to Hugging Face Spaces through GitHub Actions after tests pass.

#### Testing

Includes **19 tests checking expected concepts in synthetic scenarios based on published GitLab, Cloudflare, and AWS postmortems**. These checks exercise incident-analysis behavior; they do not establish accuracy on unseen production incidents.

### ContentPlatform — Personalized Content Feed

`Python` `FastAPI` `PostgreSQL` `SQLAlchemy 2.0` `Pydantic` `Docker` `Pytest` `Locust`

ContentPlatform is a personalized feed that combines user preferences, exploration, and fresh content. Its ranking logic uses interactions such as views, likes, and saves while limiting how much one category can dominate a page.

#### Recommendation logic

- **Preference-based ranking:** Prioritizes content using weighted user interactions.
- **Softmax exploration:** Samples additional items to introduce variety beyond the highest-ranked content.
- **Fresh content:** Includes newer unseen items.
- **Time decay:** Reduces the influence of older content and interactions.
- **Category limits:** Encourages a more varied feed.
- **Stable pagination:** Uses a user- and hour-based seed to keep ordering consistent within a browsing window.
- **Viewed-content exclusion:** Filters previously viewed content and handles feed exhaustion.

#### Backend and delivery

- Provides cookie-based JWT authentication and email OTP verification.
- Uses PostgreSQL, SQLAlchemy 2.0, and Pydantic for persistence and validation.
- Runs scheduled preference updates with APScheduler, using grouped aggregation and bulk updates.
- Includes **47 automated tests**.
- Uses Docker Compose and GitHub Actions to test the application before deployment to Hugging Face Spaces.

#### Load testing

Tested with Locust from **10 to 500 concurrent users**. In the reported test setup, the application achieved approximately **99% request success at 100 users**, with **800 ms p95 response time**. Testing at 500 users exposed database connection-pool limits. These figures describe that test environment, rather than a general production capacity guarantee.

**[Explore project repositories on GitHub](https://github.com/topukumar538?tab=repositories)**

## Technical Skills

| Area | Technologies |
| --- | --- |
| Languages | Python, C++, C, SQL |
| Backend | FastAPI, REST APIs, Pydantic, JWT authentication, APScheduler, Server-Sent Events |
| Databases | PostgreSQL, SQLAlchemy 2.0, Neon |
| AI & retrieval | LangChain, LangGraph, RAG, FAISS vector search, SentenceTransformers, embeddings, LLM integration |
| Infrastructure | Docker, Docker Compose, GitHub Actions, Hugging Face Spaces |
| Testing & development | Pytest, Locust, Git, GitHub |

## Current Focus

- Strengthening data structures, algorithms, and interview problem-solving skills.
- Improving backend reliability, database performance, and automated testing.
- Building AI features with clear workflow boundaries and persistent application state.
- Exploring open-source projects at the intersection of software engineering and applied AI.

## Education

**Rajshahi University of Engineering & Technology (RUET)**  
B.Sc. in Electrical & Computer Engineering  
Expected graduation: **October 2028**

Relevant coursework: Data Structures & Algorithms, Object-Oriented Programming, and Database Systems.

## Certifications

- **Machine Learning Specialization** — DeepLearning.AI / Andrew Ng (Coursera), December 2025
- **CS50x: Introduction to Computer Science** — HarvardX (edX), October 2024
- **CS50P: Introduction to Programming with Python** — HarvardX (edX), 2024

## Contact

I am interested in software engineering internships and open-source collaboration, especially in backend development and AI-powered applications.

- **Email:** [topukumar538@gmail.com](mailto:topukumar538@gmail.com)
- **LinkedIn:** [topu-kumar-mondol](https://linkedin.com/in/topu-kumar-mondol)
- **GitHub:** [topukumar538](https://github.com/topukumar538)
- **Portfolio:** [topukumar538.github.io](https://topukumar538.github.io/)

<!-- The resume link assumes Topu_Kumar_Mondol_Resume.pdf is in the same repository directory as this README. -->
