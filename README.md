<picture>
  <source media="(max-width: 700px)" srcset="./assets/shiverion-signal-mobile.svg">
  <img src="./assets/shiverion-signal-desktop.svg" width="100%" alt="Muhammad Iqbal Hilmy Izzulhaq — building evidence-first agentic AI, retrieval systems, and applied machine learning products">
</picture>

<h1 align="center">AI systems that can show their work.</h1>

<p align="center">
  I build agentic AI, trustworthy retrieval pipelines, and production AI products —<br>
  from benchmark design to the interface people actually use.
</p>

<p align="center">
  <a href="https://shiverion.com/"><img alt="Portfolio" src="https://img.shields.io/badge/PORTFOLIO-SHIVERION.COM-0B1220?style=for-the-badge&amp;logo=safari&amp;logoColor=67E8F9"></a>
  <a href="https://github.com/Shiverion"><img alt="GitHub" src="https://img.shields.io/badge/GITHUB-SHIVERION-0B1220?style=for-the-badge&amp;logo=github&amp;logoColor=F8FAFC"></a>
  <a href="https://www.linkedin.com/in/izzulhaq-iqbal/"><img alt="LinkedIn" src="https://img.shields.io/badge/LINKEDIN-CONNECT-0B1220?style=for-the-badge&amp;logo=linkedin&amp;logoColor=60A5FA"></a>
  <a href="https://medium.com/@miqbal.izzulhaq"><img alt="Medium" src="https://img.shields.io/badge/MEDIUM-READ-0B1220?style=for-the-badge&amp;logo=medium&amp;logoColor=F8FAFC"></a>
  <a href="https://openreview.net/forum?id=46hzq45LPE"><img alt="OpenReview paper" src="https://img.shields.io/badge/OPENREVIEW-PAPER-0B1220?style=for-the-badge&amp;logo=openreview&amp;logoColor=A78BFA"></a>
</p>

<p align="center">
  <samp>
    <a href="#hello-im-iqbal">ABOUT</a> ·
    <a href="#signature-systems">WORK</a> ·
    <a href="#technical-range">STACK</a> ·
    <a href="#project-constellation">ALL PROJECTS</a> ·
    <a href="#connect">CONNECT</a>
  </samp>
</p>

---

## Hello, I'm Iqbal.

I'm **Muhammad Iqbal Hilmy Izzulhaq** (`@Shiverion`), an AI engineer and data scientist working where **agents, retrieval, evaluation, and product engineering** meet.

My projects move between Indonesian legal-document research, MCP tool servers, real-time voice interfaces, fine-tuned language models, and leakage-safe prediction pipelines. The common thread is simple: make the system useful, make its boundaries visible, and measure whether it actually works.

> **Working principle:** AI should know its limits, show its evidence, and earn its place in a real workflow.

| Outcome | Measured signal |
| ---: | --- |
| **300** | Human-reviewed legal QA pairs in VerdictBench |
| **16–25×** | Dense RAG cost advantage observed in the benchmark |
| **40% → 73.5%** | Valid SQL improvement after QLoRA fine-tuning |
| **98% ↓ · 100× ↑** | Memory reduction and peak speedup in dataframe tests |

## What I build

| Layer | What I work on | What makes it credible |
| --- | --- | --- |
| **Agentic systems** | MCP servers, tool orchestration, multi-agent workflows | Explicit data boundaries, evidence traces, deterministic evals |
| **Retrieval & LLM evaluation** | RAG, long context, hybrid search, fine-tuning | Human-reviewed benchmarks, ablations, cost and failure analysis |
| **Production AI products** | Voice, document intelligence, auth, quotas, persistence | Deployed workflows with real product surfaces and operational constraints |
| **Applied ML** | Forecasting, classification, model interpretation | Leakage-safe backtests, calibration, model cards, interpretable outputs |

## Signature systems

### 01 / [VerdictBench](https://github.com/Shiverion/VerdictBench-LCvsRAG)

`RESEARCH` `RETRIEVAL` `EVALUATION`

Long Context, Dense RAG, and Multi-Stage RAG tested on Indonesian Constitutional Court verdicts.

> **Signal:** 50 verdicts, 300 reviewed QA pairs, and Dense RAG statistically tied with Long Context on gold-evidence faithfulness while costing 16–25× less.

`Python` `FAISS` `BM25` `IndoBERT` · [Repository ↗](https://github.com/Shiverion/VerdictBench-LCvsRAG) · [Paper ↗](https://openreview.net/forum?id=46hzq45LPE)

### 02 / [EPC Tender Screening MCP](https://github.com/Shiverion/epc-tender-screening-mcp-showcase)

`AGENT TOOLING` `MCP` `EVIDENCE`

An agent-agnostic tool server for reviewable EPC tender bid/no-bid screening.

> **Signal:** 10 MCP tools, orchestration through `screen_tender`, evidence traces, deterministic evals, and SSRF-conscious public-source search.

`TypeScript` `MCP` `Zod` `HTTP + stdio` · [Repository ↗](https://github.com/Shiverion/epc-tender-screening-mcp-showcase)

### 03 / [World Cup 2026 Engine](https://github.com/Shiverion/ml-world-cup-prediction)

`APPLIED ML` `FORECASTING` `SIMULATION`

A time-aware match and tournament forecasting pipeline built for the 48-team World Cup format.

> **Signal:** 56.0% accuracy, 0.973 log loss, and 0.573 Brier score across 384 chronologically held-out World Cup matches; the completed 2026 snapshot produced 44/72 correct group-match calls, 26/32 correct knockout teams, and 24/31 evaluated knockout advances; all 495 Annex C bracket assignments are implemented.

`Python` `scikit-learn` `Elo` `Monte Carlo` · [Repository ↗](https://github.com/Shiverion/ml-world-cup-prediction)

### 04 / [Distill / Paprika](https://distill.shiverion.com)

`AI PRODUCT` `DOCUMENT INTELLIGENCE` `LEARNING`

A production paper-to-insights product that turns a PDF or paper URL into formats people can study, present, and share.

> **Signal:** seven output types, PDF or URL input, audience tuning, interactive learning modes, Firebase auth, and credit controls.

`Next.js` `TypeScript` `Gemini` `Firebase` · [Live demo ↗](https://distill.shiverion.com) · **Source:** private

## Latest data analysis

Three football projects show the same analytical discipline at different scales: define a comparison population, protect the time boundary, quantify uncertainty, and stop where the evidence stops.

| Project | Question | Evidence-led answer | Links |
| --- | --- | --- | --- |
| **World Cup 2026 Prediction Engine** | Can match probabilities remain useful when propagated through a new 48-team format? | Across 384 held-out matches, the model matched Elo-Poisson at 56.0% accuracy while improving log loss and Brier score by roughly 1.3%. In the completed 2026 snapshot it made 44/72 group-match calls, identified 26/32 knockout teams, and correctly called 24/31 evaluated knockout advances. | [Repo](https://github.com/Shiverion/ml-world-cup-prediction) · [Portfolio](https://shiverion.com/projects/world-cup-prediction) |
| **England vs France: Third-Place Match Analysis** | Was the 6–4 bronze final simply a low-effort exhibition? | Ten goals came from 5.33 xG, yet high-intensity running and pressure increased while collective control deteriorated. The defensible reading is **high effort, weak coordination**. | [Repo](https://github.com/Shiverion/england-france-third-place-analysis) · [Report](https://github.com/Shiverion/england-france-third-place-analysis/blob/main/output/england_france_2026_third_place_insights_v2.md) · [Notebook](https://github.com/Shiverion/england-france-third-place-analysis/blob/main/output/jupyter-notebook/england_france_2026_third_place_analysis_v2.ipynb) · [Portfolio](https://shiverion.com/projects/england-france-third-place-analysis) |
| **Argentina Comeback Analysis** | How rare was Argentina's late 3–2 comeback against Egypt? | World Cup history contained 0 wins from 278 comparable two-goal deficits at 70 minutes; selected club data places the event near 0.14–0.28%, without turning rarity into a claim of officiating bias. | [Latest branch](https://github.com/Shiverion/argentina-comeback-analysis/tree/codex/comeback-penalty-sequences) · [Report](https://github.com/Shiverion/argentina-comeback-analysis/blob/codex/comeback-penalty-sequences/results/analysis_report.md) · [Notebook](https://github.com/Shiverion/argentina-comeback-analysis/blob/codex/comeback-penalty-sequences/output/jupyter-notebook/argentina_egypt_comeback_analysis.ipynb) · [Portfolio](https://shiverion.com/projects/argentina-comeback-analysis) |

## Technical range

| Domain | Tools and technologies |
| --- | --- |
| **Agents & automation** | `MCP` · `OpenAI Agents SDK` · `LangGraph` · `CrewAI` · `n8n` |
| **LLMs & retrieval** | `Gemini` · `OpenAI` · `Hugging Face` · `FAISS` · `BM25` · `IndoBERT` · `QLoRA` |
| **Product engineering** | `Next.js` · `React` · `FastAPI` · `Firebase / Firestore` · `WebRTC` · `Tauri` |
| **ML & data** | `PyTorch` · `scikit-learn` · `Pandas` · `Polars` · `DuckDB` · `SQL` |
| **Delivery** | `GCP` · `Cloud Run` · `Vercel` · `Docker` · `CI/CD` |

## Project constellation

<details>
<summary><strong>Explore the complete project index</strong> — public repositories, live products, research, and selected private work</summary>

### Research, evaluation & applied ML

| Project | Signal | Links |
| --- | --- | --- |
| **VerdictBench** | Long Context vs Dense and Multi-Stage RAG on Indonesian legal decisions; 50 verdicts and 300 reviewed QA pairs. | [Repo](https://github.com/Shiverion/VerdictBench-LCvsRAG) · [Paper](https://openreview.net/forum?id=46hzq45LPE) |
| **World Cup 2026 Prediction Engine** | 384-match chronological backtest, 44/72 current group-match calls, 24/31 evaluated knockout advances, proper-score evaluation, model registry, and 48-team Monte Carlo simulation. | [Repo](https://github.com/Shiverion/ml-world-cup-prediction) |
| **England vs France: Third-Place Match Analysis** | Multi-source holdout analysis separates high physical effort from weak collective defensive control. | [Repo](https://github.com/Shiverion/england-france-third-place-analysis) · [Report](https://github.com/Shiverion/england-france-third-place-analysis/blob/main/output/england_france_2026_third_place_insights_v2.md) |
| **Argentina Comeback Analysis** | Historical rarity, leakage-safe modeling, and counterfactual sensitivity with explicit evidence gates. | [Latest branch](https://github.com/Shiverion/argentina-comeback-analysis/tree/codex/comeback-penalty-sequences) · [Report](https://github.com/Shiverion/argentina-comeback-analysis/blob/codex/comeback-penalty-sequences/results/analysis_report.md) |
| **Text2SQL Fine-tuning** | End-to-end QLoRA and execution-based evaluation for a ≤3B SQL-generation model. | [Repo](https://github.com/Shiverion/text2sql-finetuning) · [Adapter](https://huggingface.co/Shiverion/qwen2.5-coder-1.5b-bird-qlora) |
| **Pandas vs Polars vs DuckDB** | Reproducible dataframe-engine benchmark on 13.1M SUSENAS 2024 rows. | [Repo](https://github.com/Shiverion/dataframe-engine-comparison) |
| **Galaxy Morphology Classification** | ResNet18 with Grad-CAM and Integrated Gradients for interpretable scientific imaging. | [Repo](https://github.com/Shiverion/galaxy-morphology-classification) |
| **IBM Applied Data Science Capstone** | Falcon 9 landing prediction from data collection through dashboarding and model comparison. | [Repo](https://github.com/Shiverion/IBM-Applied-Data-Science-Capstone) |
| **Telco Churn Analysis** | Cost-aware churn modeling optimized for recall, reaching **93.7% recall**. | [Repo](https://github.com/Shiverion/Telco-Churn-Analysis) |
| **Airbnb Data Analysis** | Bangkok listing and pricing analysis aimed at revenue optimization. | [Repo](https://github.com/Shiverion/AirBnB-Data-Analysis) |

### Agents & production AI

| Project | Signal | Links |
| --- | --- | --- |
| **EPC Tender Screening MCP** | Evidence-based tender screening through 10 MCP tools and reviewable orchestration. | [Repo](https://github.com/Shiverion/epc-tender-screening-mcp-showcase) |
| **Distill / Paprika** | Academic papers transformed into seven interactive learning and communication formats. | [Live](https://distill.shiverion.com) · Source private |
| **InterviewMate AI** | Real-time voice interviewing and automated candidate evaluation over OpenAI Realtime and WebRTC. | [Live](https://interviewmate-ai.shiverion.com/) · [Repo](https://github.com/Shiverion/interviewmate-ai) |
| **Financial Wellness Agent** | Multi-agent budgeting, receipt understanding, goals, market analysis, and portfolio insights. | [Case study](https://shiverion.com/projects/financial-wellness-agent) · Source private |
| **Case Vault** | Procedural noir cases with generated suspects, interrogation, evidence consistency, and episodic progression. | [Live](https://casevault.shiverion.com/) · Source private |
| **PRD Generator** | Structured product-requirements generation, Markdown editing, and professional client-side PDF export. | [Live](https://prdgenerator.shiverion.com/) · Source private |
| **Universal Commerce Protocol Agent** | Federated product discovery, inventory checks, and conversational checkout across UCP backends. | [Repo](https://github.com/Shiverion/ucp-agent) |
| **ProcureMind** | RFQ parsing, semantic search over historical products, quote comparison, and supplier-response drafting. | [Live](https://procuremind.streamlit.app/) · [Repo](https://github.com/Shiverion/ProcureMind) |
| **Meeting Summarizer** | Audio transcription, adaptive summaries, PDF output, and containerized Cloud Run delivery. | [Repo](https://github.com/Shiverion/meeting-summarizer) |
| **Cybersecurity Analyzer Agent** | Semgrep-backed Python vulnerability analysis with conversational explanations. | [Repo](https://github.com/Shiverion/cybersecurity-agent) |
| **Career Digital Twin** | Resume-grounded RAG assistant for exploring professional background and project experience. | [Live](https://huggingface.co/spaces/Shiverion/career_conversations) · [Repo](https://github.com/Shiverion/Resume-chatbot-with-RAG) |

### Human-centered products

| Project | Signal | Links |
| --- | --- | --- |
| **FocusForge** | Tauri focus environment with webcam distraction signals, Socratic review, badges, and local persistence. | [Repo](https://github.com/Shiverion/focusforge) |
| **Baseline Pro** | Mobile-first tennis coaching, booking, schedule heatmaps, vouchers, learning content, and Indonesian localization. | [Live](https://baseline-pro.vercel.app) · Source private |

### Additional private or internal work

Some production, client, company, and experimental repositories intentionally remain private. This includes the **PT Internasional Teknik Nusantara website and internal AI systems** and **ML-Enhanced Honey Powder Optimization**, alongside private-source products identified above.

</details>

## Connect

The fastest way to understand my work is to try the products, read the benchmark, or inspect the repositories:

- **Portfolio:** [shiverion.com](https://shiverion.com/)
- **GitHub:** [github.com/Shiverion](https://github.com/Shiverion)
- **LinkedIn:** [linkedin.com/in/izzulhaq-iqbal](https://www.linkedin.com/in/izzulhaq-iqbal/)
- **Writing:** [medium.com/@miqbal.izzulhaq](https://medium.com/@miqbal.izzulhaq)

This repository remains the stable, machine-readable index of my work. Private-source projects are labeled explicitly; public repositories are linked.

---

<p align="center">
  <sub>“Mystery gives life meaning. Agency gives life motion.”</sub><br>
  <samp>BUILD // MEASURE // LEARN</samp>
</p>
