<!-- ===================== HEADER ===================== -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:7F00FF,100:00C6FF&height=190&section=header&text=Mayank%20Ranjan&fontSize=58&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Aspiring%20AI%20Engineer%20%7C%20Backend%20%26%20LLM%20Applications&descSize=18&descAlignY=58" width="100%" alt="Mayank Ranjan" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=36BCF7&center=true&vCenter=true&width=650&lines=I+build+LLM-powered+tools+that+actually+ship;FastAPI+%7C+Local+LLMs+%7C+RAG+%7C+Docker;Open+to+internships+from+January+2027" alt="I build LLM-powered tools that actually ship" />
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

<!-- ===================== AT A GLANCE ===================== -->
## ⚡ At a glance

<table align="center">
  <tr>
    <td align="center" width="150"><h2>3</h2>end-to-end<br/>AI projects</td>
    <td align="center" width="150"><h2>374</h2>passing tests<br/><sub>CodeRev Bot</sub></td>
    <td align="center" width="150"><h2>169 ms</h2>per prediction on CPU<br/><sub>JobSail</sub></td>
    <td align="center" width="150"><h2>10 / 10</h2>adversarial scams caught<br/><sub>JobSail</sub></td>
    <td align="center" width="150"><h2>~95%</h2>routing accuracy in &lt;1 ms<br/><sub>SwitchOne</sub></td>
  </tr>
</table>

---

<!-- ===================== ABOUT ===================== -->
## 🙋 About me

I'm a final-year Computer Science student working toward **AI engineering**. I enjoy the part after the model works in a notebook: wrapping it in an API, securing it, testing it, packaging it with Docker and running it in CI.

My projects focus on **LLM applications**. I built an AI code reviewer that runs on a local model, a scam-job detector on a fine-tuned DistilBERT, and a router that sends each prompt to the cheapest LLM that can handle it. In each one, I measured the results instead of guessing: latency, accuracy and how the system behaves on tricky inputs.

**Right now I'm going deeper into:** RAG pipelines, LLM evaluation and guardrails, and production-ready FastAPI services.

---

<!-- ===================== PROJECTS ===================== -->
## 🚀 Featured projects

### 🔍 [CodeRev Bot](https://github.com/mayankranjan-dev/coderev): AI pull-request reviewer on a local LLM

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

- **Problem:** code reviews are slow, and sending private code to a paid AI API isn't always an option.
- **What I built:** a FastAPI service that reviews GitHub pull requests with a local Ollama model. It returns structured findings: severity, file, lines and a suggested fix. It also has a manual review mode and a Judge0-sandboxed "Run Code" feature.
- **Security:** HMAC-SHA256 webhook verification, API-key authentication and per-IP rate limiting.
- **Key decision:** local LLMs can be offline or slow, so I added a retry queue. Reviews wait and retry instead of failing.
- **Result:** ✅ **374 passing tests** and a Docker image that reaches healthy status.

### 🛡️ [JobSail](https://github.com/mayankranjan-dev/jobsail): job aggregator that catches scam postings

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)

- **Problem:** fake job postings target students and freshers.
- **What I built:** a job aggregator that scores every posting with a fine-tuned DistilBERT scam classifier, served through FastAPI and SQLite.
- **Key decision:** a model alone can be fooled, so I added rule-based guardrails that can only *raise* a risk level, never lower it. They raised risk on 3 of 10 adversarial postings.
- **Result:** ⚡ **169 ms** per posting on CPU, 🎯 **10 of 10** hand-written adversarial scams flagged as suspicious or worse, and ✅ **52 passing tests**.

### 🔀 [SwitchOne](https://github.com/mayankranjan-dev/switchone): cost-aware LLM router

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)

- **Problem:** sending every prompt to a premium LLM wastes money, because many prompts are simple.
- **What I built:** a FastAPI service that sends each prompt to a local, free-tier or premium model, with fallback when a model fails and one-step escalation.
- **Key decision:** routing must be nearly free, so I used logistic regression on 10 hand-built features instead of asking another LLM. It was trained on 150 hand-labeled prompts.
- **Result:** ⚡ **under 1 ms** per routing decision at 🎯 **about 95%** cross-validated accuracy, with CI enforcing **80% test coverage**.

### 📄 [RAG Resume Screener](https://github.com/mayankranjan-dev/rag-resume-screener): match resumes to a job description

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-6E40C9?style=flat-square)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6446?style=flat-square)
![sentence-transformers](https://img.shields.io/badge/sentence--transformers-0A66C2?style=flat-square)

- Embeds resumes and a job description, searches them with a vector database, and uses an LLM to rank and explain the best matches.

---

<!-- ===================== SKILLS ===================== -->
## 🛠️ Tech stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=py,fastapi,docker,githubactions,git,sqlite,react,js,java,cpp&perline=10" alt="Python, FastAPI, Docker, GitHub Actions, Git, SQLite, React, JavaScript, Java, C++" />
</p>

| Area | Skills |
|---|---|
| 🤖 **AI / ML** | RAG, ChromaDB, sentence-transformers, Hugging Face Transformers, scikit-learn, Ollama (local LLMs), LLM evaluation |
| ⚙️ **Backend** | FastAPI, REST APIs, SQLAlchemy, pytest, HMAC-SHA256 and API-key auth, rate limiting |
| 💬 **Languages** | Python, SQL, JavaScript, Java, C, C++ |
| 📊 **Data & DevOps** | SQLite, Pandas, Tableau, Excel, Git, GitHub Actions, Docker |
| 🎨 **Frontend** | React, Vite, Tailwind CSS |

---

<!-- ===================== EDUCATION, EXPERIENCE, CERTS ===================== -->
## 🎓 Education and experience

**B.Tech in Computer Science**, ADYP University, Pune · *Aug 2023 – May 2027*<br/>
<sub>Coursework: Data Structures and Algorithms · DBMS · Operating Systems · Computer Networks · Software Reliability · Software Analysis · Java · C and C++</sub>

**Deloitte Data Analytics Job Simulation**, Forage (virtual) · *June 2025*<br/>
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

<!-- ===================== CONTACT ===================== -->
## 📫 Let's work together

<p align="center">
  I'm looking for an internship from <b>January 2027</b> in <b>AI / ML</b>, <b>backend</b> or <b>software engineering</b>.<br/>
  If your team is hiring, or you'd like to talk about AI engineering, I'd love to hear from you.<br/><br/>
  📧 <a href="mailto:mayankranjan1606@gmail.com"><b>mayankranjan1606@gmail.com</b></a> · 💼 <a href="https://www.linkedin.com/in/mayankranjan1606/"><b>LinkedIn</b></a> · 📄 <a href="https://github.com/mayankranjan-dev/mayankranjan-dev/blob/main/resume.pdf"><b>Resume</b></a>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:00C6FF,100:7F00FF&height=110&section=footer" width="100%" alt="" />
</p>
