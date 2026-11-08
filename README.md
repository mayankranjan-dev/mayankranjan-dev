<!-- GitHub profile repository: mayankranjan-dev/mayankranjan-dev -->
<p align="center">
  <img src="./banner.svg" alt="Mayank Ranjan — Building useful technology, end to end" width="100%" />
</p>

<p align="center">
  <strong>Computer Science undergraduate · ADYP University, Pune · Class of 2027</strong><br/>
  I turn ideas into working software, with an emphasis on thoughtful design, reliable implementation, and measurable results.
</p>

<p align="center">
  <a href="mailto:mayankranjan.dev@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-DB4437?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://www.linkedin.com/in/mayankranjan1606/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://mayank-portfolio-nine-navy.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-Explore-18181B?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" /></a>
  <a href="./resume.pdf"><img src="https://img.shields.io/badge/Resume-View_PDF-0F766E?style=for-the-badge&logo=adobeacrobatreader&logoColor=white" alt="Resume PDF" /></a>
</p>

---

## About

I'm a final-year **B.Tech Computer Science** student at **ADYP University, Pune** (expected graduation: May 2027). I enjoy working across the development lifecycle: identifying a problem, choosing an approach, building the solution, and validating how well it performs.

My projects span **software development, APIs, machine learning, automation, and data**. I focus on fundamentals—**data structures, object-oriented design, databases, testing, and security**—alongside practical tools such as Python, FastAPI, Docker, and GitHub Actions.

## Selected results

<table align="center">
  <tr>
    <td align="center" width="25%"><strong>374</strong><br/><sub>passing tests · CodeRev Bot</sub></td>
    <td align="center" width="25%"><strong>169 ms</strong><br/><sub>CPU scoring per posting · JobSail</sub></td>
    <td align="center" width="25%"><strong>~95%</strong><br/><sub>cross-validated routing accuracy · SwitchOne</sub></td>
    <td align="center" width="25%"><strong>10/10</strong><br/><sub>hand-written scam examples flagged · JobSail</sub></td>
  </tr>
</table>

<sub>Figures are from project-specific tests: SwitchOne was evaluated on 150 hand-labeled prompts, and the 10 JobSail examples were hand-written adversarial cases. They are not general production benchmarks.</sub>

## Featured projects

### 01 · [CodeRev Bot](https://github.com/mayankranjan-dev/coderev) — Automated pull-request reviews

**Python · FastAPI · Ollama · React · Docker · GitHub Actions**

Built a GitHub pull-request review service that uses a **locally hosted LLM** to return structured feedback with file locations, severity, and suggested fixes.

- Implemented **HMAC-SHA256 webhook verification**, API-key authentication, and per-IP rate limiting.
- Added a **retry queue** for unavailable or timed-out models and a **Judge0 sandbox** for code execution.
- Validated the system with **374 passing tests** and a Docker health check.

### 02 · [JobSail](https://github.com/mayankranjan-dev/JobSail) — Job discovery and scam-risk detection

**Python · FastAPI · PyTorch · DistilBERT · SQLite · React · TypeScript**

Created a job aggregation pipeline with a **fine-tuned text classifier** to assess suspicious postings, plus rules that can escalate risk when known scam patterns appear.

- Integrated job feeds, **30-minute refreshes**, and SHA-256-based duplicate detection.
- Achieved **169 ms CPU scoring per posting** in project testing, with **52 passing tests**.
- Flagged **10/10 hand-written adversarial scam examples**; deterministic guardrails increased risk on **3/10** of them.

### 03 · [SwitchOne](https://github.com/mayankranjan-dev/switchone) — Cost-aware language-model routing

**Python · FastAPI · scikit-learn · Ollama**

Designed a router that selects between local, free-tier, and premium language models based on estimated prompt complexity, with fallback and escalation handling.

- Used **logistic regression** and ten engineered features instead of an additional LLM call for routing.
- Reached **~95% cross-validated accuracy** on **150 hand-labeled prompts** and **under 1 ms routing time** in project testing.
- Configured CI to require a **minimum 80% test-coverage threshold**.

<details>
  <summary><strong>More work — RAG Resume Screener</strong></summary>
  <br/>
  <a href="https://github.com/mayankranjan-dev/rag-resume-screener"><strong>RAG Resume Screener</strong></a> explores resume–job-description matching using embeddings, vector retrieval, and LLM-generated explanations.
</details>

## Skills & tools

| Area | Technologies |
| :-- | :-- |
| **Programming** | Python · SQL · C++ · C · JavaScript · TypeScript |
| **Backend & databases** | FastAPI · REST APIs · SQLAlchemy · SQLite · API security |
| **AI & data** | PyTorch · Hugging Face Transformers · scikit-learn · Ollama · Pandas · NLP · Tableau · Excel |
| **Frontend** | React · Vite |
| **Engineering tools** | Git · GitHub Actions · Docker · pytest · CI/CD · Judge0 |
| **Core foundations** | DSA · OOP · DBMS · Operating Systems · Computer Networks · Problem Solving |

## Education & credentials

**B.Tech, Computer Science** — ADYP University, Pune  
*August 2023 – May 2027 (expected)*

**Certifications and professional learning**
- **Oracle Cloud Infrastructure Certified AI Foundations Associate** — Oracle (2026)
- **SQL (Intermediate)** — HackerRank (2026)
- **AI Skills Passport** — EY & Microsoft
- **Claude 101** — Anthropic
- **Deloitte Australia Data Analytics Job Simulation** — Forage (2025, virtual simulation)

## Connect

I enjoy exchanging ideas, learning from other builders, and contributing to projects that solve real problems. Whether you want to discuss my work, collaborate, or explore an opportunity, feel free to reach out.

<p align="center">
  <a href="mailto:mayankranjan.dev@gmail.com"><strong>Email</strong></a> &nbsp;·&nbsp;
  <a href="https://www.linkedin.com/in/mayankranjan1606/"><strong>LinkedIn</strong></a> &nbsp;·&nbsp;
  <a href="https://mayank-portfolio-nine-navy.vercel.app/"><strong>Portfolio</strong></a> &nbsp;·&nbsp;
  <a href="./resume.pdf"><strong>Resume</strong></a>
</p>

<p align="center">
  <img src="./footer.svg" alt="Thanks for visiting. Explore the projects or start a conversation." width="100%" />
</p>
