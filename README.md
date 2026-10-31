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

---

<!-- ===================== ABOUT ===================== -->
## 🙋 About me

```python
class MayankRanjan:
    location   = "Pune, India 🇮🇳"
    education  = "B.Tech Computer Science @ ADYP University (2023 – 2027)"
    focus      = ["AI Engineering", "LLM apps & RAG", "Backend APIs"]
    builds_with = ["Python", "FastAPI", "Ollama", "Hugging Face", "Docker"]
    cares_about = ["tests", "security", "CI/CD", "measurable results"]
    looking_for = "Backend / Applied AI / Software internship from January 2027"
    languages  = ["English", "Hindi", "Japanese (beginner)"]

    def fun_fact(self):
        return "My code reviewer is an LLM I built myself 🤖"
```

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
      </p>
      <p>✅ <b>374 passing tests</b> · 🔐 HMAC-secured webhooks</p>
      <details>
        <summary><b>▶ How it works</b></summary>
        <ul>
          <li>Receives GitHub PR webhooks and reviews the diff with a local Ollama model.</li>
          <li>Returns structured findings: severity, file, lines and a suggested fix.</li>
          <li>HMAC-SHA256 signature checks, API-key auth and per-IP rate limiting.</li>
          <li>Retry queue for offline or timed-out LLM calls.</li>
          <li>Judge0-sandboxed "Run Code" feature and a manual review mode.</li>
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
      <p>⚡ <b>169 ms</b> per posting on CPU · 🎯 <b>10/10</b> adversarial scams flagged</p>
      <details>
        <summary><b>▶ How it works</b></summary>
        <ul>
          <li>Aggregates job postings and scores each one with a fine-tuned DistilBERT classifier.</li>
          <li>Deterministic guardrail rules can only <i>raise</i> risk, never lower it. They raised risk on 3 of 10 adversarial postings.</li>
          <li>Served through FastAPI with a SQLite backend.</li>
          <li>52 passing tests.</li>
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
      <p>⚡ <b>&lt;1 ms</b> routing · 🎯 <b>~95%</b> cross-validated accuracy</p>
      <details>
        <summary><b>▶ How it works</b></summary>
        <ul>
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

<!-- ===================== SKILLS ===================== -->
## 🛠️ Tech stack

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=py,java,c,cpp,js,fastapi,sqlite,react,vite,tailwind,sklearn,docker,githubactions,git,linux&perline=8" alt="Tech stack icons" />
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Hugging_Face_Transformers-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" />
  <img src="https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white" />
  <img src="https://img.shields.io/badge/ChromaDB-FF6446?style=for-the-badge" />
  <img src="https://img.shields.io/badge/RAG-6E40C9?style=for-the-badge" />
  <img src="https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge&logo=sqlalchemy&logoColor=white" />
  <img src="https://img.shields.io/badge/pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white" />
</p>

---

<!-- ===================== CERTIFICATIONS ===================== -->
<details>
  <summary><h2>📜 Certifications (click to expand)</h2></summary>

- 🏅 Oracle Cloud Infrastructure Certified **AI Foundations Associate**: Oracle (2026)
- 🏅 **SQL (Intermediate)** and **Python (Basic)**: HackerRank (2026)
- 🏅 **AI Skills Passport**: EY and Microsoft
- 🏅 **Claude 101**: Anthropic
- 💼 **Deloitte Data Analytics Job Simulation**: Forage (2025)

</details>

---

<!-- ===================== CONTRIBUTION SNAKE ===================== -->
## 🐍 Contribution snake

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/mayankranjan-dev/mayankranjan-dev/output/github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/mayankranjan-dev/mayankranjan-dev/output/github-snake.svg" />
    <img alt="Snake eating my contribution graph" src="https://raw.githubusercontent.com/mayankranjan-dev/mayankranjan-dev/output/github-snake-dark.svg" />
  </picture>
</p>

---

<!-- ===================== CONTACT ===================== -->
## 📫 Let's connect

<p align="center">
  I'm looking for an internship starting <b>January 2027</b>, in AI / ML, backend or software engineering.<br/>
  📧 <a href="mailto:mayankranjan1606@gmail.com"><b>mayankranjan1606@gmail.com</b></a> · 💼 <a href="https://www.linkedin.com/in/mayankranjan1606/"><b>LinkedIn</b></a>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:00C6FF,100:7F00FF&height=120&section=footer" width="100%" />
</p>
