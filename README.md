# Workshop Slides

A collection of presentation slides from workshops focused on **Artificial Intelligence** and **Finance**. These materials were created and delivered as educational workshops covering practical AI development techniques and real-world macroeconomic investing strategies.

---

## 📁 Repository Structure

```
Workshop-Slides/
├── AI/
│   ├── Agentic_Coding_Workshop.pdf
│   └── MedAgent Presentation - FINAL.pdf
└── finance/
    ├── MIA Lecture Complete Lecture Module.pptx.pdf
    └── Workshop_Presentation.pptx.pdf
```

---

## 🤖 AI Workshops

### 1. Agentic Coding Workshop (2026)
**File:** [`AI/Agentic_Coding_Workshop.pdf`](./AI/Agentic_Coding_Workshop.pdf) · 42 slides

A hands-on workshop on **agentic coding** — the practice of building AI agents that can plan, act, self-check, and retry in order to automate real software workflows.

**Topics covered:**
- **The history of AI-assisted coding** — from Stack Overflow snippet hunting (2010s) → GitHub Copilot autocomplete (2021) → ChatGPT copy-paste (2022–23) → LLMs that read and refactor entire repos (2023–24) → agents that write, run, and ship autonomously (2025–today)
- **Why agentic coding matters** — most knowledge work (tickets, reports, code reviews, glue code) is repetitive; agents take goals instead of keystrokes, eliminating context switches
- **What an agent actually is** — a reasoning loop: Goal → Tools → Check → Retry, with judgment at each step
- **OpenClaw** — a demo agent project showcasing real-world agentic automation
- **How to build an agent** — practical step-by-step guide to constructing your own agentic pipeline

---

### 2. MedAgent — Trustworthy Personalized Consumer Health Search (SIEDS 2026)
**File:** [`AI/MedAgent Presentation - FINAL.pdf`](./AI/MedAgent%20Presentation%20-%20FINAL.pdf)

A research presentation submitted to **SIEDS 2026** introducing **MedAgent**, a multi-agent AI system designed to solve the problem of untrustworthy, generic, and hard-to-understand consumer health information online.

**Background & Motivation:**
- 58.5% of U.S. adults search for health information online
- 88% have less than proficient health literacy
- Low health literacy costs the U.S. healthcare system $106–238 billion annually
- Plain LLMs hallucinate in clinical decision support at rates of 50–82%; RAG improves accuracy by ~6.6 percentage points

**System Architecture — Four Specialized Agents:**
| Agent | Role |
|-------|------|
| **Agent A** — Query Understanding | Classifies query into 1 of 20 health categories and expands it using HyDE |
| **Agent B** — Retrieval Planning | Builds a personalized user knowledge subgraph and selects sources |
| **Agent C** — Evidence Synthesis | Performs hybrid search and generates literacy-tailored LLM responses |
| **Agent D** — Verification | Applies confidence scoring, uncertainty flags, and medical disclaimers |

**Key Design Principles:**
- **Multi-agent decomposition** — interpretable and modular pipeline
- **Tiered source strategy** — distinguishes authoritative medical literature from community Q&A
- **Personal Health Knowledge Graphs** — per-user subgraph built from history drives context-aware retrieval and reranking

**Authors:** Ashleyn Castelino, Blazej Madrzyk, Keshav Trikha, Aram Bahrini  
*(Gies College of Business & Siebel School of Computing and Data Science)*

---

## 💰 Finance Workshops

### 3. Overview of Global Financial Markets
**File:** [`finance/Workshop_Presentation.pptx.pdf`](./finance/Workshop_Presentation.pptx.pdf)

A comprehensive introductory workshop on **global financial markets**, covering macro trends, portfolio construction, and key concepts for investors navigating today's environment.

**Topics covered:**
- **Market Background** — The S&P 500's ~178% return since 2015 vs. the Information Technology sector's 450%+ surge; the "Magnificent Seven" tech companies' 698% combined return (2015–2024), nearly 4× the average S&P 500 company
- **Market Concentration** — Top 7 tech companies grew from 12% to 34%+ of the S&P 500 between 2015 and 2025
- **Past Macro Environment** — Zero Interest Rate Policy (ZIRP), supply chain globalization, Dollar Exceptionalism (DXY rising from ~98 in 2016 to peaks above 114 in 2022)
- **Key Economic Data Points:**
  - S&P 500 average annual return since 2015: ~12.9%
  - Gold CAGR over last decade: ~13.6% (from $1,060/oz in 2016 to ~$4,320/oz in 2026)
  - U.S. national debt growth: $19 trillion (2016) → $38+ trillion (2026)
  - U.S. debt-to-GDP ratio: ~104% (2016) → 120%+ (today)
- **Key Concepts & Terminology** — Core vocabulary for understanding financial markets
- **Introduction to the Federal Reserve** — The Fed's tools and how monetary policy affects markets
- **Portfolio Construction** — Principles for building and managing an investment portfolio

---

### 4. Macro Investing Association (MIA) — Complete Lecture Module
**File:** [`finance/MIA Lecture Complete Lecture Module.pptx.pdf`](./finance/MIA%20Lecture%20Complete%20Lecture%20Module.pptx.pdf)

A full-semester lecture guide from the **Macro Investing Association (MIA)**, an investment club focused on investment research, financial analysis, and macroeconomic strategy across multiple asset classes. Designed to take analysts from beginner to portfolio manager level.

**Full Curriculum:**

| Module | Topics |
|--------|--------|
| **Intro to Macro Investing** | Top-down approach, asset class overview (equities, fixed income, commodities, FX, crypto, alternatives), discretionary vs. systematic vs. thematic macro strategies (Soros vs. Dalio) |
| **Macroeconomic Indicators** | GDP, CPI, PCE, unemployment rate — how to read and apply them |
| **Central Banks & Monetary/Fiscal Policy** | Fed tools, interest rate policy, fiscal stimulus |
| **Fixed Income** | Introduction to bonds, government bonds, corporate bonds, credit markets |
| **Equities** | Business cycle investing, sector rotation, developed and emerging markets |
| **Commodity Markets** | Energy, industrials, agriculture, gold |
| **FX & Crypto Markets** | Fundamental and macro drivers of currencies and crypto assets |
| **Futures & Options** | Derivatives basics for macro positioning |
| **Technical Analysis** | Chart-based tools to complement macro views |

**Club Goals:**
- Develop real-world investment skills through hands-on research
- Gain experience across investment research, financial analysis, and macroeconomic strategy
- Connect with industry professionals and explore career opportunities in finance
- Top-performing analysts are promoted to Portfolio Manager (PM) roles

---

## 🚀 Getting Started

Browse the slides by navigating into the relevant folder:
- [`/AI`](./AI) — Artificial Intelligence workshop materials
- [`/finance`](./finance) — Finance workshop materials

All slides are provided as PDF files and can be opened with any standard PDF viewer.
