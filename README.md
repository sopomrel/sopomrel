# Hi, I'm Sopo 👋

Computer Science student at **Kutaisi International University** (BSc, expected 2027), based in Tbilisi, Georgia.

I build **LLM-powered applications** and **backend systems**, in Python and Java. I care about what happens after the demo works: evaluating model output, handling failures gracefully, keeping costs under control, and writing code that's tested.

---

### 🤖 AI & LLM projects

**[CareerSim (Ascend.AI)](https://github.com/dioramashvili/Ascend.AI)** — *Python · FastAPI · Gemini · DeepSeek*
*University AI capstone · team of 4 · my role: LLM evaluation & reliability*

An AI career simulator: an LLM generates realistic workplace scenarios, users decide how to respond, and a second LLM call scores the decision and explains the trade-offs. The backend routes requests through a multi-provider layer (Gemini first, DeepSeek as fallback) with structured JSON outputs and error-aware retries.

What I worked on:
- Designed the **LLM evaluation plan** and function-calling test suite, covering JSON schema validity, input validation, sync vs. async evaluation, and cached vs. uncached latency.
- Reworked **Gemini safety-filter handling** to separate real safety blocks from false positives, so valid generations weren't discarded and true blocks returned clear, logged errors.
- Authored the **case study and cost analysis**: model-tier selection, trimmed evaluation context, caching, and prompt compression brought the estimated cost per interaction down by ~95%.
- Wrote the **PRD and feature roadmap** that defined the scenario-generation and evaluation flows.

**AgroAI — Agricultural AI Assistant** — *LLM · RAG · vector search · Lovable*
*Hacktoberfest 2025 · team of 5 · hackathon prototype, no public repo*

An AI assistant that answers farmers' agricultural questions, grounding its responses in a domain knowledge base through retrieval-augmented generation and vector search. The team prototyped it end to end within the hackathon.

What I worked on:
- Collected and processed domain data for the knowledge base.
- Validated the assistant's answers for relevance and accuracy and fed the findings back into prompt and design decisions.
- Shaped the product scope and weighed feature trade-offs to fit a working demo into the hackathon timeframe.

---

### ⚙️ Backend projects

**[Cinema API](https://github.com/sopomrel/cinema-api)** — *Java 21 · Spring Boot 3*
A production-oriented REST API for a movie catalog (movies, actors, directors). Layered architecture, DTOs with validation, role-based Spring Security, internationalized error handling (Georgian / English), profile-based config (H2 in dev, PostgreSQL in prod), Actuator monitoring with custom health indicators and metrics, structured logging, and a full test suite (unit, controller, repository, integration) behind a JaCoCo coverage gate.

**[DuckieTown](https://github.com/sopomrel/FinalProject)** — *Python · Flask · Godot*
A team-built robotics education platform for the Duckiebot DB21J. Students program tasks that run in a Godot 4.6 simulation or on real hardware, controlled through Flask task servers with live MJPEG camera streaming, JSON status polling, runtime YAML configuration, and a CLI launcher that deploys tasks to robots over the network.

---

### 🔧 What I work with

**AI / LLM:** Gemini API · OpenAI-compatible APIs (DeepSeek) · prompt engineering · structured JSON outputs · function calling · LLM evaluation · RAG · vector search
**Languages:** Python · Java · SQL
**Backend:** FastAPI · Pydantic · Flask · Spring Boot · Spring Security · Spring Data JPA / Hibernate · REST
**Data & infrastructure:** PostgreSQL · Supabase · Redis · Celery · H2
**Testing & quality:** JUnit 5 · Mockito · MockMvc · `@DataJpaTest` · JaCoCo
**Tooling:** Git · Maven · OpenAPI / Swagger · Spring Boot Actuator · SLF4J / Logback

---

### 🌱 Currently

- Going deeper into RAG pipelines, embeddings, and systematic LLM evaluation
- Strengthening my backend fundamentals through hands-on Java and Python projects
- Open to AI engineering and backend internship opportunities

---

### 📫 Reach me

- **Email:** sopomrel@gmail.com
- **LinkedIn:** [sopomrel](https://www.linkedin.com/in/sopomrel/)
