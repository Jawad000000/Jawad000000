<div align="center">

  <!-- Header Banner in Dark Souls 1 Palette (Obsidian / Ember / Antique Sunlight Gold) -->
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:090909,30:170c06,70:5c1d06,100:d4af37&height=220&section=header&text=MOHD%20JAWWAD&fontSize=64&fontColor=d4af37&animation=fadeIn&fontAlignY=38&desc=PYTHON%20AND%20FASTAPI%20DEVELOPER%20%E2%80%A2%20GENAI%20SYSTEMS&descFontSize=19&descAlignY=62&descAlign=50" width="100%" />

  <br/>

  <!-- Quick Badges & Summon Sign -->
  <p align="center">
    <a href="mailto:mohdjawwad73@gmail.com">
      <img src="https://img.shields.io/badge/Summon_Sign-mohdjawwad73%40gmail.com-D4AF37?style=for-the-badge&logo=gmail&logoColor=black" alt="Summon Sign Email" />
    </a>
    <a href="https://github.com/Jawad000000">
      <img src="https://img.shields.io/badge/GitHub-Jawad000000-161616?style=for-the-badge&logo=github&logoColor=D4AF37" alt="GitHub" />
    </a>
    <a href="https://linkedin.com">
      <img src="https://img.shields.io/badge/LinkedIn-Mohd_Jawwad-161616?style=for-the-badge&logo=linkedin&logoColor=D4AF37" alt="LinkedIn" />
    </a>
    <a href="https://github.com/Jawad000000">
      <img src="https://komarev.com/ghpvc/?username=Jawad000000&color=d4af37&style=for-the-badge&label=SOULS+ACQUIRED" alt="Souls Acquired" />
    </a>
  </p>

</div>

---

### 🔥 About Me

Hey there! 👋 I am **Mohd Jawwad**, a backend and systems developer specializing in **Python, FastAPI, and Generative AI**. I focus on engineering high-concurrency microservices, distributed task pipelines, and production-ready GenAI/RAG applications.

- ⚡ **Backend & Distributed Systems:** Designing robust async microservices with **FastAPI**, distributed background worker pools with **Redis & AsyncIO**, schema management with **SQLModel & Alembic**, and custom primitives like in-memory **Token Bucket** rate limiters.
- 🤖 **Generative AI & RAG:** Building semantic search engines with **Qdrant** vector databases, dense embeddings using **Sentence-Transformers**, multi-tool LLM workflows (**Groq**, **Google Gemini**), and strict schema validation with **Pydantic v2**.
- 🛠️ **Engineering Philosophy:** Building systems from first principles—optimizing worker pools, bypassing the Python GIL via multiprocessing, designing exponential backoffs, and writing high-efficiency database queries.

> *"Don't you dare go hollow."*

---

### 💻 Tech Stack & Toolkit

<div align="center">

| Domain | Technologies |
| :--- | :--- |
| **Backend & Architecture** | ![Python](https://img.shields.io/badge/Python%203.12+-3776AB?style=flat-square&logo=python&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![AsyncIO](https://img.shields.io/badge/AsyncIO-3776AB?style=flat-square) ![SQLModel](https://img.shields.io/badge/SQLModel-009688?style=flat-square) ![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white) ![Alembic](https://img.shields.io/badge/Alembic-003B57?style=flat-square) ![REST APIs](https://img.shields.io/badge/REST%20APIs-005571?style=flat-square) |
| **Databases & Infrastructure** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) |
| **GenAI & Vector Search** | ![Groq](https://img.shields.io/badge/Groq-F05A28?style=flat-square&logo=groq&logoColor=white) ![Google Gemini](https://img.shields.io/badge/Google%20Gemini-8E75C2?style=flat-square&logo=googlegemini&logoColor=white) ![Qdrant](https://img.shields.io/badge/Qdrant-DC2626?style=flat-square&logo=qdrant&logoColor=white) ![Sentence Transformers](https://img.shields.io/badge/Sentence--Transformers-008080?style=flat-square) ![Pydantic v2](https://img.shields.io/badge/Pydantic%20v2-E92063?style=flat-square&logo=pydantic&logoColor=white) ![RAG](https://img.shields.io/badge/RAG%20Pipelines-0284C7?style=flat-square) |
| **Developer Tools & Testing** | ![uv](https://img.shields.io/badge/uv-DE5FE9?style=flat-square) ![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white) ![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white) |

</div>

---

### 🚀 Featured Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>⚙️ <a href="https://github.com/Jawad000000/taskqueue">WorkQueue — Distributed Task Processing System</a></h3>
      <p>High-performance distributed background job processing system built with FastAPI, Redis, and AsyncIO:</p>
      <ul>
        <li><b>Concurrent Worker Pools:</b> Asyncio worker pools executing atomic Redis <code>BRPOP</code> operations to guarantee non-blocking task delivery without race conditions.</li>
        <li><b>Hybrid Task Dispatcher:</b> Routes non-blocking I/O to async coroutines, while offloading CPU-intensive jobs to a <code>ProcessPoolExecutor</code> to bypass the Python GIL.</li>
        <li><b>Fault Tolerance:</b> Exponential backoff retries ($2^s$ delay) with delayed queue scheduling and Dead Letter Queue (DLQ) containment for exhausted jobs.</li>
        <li><b>Observability:</b> Real-time atomic metrics counters via <code>HINCRBY</code>, worker heartbeat leases with TTLs, and structured audit logs.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square" />
        <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square" />
        <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square" />
        <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square" />
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>🔗 <a href="https://github.com/Jawad000000/URL-SHORTENER">URL Shortener API</a></h3>
      <p>Production-ready URL shortener and redirect backend with caching and stateless security:</p>
      <ul>
        <li><b>Asynchronous Architecture:</b> Built with FastAPI, PostgreSQL via <code>asyncpg</code>, and SQLModel with Alembic version-controlled migrations.</li>
        <li><b>High-Speed Caching:</b> Redis-powered URL redirect caching and access count analytics for low-latency redirection paths.</li>
        <li><b>Authentication & Security:</b> JWT authentication featuring dual access/refresh tokens, token revocation blocklists, and endpoint rate limiting.</li>
        <li><b>Containerized Deployment:</b> Fully configured with Docker and Docker Compose orchestrations for multi-service environments.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square" />
        <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square" />
        <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square" />
        <img src="https://img.shields.io/badge/JWT-000000?style=flat-square" />
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>⚡ <a href="https://github.com/Jawad000000/token-bucket">Token Bucket Rate Limiter</a></h3>
      <p>Concurrency-safe token bucket rate limiting engine constructed from first principles in FastAPI:</p>
      <ul>
        <li>Prevents API overload and manages client burst traffic using dedicated per-client token buckets.</li>
        <li>Refills tokens over time with configurable refill rates and returns HTTP 429 when depleted.</li>
        <li>Implemented as reusable FastAPI middleware with isolated in-memory client state tracking.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square" />
        <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square" />
        <img src="https://img.shields.io/badge/Rate_Limiter-D4AF37?style=flat-square" />
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>📄 <a href="https://github.com/Jawad000000/aieng">ATS Resume Intelligence Matcher</a></h3>
      <p>Automated resume extraction and semantic job-fit evaluation pipeline:</p>
      <ul>
        <li>Extracts structured candidate data (experience, skills, certifications) from PDF documents.</li>
        <li>Enforces deterministic, type-safe JSON extraction with strict Pydantic v2 schemas and high-throughput LLM inference.</li>
        <li>Evaluates qualification match ratios against job descriptions with automated scoring algorithms.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Pydantic_v2-E92063?style=flat-square" />
        <img src="https://img.shields.io/badge/Groq-F05A28?style=flat-square" />
        <img src="https://img.shields.io/badge/pypdf-3178C6?style=flat-square" />
      </p>
    </td>
  </tr>
  <tr>
    <td colspan="2" valign="top">
      <h3>🎥 <a href="https://github.com/Jawad000000/youtube-rag-assistant">YouTube RAG Assistant</a></h3>
      <p>Semantic search and conversational question-answering over video content:</p>
      <ul>
        <li>Transforms video transcripts into dense semantic vector space with optimal chunking and metadata tags.</li>
        <li>Executes high-accuracy similarity queries using Sentence-Transformers and vector indexing.</li>
        <li>Grounds LLM responses with exact video timestamps to eliminate hallucinations and cite source context.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square" />
        <img src="https://img.shields.io/badge/RAG-0284C7?style=flat-square" />
        <img src="https://img.shields.io/badge/Vector_Search-4F46E5?style=flat-square" />
        <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square" />
      </p>
    </td>
  </tr>
</table>

---

### 📊 Activity & Metrics (Soul Tracker)

<div align="center">

  <img src="https://github-stats-extended.vercel.app/api?username=Jawad000000&show_icons=true&bg_color=0a0a0a&title_color=d4af37&icon_color=f97316&text_color=c0c0c0&border_color=d4af37" height="175" alt="Dark Souls Stats" />
  &nbsp;
  <img src="https://streak-stats.demolab.com/?user=Jawad000000&background=0a0a0a&ring=d4af37&fire=f97316&currStreakNum=d4af37&sideNums=c0c0c0&sideLabels=a3a3a3&dates=737373&border=d4af37" height="175" alt="Dark Souls Streak" />

</div>

<div align="center" style="margin-top: 15px;">
  <img src="https://github-stats-extended.vercel.app/api/top-langs/?username=Jawad000000&layout=compact&bg_color=0a0a0a&title_color=d4af37&text_color=c0c0c0&border_color=d4af37" height="150" alt="Top Languages" />
</div>

---

<div align="center">

  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:d4af37,30:5c1d06,70:170c06,100:090909&height=100&section=footer" width="100%" />

</div>
