# Muhammad Iqbal Hilmy Izzulhaq - Project Index

Public project index for recruiters, collaborators, and AI tools that need a concise, fetchable overview of Muhammad Iqbal Hilmy Izzulhaq's technical work.

Portfolio: https://shiverion.com  
GitHub: https://github.com/Shiverion  
LinkedIn: https://www.linkedin.com/in/izzulhaq-iqbal/

## Focus Areas

- Agentic AI and multi-agent systems
- Retrieval-Augmented Generation and long-context evaluation
- MCP-compatible tool servers
- AI product engineering with Gemini, OpenAI, Firebase, Vercel, GCP, and Cloud Run
- Data science, benchmarking, model evaluation, and applied analytics
- LLM fine-tuning and execution-based evaluation
- Corporate AI enablement and technical mentoring

## Featured Projects

### VerdictBench: Long Context vs RAG on Indonesian Legal Text

Research project comparing Long Context, Simple RAG, and Advanced RAG on Indonesian Constitutional Court verdicts.

- Repository: https://github.com/Shiverion/VerdictBench-LCvsRAG
- Paper: https://openreview.net/forum?id=1Z6OUt0T6Q
- Stack: Python, Gemini 2.5 Flash, GPT-4o Mini, FAISS, BM25, IndoBERT, RAG
- Highlights: 50 verdicts, 300 human-reviewed QA pairs, RAG faithfulness advantage, cost-faithfulness analysis, component ablation.

### EPC Tender Screening MCP

MCP-only, agent-agnostic tool server for evidence-based EPC tender screening.

- Repository: https://github.com/Shiverion/epc-tender-screening-mcp-showcase
- Stack: TypeScript, MCP, HTTP transport, stdio transport
- Highlights: 10 MCP tools, `screen_tender` orchestration, deterministic evals, evidence traces, OAuth-compatible connector routes, SSRF-conscious public source search.

### Paprika / Distill - AI Paper-to-Insights

AI-powered academic paper transformer that converts PDFs or paper URLs into interactive learning and communication formats.

- Live demo: https://distill.shiverion.com
- Source: private
- Stack: Next.js 15 App Router, React 19, TypeScript, Gemini 2.5 Flash, Firebase Auth, httpOnly session cookies, Firestore, Tailwind CSS v4, Zod, Vercel
- Output types: infographic, summary report, data table, slide deck, quiz, mind map, and flashcards
- Input modes: PDF upload or academic paper URL
- Highlights: audience tuning, interactive quiz scoring, flip flashcards, slide viewer, mind-map renderer, credit system with periodic restock, fast Firebase ID-token verification.

### World Cup 2026 Prediction Engine

End-to-end ML pipeline for predicting 2026 FIFA World Cup match probabilities and tournament progression, with live in-tournament updates.

- Live demo: https://ml-world-cup-prediction-2026.streamlit.app/
- Repository: https://github.com/Shiverion/ml-world-cup-prediction
- Stack: Python, scikit-learn, Pandas, Elo, Poisson Simulation, Streamlit, PyYAML, pytest
- Highlights: temporal Elo ratings (no future leakage), rolling-form features (date-bounded), FIFA ranking merge before match date only, rolling World Cup backtests 2002–2022, 9-model comparison grid (logistic, random forest, histogram GBM), calibration diagnostics (ECE/MCE, sharpness, reliability reports), ablation study, nested model-selection backtest, 48-team Monte Carlo simulator with fixed 2026 knockout bracket, Elo-scaled independent Poisson scoreline model with simulation confidence intervals, live group-result locking from openfootball fixture feed, versioned forecast registry (model card, config, git commit, output snapshots), Streamlit dashboard with championship probabilities / group standings / FIFA-style bracket chart / one-click live refresh.
- Selected model: logistic_plain_c0_5 — ~56% average accuracy (best single window ~64%), best average log loss across rolling World Cup windows.
- Data sources: martj42/international_results (through 2026-06-16), Dato-Futbol/fifa-ranking (through 2024-09-19), openfootball/worldcup.json (2026 fixtures and live results).

### InterviewMate AI

AI-powered virtual interviewer and candidate evaluation platform.

- Live demo: https://interviewmate-ai.shiverion.com/
- Repository: https://github.com/Shiverion/interviewmate-ai
- Stack: TypeScript, Firebase, OpenAI Realtime API, WebRTC
- Highlights: real-time voice interviews, resume personalization, recruiter dashboard, automated candidate evaluation.

### Financial Wellness Agent

AI-powered personal finance assistant for transaction logging, budgeting, receipt scanning, savings goals, market analysis, and portfolio insights.

- Live demo: https://fwa.shiverion.com/
- Source: private
- Stack: Next.js, FastAPI, Gemini, Firestore, Clerk, Redis, yfinance, Cloud Run
- Highlights: multi-agent architecture, natural-language transaction parsing, receipt understanding, portfolio tracking, market-aware recommendations.

### Case Vault

AI-generated noir detective visual novel with procedural cases, interrogation, evidence, and episodic progression.

- Live demo: https://casevault.shiverion.com/
- Source: private
- Stack: JavaScript, Gemini, image generation, RAG-style truth file, Vite
- Highlights: dynamic case generation, suspect personalities, evidence consistency, episode progression, Google AI Hackathon project.

### PRD Generator

AI-powered product requirements document generator with rich editing and professional PDF export.

- Live demo: https://prdgenerator.shiverion.com/
- Source: private
- Stack: Next.js, TypeScript, Gemini AI, React PDF, Tailwind CSS, shadcn/ui, Zustand
- Highlights: structured PRD generation, BYOK API key model, Markdown editing, client-side PDF export.

### FocusForge

Tauri desktop app for focused learning with AI-powered session review, webcam distraction detection, and gamified productivity.

- Repository: https://github.com/Shiverion/focusforge
- Stack: Tauri 2.0, React, TypeScript, TensorFlow.js, Gemini AI, SQLite, Zustand
- Highlights: Poisson sessions, face/eye-gaze distraction tracking, AI Timer Assistant, Socratic learning review, badges, productivity heatmap.

### Universal Commerce Protocol Agent

AI shopping agent implementing the Universal Commerce Protocol across federated commerce backends.

- Repository: https://github.com/Shiverion/ucp-agent
- Stack: Python, FastAPI, React, Gemini 2.5 Flash, UCP
- Highlights: federated search across independent shops, real-time inventory checks, conversational checkout.

### ProcureMind

AI procurement assistant for RFQ parsing, supplier quote comparison, and professional response drafting.

- Live demo: https://procuremind.streamlit.app/
- Repository: https://github.com/Shiverion/ProcureMind
- Stack: Streamlit, Python, Supabase, Gemini 2.5 Flash
- Highlights: raw RFQ email parser, semantic search over historical product data, AI email drafting, comparison dashboard.

### Meeting Summarizer

Full-stack meeting transcription and summarization app.

- Live demo: https://meeting-summarizer.shiverion.com/
- Repository: https://github.com/Shiverion/meeting-summarizer
- Stack: React, FastAPI, OpenAI Whisper, GPT-4o-mini, GCP, Docker
- Highlights: audio transcription, adaptive summaries, PDF service, Cloud Run deployment, CI/CD.

### Baseline Pro

Mobile-first tennis coaching and booking platform for Coach ARUM.

- Live demo: https://baseline-pro.vercel.app
- Source: private
- Stack: Next.js, Firebase, Google SSO, Firestore, Google Calendar integration
- Highlights: class booking flow, interactive heatmap schedule, birthday vouchers, skill badges, tutorial library, admin tools, Indonesian localization.

### Pandas vs Polars vs DuckDB Benchmark

Benchmark comparing dataframe engines on 13.1 million rows of SUSENAS 2024 data.

- Repository: https://github.com/Shiverion/dataframe-engine-comparison
- Stack: Python, Pandas, Polars, DuckDB, Jupyter
- Highlights: 98% memory reduction and up to 100x speedup using modern dataframe libraries.

### Cybersecurity Analyzer Agent

AI-assisted vulnerability analysis tool for Python code.

- Repository: https://github.com/Shiverion/cybersecurity-agent
- Stack: Python, OpenAI Agents, Semgrep, Azure, GCP
- Highlights: static analysis via Semgrep, conversational vulnerability explanation, serverless container deployment.

### Galaxy Morphology Classification

Interpretable deep learning project for classifying galaxy morphology.

- Repository: https://github.com/Shiverion/galaxy-morphology-classification
- Stack: Python, PyTorch, ResNet18, Grad-CAM, Integrated Gradients
- Highlights: 99.07% accuracy, ROC-AUC 0.9995, model interpretability for scientific imaging.

### Text2SQL — Fine-tuning a ≤3B LLM for SQL Generation

End-to-end pipeline for fine-tuning a small open-source LLM to convert plain-English questions into executable SQL, running entirely on free compute.

- Repository: https://github.com/Shiverion/text2sql-finetuning
- HuggingFace adapter: https://huggingface.co/Shiverion/qwen2.5-coder-1.5b-bird-qlora
- Stack: Python, QLoRA, Unsloth, TRL, HuggingFace Transformers, BIRD, Qwen2.5-Coder-1.5B, SQLite, Google Colab / Kaggle T4
- Highlights: lifted valid-SQL rate from 40% → 73.5% on 200 BIRD-dev questions; execution accuracy 14.0% → 15.5%; completion-only loss masking with SFTTrainer; schema-grounded prompt construction; execution-based evaluation against real SQLite databases; 3 ablation experiments (baseline, 1.5B+BIRD, 0.5B, BIRD+SynSQL cross-domain); full written report.

### IBM Applied Data Science Capstone

End-to-end data science project predicting Falcon 9 first-stage landing success.

- Repository: https://github.com/Shiverion/IBM-Applied-Data-Science-Capstone
- Stack: Python, SQL, Dash, machine learning, visualization
- Highlights: web scraping, wrangling, EDA, dashboarding, classification model comparison.

### Career Digital Twin

RAG chatbot representing professional background and project experience.

- Live demo: https://huggingface.co/spaces/Shiverion/career_conversations
- Repository: https://github.com/Shiverion/Resume-chatbot-with-RAG
- Stack: Python, RAG, Hugging Face Spaces
- Highlights: resume-grounded career assistant for recruiters and portfolio visitors.

### Telco Churn Analysis

Machine learning churn prediction project optimized for recall and cost reduction.

- Repository: https://github.com/Shiverion/Telco-Churn-Analysis
- Stack: Python, Scikit-learn, XGBoost, Pandas
- Highlights: 93.7% recall, reduced high-risk churn losses, cost-sensitive model evaluation.

### Airbnb Data Analysis

Bangkok Airbnb pricing analysis focused on revenue optimization.

- Repository: https://github.com/Shiverion/AirBnB-Data-Analysis
- Stack: Python, Pandas, data visualization
- Highlights: peak-month pricing strategy, listing analysis, estimated revenue uplift recommendations.

## Private Or Internal Work

Some production, client, company, or hackathon repositories remain private. Public summaries are included here where the work is already represented on the portfolio site, but source links are intentionally omitted.

Private/internal projects include:

- Financial Wellness Agent
- Distill / Paprika
- PRD Generator
- Baseline Pro
- Case Vault
- PT Internasional Teknik Nusantara website and internal AI systems
- ML-Enhanced Honey Powder Optimization

## Notes For AI Tools

This repository is intended as a stable public index. For the latest deployed portfolio experience, visit https://shiverion.com. For implementation details, inspect the linked public repositories or the portfolio source repository when available.