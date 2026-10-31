<!-- Banner and footer are stored in this repo, so they always load. -->
<p align="center">
  <img src="banner.svg" width="100%" alt="Mayank Ranjan · Aspiring AI Engineer · Backend & LLM Applications · Open to internships from January 2027" />
</p>

<p align="center">
  <b>Final-year B.Tech Computer Science student</b> at ADYP University, Pune.<br/>
  I turn machine learning models into secure, tested backend services.<br/>
  🎯 <b>Looking for a Backend / Applied AI / Software Engineering internship from January 2027.</b>
</p>

<p align="center">
  <a href="mailto:mayankranjan1606@gmail.com"><img src="https://img.shields.io/badge/Email-Contact_me-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://www.linkedin.com/in/mayankranjan1606/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://github.com/mayankranjan-dev/mayankranjan-dev/blob/main/resume.pdf"><img src="https://img.shields.io/badge/Resume-View_PDF-2ea44f?style=for-the-badge&logo=adobeacrobatreader&logoColor=white" alt="Resume" /></a>
</p>

---

## ⚡ At a glance

<table align="center">
  <tr>
    <td align="center" width="150"><h3>3</h3>end-to-end AI projects<br/><sub>FastAPI + models</sub></td>
    <td align="center" width="150"><h3>374</h3>passing tests<br/><sub>CodeRev Bot</sub></td>
    <td align="center" width="150"><h3>169 ms</h3>per prediction on CPU<br/><sub>JobSail</sub></td>
    <td align="center" width="150"><h3>10 / 10</h3>adversarial scams caught<br/><sub>JobSail</sub></td>
    <td align="center" width="150"><h3>~95%</h3>routing accuracy in under 1 ms<br/><sub>SwitchOne</sub></td>
  </tr>
</table>

---

## 🙋 About me

I'm a final-year Computer Science student working toward **AI engineering**. I enjoy the part after the model works in a notebook: wrapping it in an API, securing it, testing it, packaging it with Docker and running it in CI.

My projects focus on **LLM applications**: an AI code reviewer that runs on a local model, a scam-job detector built on a fine-tuned DistilBERT, and a router that sends each prompt to the cheapest LLM that can handle it. In each one I measured the results instead of guessing: latency, accuracy and behavior on tricky inputs.

**Going deeper into:** RAG pipelines · LLM evaluation and guardrails · production-ready FastAPI services

---

## 🚀 Featured projects

### 🔍 [CodeRev Bot](https://github.com/mayankranjan-dev/coderev) · AI pull-request reviewer on a local LLM

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

- **Problem**: Code reviews are slow, and sending private code to a paid AI API isn't always an option.
- **What I built**: A FastAPI service that reviews GitHub pull requests with a local Ollama model and returns structured findings: severity, file, lines and a suggested fix. Includes a manual review mode and a Judge0-sandboxed "Run Code" feature.
- **Security**: HMAC-SHA256 webhook verification, API-key authentication and per-IP rate limiting.
- **Key decision**: Local LLMs can be offline or slow, so I added a retry queue. Reviews wait and retry instead of failing.
- **Result**: ✅ **374 passing tests** and a Docker image that reaches healthy status.

### 🛡️ [JobSail](https://github.com/mayankranjan-dev/jobsail) · Job aggregator that catches scam postings

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)

- **Problem**: Fake job postings target students and freshers.
- **What I built**: A job aggregator that scores every posting with a fine-tuned DistilBERT scam classifier, served through FastAPI and SQLite.
- **Key decision**: A model alone can be fooled, so I added rule-based guardrails that can only *raise* a risk level, never lower it. They raised risk on 3 of 10 adversarial postings.
- **Result**: ⚡ **169 ms** per posting on CPU · 🎯 **10 of 10** hand-written adversarial scams flagged · ✅ **52 passing tests**

### 🔀 [SwitchOne](https://github.com/mayankranjan-dev/switchone) · Cost-aware LLM router

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)

- **Problem**: Sending every prompt to a premium LLM wastes money, because many prompts are simple.
- **What I built**: A FastAPI service that sends each prompt to a local, free-tier or premium model, with fallback when a model fails and one-step escalation.
- **Key decision**: Routing must be nearly free, so I used logistic regression on 10 hand-built features instead of calling another LLM. Trained on 150 hand-labeled prompts.
- **Result**: ⚡ **Under 1 ms** per decision · 🎯 **~95%** cross-validated accuracy · ✅ CI enforces **80% test coverage**

### 📄 [RAG Resume Screener](https://github.com/mayankranjan-dev/rag-resume-screener) · Match resumes to a job description

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-6E40C9?style=flat-square)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6446?style=flat-square)
![sentence-transformers](https://img.shields.io/badge/sentence--transformers-0A66C2?style=flat-square)

Embeds resumes and a job description, searches them in a vector database, and uses an LLM to rank and explain the best matches.

---

## 🛠️ Tech stack

| Area | Tools |
|---|---|
| 🤖 **AI / ML** | ![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black) ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white) ![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white) ![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6446?style=flat-square) ![RAG](https://img.shields.io/badge/RAG-6E40C9?style=flat-square) ![sentence-transformers](https://img.shields.io/badge/sentence--transformers-0A66C2?style=flat-square) ![LLM evaluation](https://img.shields.io/badge/LLM_evaluation-374151?style=flat-square) |
| ⚙️ **Backend** | ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![REST APIs](https://img.shields.io/badge/REST_APIs-374151?style=flat-square) ![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white) ![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white) ![Auth & rate limiting](https://img.shields.io/badge/Auth_%26_rate_limiting-374151?style=flat-square) |
| 💬 **Languages** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=sqlite&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black) ![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white) |
| 📊 **Data & DevOps** | ![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white) ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white) ![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white) ![Excel](https://img.shields.io/badge/Excel-217346?style=flat-square&logo=microsoftexcel&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) |
| 🎨 **Frontend** | ![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white) ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white) |

---

## 🎓 Education and experience

**B.Tech in Computer Science** · ADYP University, Pune · *Aug 2023 – May 2027*<br/>
<sub>Coursework: Data Structures and Algorithms · DBMS · Operating Systems · Computer Networks · Software Reliability · Software Analysis · Java · C and C++</sub>

**Deloitte Data Analytics Job Simulation** · Forage (virtual) · *June 2025*<br/>
<sub>Built a Tableau dashboard and completed Excel data analysis tasks.</sub>

## 📜 Certifications

| Certification | Issuer | Year |
|---|---|---|
| 🏅 OCI Certified **AI Foundations Associate** | Oracle | 2026 |
| 🏅 **SQL (Intermediate)** | HackerRank | 2026 |
| 🏅 **Python (Basic)** | HackerRank | 2026 |
| 🏅 **AI Skills Passport** | EY and Microsoft | |
| 🏅 **Claude 101** | Anthropic | |

---

## 📫 Let's work together

<p align="center">
  I'm looking for an internship from <b>January 2027</b> in <b>AI / ML</b>, <b>backend</b> or <b>software engineering</b>.<br/>
  If your team is hiring, or you'd like to talk about AI engineering, I'd love to hear from you.<br/><br/>
  📧 <a href="mailto:mayankranjan1606@gmail.com"><b>mayankranjan1606@gmail.com</b></a> · 💼 <a href="https://www.linkedin.com/in/mayankranjan1606/"><b>LinkedIn</b></a> · 📄 <a href="https://github.com/mayankranjan-dev/mayankranjan-dev/blob/main/resume.pdf"><b>Resume</b></a>
</p>

<p align="center">
  <img src="footer.svg" width="100%" alt="Thanks for visiting" />
</p>
