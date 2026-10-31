<!-- ===================== HEADER ===================== -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:7F00FF,100:00C6FF&height=200&section=header&text=Mayank%20Ranjan&fontSize=60&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=AI%20Engineer%20in%20the%20making&descSize=20&descAlignY=58" width="100%" />
</p>

<p align="center">
  <a href="https://github.com/mayankranjan-dev">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&pause=1000&color=36BCF7&center=true&vCenter=true&width=650&lines=Final-year+B.Tech+CS+student+%F0%9F%8E%93;Aspiring+AI+Engineer+%F0%9F%A4%96;I+build+LLM-powered+tools+with+FastAPI+%E2%9A%A1;RAG+%7C+Local+LLMs+%7C+Model+serving;Open+to+internships+from+Jan+2027+%F0%9F%9A%80" alt="Typing intro" />
  </a>
</p>

<p align="center">
  <a href="mailto:mayankranjan1606@gmail.com"><img src="https://img.shields.io/badge/Email-Contact_me-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/mayankranjan1606/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="https://github.com/mayankranjan-dev/mayankranjan-dev/blob/main/resume.pdf"><img src="https://img.shields.io/badge/Resume-View_PDF-2ea44f?style=for-the-badge&logo=adobeacrobatreader&logoColor=white" /></a>
  <img src="https://komarev.com/ghpvc/?username=mayankranjan-dev&label=Profile%20views&color=7F00FF&style=for-the-badge" alt="Profile views" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Status-Open_to_internships-brightgreen?style=flat-square" />
  <img src="https://img.shields.io/badge/Available_from-January_2027-blue?style=flat-square" />
  <img src="https://img.shields.io/badge/Location-Pune,_India-orange?style=flat-square" />
</p>

---

<!-- ===================== ABOUT ===================== -->
## 🙋 About me

I'm a final-year **B.Tech Computer Science** student at ADYP University, Pune, heading toward **AI engineering**. I like taking an idea from a model to a working service: an API with auth, tests, a Docker image and CI around it.

My recent work is in **LLM applications**: an AI code reviewer on a local model, a scam-job classifier built on DistilBERT, and a router that picks the cheapest LLM that can handle each prompt.

```python
class MayankRanjan:
    location    = "Pune, India 🇮🇳"
    education   = "B.Tech Computer Science @ ADYP University (2023 – 2027)"
    focus       = ["AI Engineering", "LLM apps & RAG", "Backend APIs"]
    builds_with = ["Python", "FastAPI", "Ollama", "Hugging Face", "Docker"]
    cares_about = ["tests", "security", "CI/CD", "measurable results"]
    looking_for = "Backend / Applied AI / Software internship from January 2027"
    languages   = ["English", "Hindi", "Japanese (beginner)"]

    def fun_fact(self):
        return "My code reviewer is an LLM I built myself 🤖"
```

### 🔭 What I'm focused on
- 🤖 **LLM applications**: local models with Ollama, structured outputs, fallbacks and retries
- 📚 **RAG**: embeddings with sentence-transformers, vector search with ChromaDB
- 📏 **LLM evaluation**: adversarial test sets, accuracy checks and guardrails
- ⚙️ **Backend engineering**: FastAPI services that are secure, tested and containerized

---

<!-- ===================== NUMBERS ===================== -->
## 📊 By the numbers

<table align="center">
  <tr>
    <td align="center" width="140"><h2>374</h2>passing tests<br/><sub>CodeRev Bot</sub></td>
    <td align="center" width="140"><h2>169 ms</h2>per job posting on CPU<br/><sub>JobSail</sub></td>
    <td align="center" width="140"><h2>10 / 10</h2>adversarial scams caught<br/><sub>JobSail</sub></td>
    <td align="center" width="140"><h2>&lt;1 ms</h2>prompt routing<br/><sub>SwitchOne</sub></td>
    <td align="center" width="140"><h2>~95%</h2>routing accuracy<br/><sub>SwitchOne</sub></td>
  </tr>
</table>

---

<!-- ===================== PROJECTS ===================== -->
## 🚀 Featured projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🔍 <a href="https://github.com/mayankranjan-dev/coderev">CodeRev Bot</a></h3>
      <p>AI pull-request reviewer running on a <b>local LLM</b>.</p>
      <p>
        <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
        <img src="https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white" />
        <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" />
        <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
        <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" />
      </p>
      <p>✅ <b>374 passing tests</b> · 🔐 HMAC-secured webhooks · 🐳 Docker</p>
      <details>
        <summary><b>▶ How it works</b></summary>
        <ul>
          <li>Receives GitHub PR webhooks and reviews the diff with a local Ollama model.</li>
          <li>Returns structured findings: severity, file, lines and a suggested fix.</li>
          <li>Also has a manual mode where you paste code to review.</li>
          <li>HMAC-SHA256 signature checks, API-key auth and per-IP rate limiting.</li>
          <li>Retry queue for offline or timed-out LLM calls.</li>
          <li>Judge0-sandboxed "Run Code" feature.</li>
          <li>Docker image reaches healthy status.</li>
        </ul>
      </details>
    </td>
    <td width="50%" valign="top">
      <h3>🛡️ <a href="https://github.com/mayankranjan-dev/jobsail">JobSail</a></h3>
      <p>Job aggregator that <b>catches scam postings</b> with a fine-tuned DistilBERT.</p>
      <p>
        <img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black" />
        <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
        <img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white" />
        <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" />
      </p>
      <p>⚡ <b>169 ms</b> per posting on CPU · 🎯 <b>10/10</b> adversarial scams flagged · ✅ 52 tests</p>
      <details>
        <summary><b>▶ How it works</b></summary>
        <ul>
          <li>Aggregates job postings and scores each one with a fine-tuned DistilBERT scam classifier.</li>
          <li>Classifier trained on 300 synthetic postings.</li>
          <li>Deterministic guardrail rules can only <i>raise</i> risk, never lower it. They raised risk on 3 of 10 adversarial postings.</li>
          <li>Flagged all 10 hand-written adversarial scam postings as suspicious or worse.</li>
          <li>Served through FastAPI with a SQLite backend. 52 passing tests.</li>
        </ul>
      </details>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🔀 <a href="https://github.com/mayankranjan-dev/switchone">SwitchOne</a></h3>
      <p>Cost-aware <b>LLM router</b>: local, free-tier or premium model per prompt.</p>
      <p>
        <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
        <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" />
        <img src="https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white" />
      </p>
      <p>⚡ <b>&lt;1 ms</b> routing · 🎯 <b>~95%</b> cross-validated accuracy · 🧪 80% coverage gate</p>
      <details>
        <summary><b>▶ How it works</b></summary>
        <ul>
          <li>Sends each prompt to the cheapest model that can handle it: local, free-tier or premium.</li>
          <li>Logistic regression on 10 hand-built features classifies prompt complexity locally.</li>
          <li>Trained on 150 hand-labeled prompts.</li>
          <li>Falls back to another model on failure and escalates one step when needed.</li>
          <li>CI enforces at least 80% test coverage.</li>
        </ul>
      </details>
    </td>
    <td width="50%" valign="top">
      <h3>📄 <a href="https://github.com/mayankranjan-dev/rag-resume-screener">RAG Resume Screener</a></h3>
      <p>Matches resumes to a job description with <b>retrieval-augmented generation</b>.</p>
      <p>
        <img src="https://img.shields.io/badge/RAG-6E40C9?style=flat-square" />
        <img src="https://img.shields.io/badge/ChromaDB-FF6446?style=flat-square" />
        <img src="https://img.shields.io/badge/sentence--transformers-0A66C2?style=flat-square" />
      </p>
      <p>🧠 Semantic search over resumes</p>
      <details>
        <summary><b>▶ How it works</b></summary>
        <ul>
          <li>Embeds resumes and the job description with sentence-transformers.</li>
          <li>Stores and searches embeddings in ChromaDB.</li>
          <li>Uses an LLM to rank and explain the best matches.</li>
        </ul>
      </details>
    </td>
  </tr>
</table>

<p align="center"><i>Click <b>▶ How it works</b> on any project to see the details.</i></p>

---

<!-- ===================== HOW I BUILD ===================== -->
## 🧭 How I build

| Principle | What it looks like in my projects |
|---|---|
| 🧪 **Test everything** | 374 tests in CodeRev Bot, 52 in JobSail, an 80% coverage gate in SwitchOne |
| 🔐 **Secure by default** | HMAC-SHA256 webhook verification, API-key auth and per-IP rate limiting |
| 🛟 **Plan for failure** | Retry queues for timed-out LLM calls, model fallback and escalation |
| 🧱 **Guardrails around models** | Rules that can only raise a model's risk score, never lower it |
| 📏 **Measure, don't guess** | Latency, accuracy and adversarial test results for every model |
| 💻 **Local-first AI** | Ollama models that run on my own machine, with no paid API needed |

---

<!-- ===================== SKILLS ===================== -->
## 🛠️ Tech stack

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=py,java,c,cpp,js,fastapi,sqlite,react,vite,tailwind,sklearn,docker,githubactions,git,linux&perline=8" alt="Tech stack icons" />
  </a>
</p>

| Area | Skills |
|---|---|
| 💬 **Languages** | Python, SQL, JavaScript, Java, C, C++ |
| 🤖 **AI / ML** | RAG, ChromaDB, sentence-transformers, Hugging Face Transformers, scikit-learn, Ollama (local LLMs), LLM evaluation |
| ⚙️ **Backend** | FastAPI, REST APIs, SQLAlchemy, pytest, HMAC-SHA256 and API-key auth, rate limiting |
| 📊 **Data, tools & DevOps** | SQLite, Pandas, Tableau, Excel, Git, GitHub Actions, Docker |
| 🎨 **Frontend** | React, Vite, Tailwind CSS |

---

<!-- ===================== EDUCATION & EXPERIENCE ===================== -->
## 🎓 Education

**B.Tech in Computer Science**, ADYP University, Pune · *Aug 2023 – May 2027*

<details>
  <summary><b>▶ Relevant coursework</b></summary>

- Data Structures and Algorithms
- Database Management Systems
- Operating Systems
- Computer Networks
- Software Reliability
- Software Analysis
- Java Application Development
- C and C++

</details>

## 💼 Experience

**Deloitte Data Analytics Job Simulation**, Forage (virtual) · *June 2025*
- Built a Tableau dashboard and completed Excel data analysis tasks.

---

<!-- ===================== CERTIFICATIONS ===================== -->
## 📜 Certifications

| Certification | Issuer | Year |
|---|---|---|
| 🏅 OCI Certified **AI Foundations Associate** | Oracle | 2026 |
| 🏅 **SQL (Intermediate)** | HackerRank | 2026 |
| 🏅 **Python (Basic)** | HackerRank | 2026 |
| 🏅 **AI Skills Passport** | EY and Microsoft | |
| 🏅 **Claude 101** | Anthropic | |

---

<!-- ===================== LOOKING FOR ===================== -->
## 🎯 What I'm looking for

- **Role:** internship in **AI / ML engineering**, **backend** or **software engineering**
- **Start:** January 2027
- **Where:** Pune, or remote
- **I bring:** working LLM projects with tests, security and Docker already in place

---

<!-- ===================== CONTACT ===================== -->
## 📫 Let's connect

<p align="center">
  If you're hiring interns or want to talk about AI engineering, I'd love to hear from you.<br/><br/>
  📧 <a href="mailto:mayankranjan1606@gmail.com"><b>mayankranjan1606@gmail.com</b></a> · 💼 <a href="https://www.linkedin.com/in/mayankranjan1606/"><b>LinkedIn</b></a> · 📄 <a href="https://github.com/mayankranjan-dev/mayankranjan-dev/blob/main/resume.pdf"><b>Resume</b></a>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:00C6FF,100:7F00FF&height=120&section=footer" width="100%" />
</p>
