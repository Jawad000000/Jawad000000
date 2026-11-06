<div align="center">

  <!-- Header Banner (XML-safe text without raw ampersands) -->
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=1,12,24&height=220&section=header&text=Mohd%20Jawwad&fontSize=68&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Python%20and%20FastAPI%20Developer%20%7C%20GenAI%20and%20Backend%20Systems&descFontSize=22&descAlignY=62&descAlign=50" width="100%" />

  <!-- Animated Typing SVG -->
  <a href="https://github.com/Jawad000000">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=60A5FA&center=true&vCenter=true&random=false&width=680&lines=Building+Distributed+Task+Queues+with+FastAPI+and+Redis;Architecting+Scalable+APIs+with+FastAPI+and+PostgreSQL;Developing+GenAI+Applications+and+RAG+Pipelines;Building+Core+Systems+from+Scratch+(Rate+Limiters%2C+APIs)" alt="Typing SVG" />
  </a>

  <br/>

  <!-- Social & Quick Contact Badges -->
  <p align="center">
    <a href="mailto:mohdjawwad73@gmail.com">
      <img src="https://img.shields.io/badge/Email-mohdjawwad73%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail" />
    </a>
    <a href="https://github.com/Jawad000000">
      <img src="https://img.shields.io/badge/GitHub-Jawad000000-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
    </a>
    <a href="https://linkedin.com">
      <img src="https://img.shields.io/badge/LinkedIn-Mohd_Jawwad-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
    </a>
  </p>

</div>

---

### 🚀 About Me

Hey there! 👋 I am **Mohd Jawwad**, a backend and systems developer specializing in **Python, FastAPI, and Generative AI**. I focus on building high-concurrency microservices, distributed task pipelines, and production-ready GenAI/RAG applications.

- ⚡ **Backend & Distributed Systems:** Designing robust async microservices with **FastAPI**, distributed background workers with **Redis & AsyncIO**, database schema management with **SQLModel/Alembic**, and custom primitives like in-memory **Token Bucket** rate limiters.
- 🤖 **Generative AI & RAG:** Building semantic search engines with **Qdrant** vector databases, dense embeddings using **Sentence-Transformers**, multi-tool LLM workflows (**Groq**, **Google Gemini**), and strict schema validation with **Pydantic**.
- 🛠️ **Engineering Mindset:** Building from first principles. I love getting under the hood to handle worker pools, GIL bypasses via multi-processing, exponential backoffs, and caching strategies.

---

### 💻 Tech Stack & Toolkit

<div align="center">

| Domain | Technologies |
| :--- | :--- |
| **Backend & Architecture** | ![Python](https://img.shields.io/badge/Python%203.12+-3776AB?style=flat-square&logo=python&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![AsyncIO](https://img.shields.io/badge/AsyncIO-3776AB?style=flat-square) ![SQLModel](https://img.shields.io/badge/SQLModel-009688?style=flat-square) ![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white) ![Alembic](https://img.shields.io/badge/Alembic-003B57?style=flat-square) ![REST APIs](https://img.shields.io/badge/REST%20APIs-005571?style=flat-square) |
| **Databases & Caching** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) |
| **GenAI & Vector Search** | ![Groq](https://img.shields.io/badge/Groq-F05A28?style=flat-square&logo=groq&logoColor=white) ![Google Gemini](https://img.shields.io/badge/Google%20Gemini-8E75C2?style=flat-square&logo=googlegemini&logoColor=white) ![Qdrant](https://img.shields.io/badge/Qdrant-DC2626?style=flat-square&logo=qdrant&logoColor=white) ![Sentence Transformers](https://img.shields.io/badge/Sentence--Transformers-008080?style=flat-square) ![Pydantic](https://img.shields.io/badge/Pydantic%20v2-E92063?style=flat-square&logo=pydantic&logoColor=white) ![RAG](https://img.shields.io/badge/RAG%20Pipelines-0284C7?style=flat-square) |
| **Tools & Testing** | ![uv](https://img.shields.io/badge/uv-DE5FE9?style=flat-square) ![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white) ![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white) |

</div>

---

### 🔥 Featured Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>⚙️ <a href="https://github.com/Jawad000000/taskqueue">WorkQueue — Distributed Task Queue</a></h3>
      <p>High-performance, distributed background job processing system:</p>
      <ul>
        <li><b>Concurrent Worker Pools:</b> Asyncio worker pools polling Redis with atomic <code>BRPOP</code> operations.</li>
        <li><b>Hybrid Task Dispatcher:</b> Non-blocking async handling for I/O tasks and <code>ProcessPoolExecutor</code> for CPU-bound tasks to bypass the Python GIL.</li>
        <li><b>Resilience:</b> Exponential backoff retries with delayed queue scheduling and Dead Letter Queue (DLQ) isolation.</li>
        <li><b>Real-Time Observability:</b> Atomic metrics tracking, worker heartbeats, and persistent audit logging.</li>
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
      <p>Production-ready URL shortener backend with caching and auth:</p>
      <ul>
        <li><b>FastAPI + Async Database:</b> Built with PostgreSQL, <code>asyncpg</code>, and SQLModel with Alembic migration versioning.</li>
        <li><b>High-Speed Caching:</b> Redis-powered redirect caching and access count analytics.</li>
        <li><b>Stateless Auth & Security:</b> JWT authentication with access + refresh token cycles, token blocklisting, and endpoint rate limiting.</li>
        <li><b>Containerized:</b> Fully containerized with Docker & Docker Compose setup.</li>
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
      <p>A FastAPI project implementing token bucket rate limiting from scratch:</p>
      <ul>
        <li>Prevents API overload and manages client burst traffic using dedicated token buckets.</li>
        <li>Refills tokens over time with configurable refill rates and returns HTTP 429 when depleted.</li>
        <li>Built to understand backend request handling and middleware interceptors.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square" />
        <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square" />
        <img src="https://img.shields.io/badge/Rate_Limiter-6366F1?style=flat-square" />
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>📄 <a href="https://github.com/Jawad000000/aieng">ATS Resume Intelligence Matcher</a></h3>
      <p>Automated resume extraction and job-fit evaluation system:</p>
      <ul>
        <li>Extracts candidate experience, skill matrices, and qualifications from PDF documents.</li>
        <li>Guarantees validated structured schema output with Pydantic models.</li>
        <li>Compares candidate qualifications against job descriptions to compute match details.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Pydantic-E92063?style=flat-square" />
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
        <li>Ingests video transcripts into vector space with optimized chunking and metadata.</li>
        <li>Retrieves precise video segments using semantic vector search.</li>
        <li>Grounds LLM responses with exact transcript context and timestamps to eliminate hallucinations.</li>
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

### 📊 GitHub Activity & Metrics

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Jawad000000&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=60a5fa&icon_color=38bdf8&text_color=94a3b8" height="175" alt="GitHub Stats" />
  &nbsp;
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Jawad000000&theme=tokyonight&hide_border=true&background=0d1117&ring=60a5fa&fire=f59e0b&currStreakNum=60a5fa&sideNums=94a3b8&sideLabels=94a3b8&dates=94a3b8" height="175" alt="Streak Stats" />
</div>

<div align="center" style="margin-top: 15px;">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Jawad000000&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=60a5fa&text_color=94a3b8" height="150" alt="Top Languages" />
</div>

---

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=1,12,24&height=100&section=footer" width="100%" />
</div>
