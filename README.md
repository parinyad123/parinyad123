# Hi, I'm Parinya (Aof) 👋

**AI/ML Engineer** building **multi-agent LLM systems** — with a physics background to keep the math underneath them *deterministic and explainable*.

🧮 M.S. Physics (Chulalongkorn) · 5+ years in space technology and astronomical research
💬 Ask my portfolio chatbot about my work: **[parinya-chatbot.vercel.app](https://parinya-chatbot.vercel.app)**
📍 Bangkok, Thailand · Open to AI/ML engineering roles

---

### 🚀 Featured Projects

**X-ray Timing Agent** — Multi-agent system for X-ray astronomy timing analysis · *SUT × NARIT* · private repository
> Researchers upload an XMM-Newton light curve (FITS) and ask in chat or pick analyses in a form; specialized agents classify the request, run deterministic statistics, PSD and power-law / bending-power-law fits (SciPy/Astropy), and explain the results.
> - First version, built during the contract: locally-hosted **AstroSage-Llama-3.1-8B** + **OpenAI GPT**.
> - Continued after the contract on **Groq-hosted gpt-oss**, with a parameter form prefilled for each file and code checks that verify every number in the LLM's answers; now in trial use by the supervising professor.
>
> `LangChain` · `FastAPI` · `PostgreSQL` · `SciPy` · `Astropy` · `Groq` · `Next.js` · `SSE`

**[Financial Analyst Agent](https://github.com/parinyad123/financial-analyst-agent)** — Explainable Quant Analytics & LLM Agent Orchestration
> End-to-end explainable quant agent: single-stock analysis, what-if portfolio risk, and live holdings tracking through **one LLM router**.
> - **Deterministic quant core** — every metric (Hurst regime, IC/IR, VaR, Risk Contribution) is computed in code, *not* LLM-generated.
> - **LangGraph StateGraph router** (`planner → agent → tools`) with deterministic pre-routing, verified by a 13/13 routing-regression suite + adversarial guardrails against LLM misrepresentation.
> - **FastAPI**, async SQLAlchemy persistence, per-request **LangSmith** tracing, Streamlit UI, multi-stage **Docker** build.
>
> `LangGraph` · `LangChain` · `Groq` · `FastAPI` · `SQLAlchemy` · `Docker` · `pandas` · `NumPy` · `SciPy`

**[Parinya Chatbot](https://parinya-chatbot.vercel.app)** — Hybrid RAG assistant with layered guardrails
> Public Thai/English chatbot that answers recruiter questions about my work, cites its sources, and declines when it has no evidence.
> - Hybrid retrieval (BM25 + vector, RRF) — MRR 1.000 on a 32-query eval.
> - Four safety layers against leaking confidential or overclaimed content: ingest deny list, retrieval filter, prompt guardrails, and a code post-check — covered by 220 automated tests.
>
> `FastAPI` · `Gemini` · `Chroma` · `Cloud Run` · `Next.js` · `Vercel`

**[LLM & RAG Workshop — SUT](https://github.com/parinyad123/LLM-and-RAG-Workshop-SUT)** — Open-source teaching material
> Hands-on workshop for astronomy researchers and graduate students: transformer internals → full RAG pipelines (FAISS, Top-K vs. MMR retrieval, prompt engineering, Gradio deployment).

**[GHG Emissions Analysis](https://github.com/parinyad123/ghg-emissions-analysis)** — Data Analysis & BI Dashboard
> CO₂ emissions vs GDP for the world's largest emitters on the Our World in Data dataset (48,058 rows): PostgreSQL star schema, pandas cleaning, Looker Studio dashboard (189 countries, 1981–2022).
> Finding: **US emissions decoupled from GDP after 2008**; China's did not, at one-fifth the GDP per capita.

<details>
<summary><b>More projects</b></summary>

- **[Satellite Telemetry Anomaly Detection](https://github.com/parinyad123/vermouth-desktop-application)** (GISTDA) — PyTorch autoencoders per telemetry parameter, trained from a PySide6 desktop tool; daily inference into PostgreSQL; Go (Gin) API ([backend](https://github.com/parinyad123/vermouth-backend)) and Vue 2 dashboard ([frontend](https://github.com/parinyad123/vermouth-frontend)).
- **[Satellite Imagery QC Automation](https://github.com/parinyad123/mmgs-igstool)** (GISTDA) — 285 products checked against 8 criteria at ~4.9 s each, replacing a manual checklist.
- **[Brain Tumor Classification](https://github.com/parinyad123/brain-tumor-classification)** — VGG-19 on MRI, 91% test accuracy.
- **[Movie Recommender API](https://github.com/parinyad123/ml-recommender-system-fastapi)** — Keras collaborative filtering served by FastAPI on AWS EC2 behind Nginx.
- **Satellite ground station proofs of concept** (TRUS) — CSP over CAN bus, an Angular (NgRx) + FastAPI configuration platform, a RabbitMQ broker with mutual TLS, and a GeoServer publishing pipeline.
- **[Flutter Counter with BLoC](https://github.com/parinyad123/flutter_counter_bloc)** — learning project for the BLoC pattern, with `bloc_test` unit tests.

</details>

---

### 🛠️ Tech Stack

**LLM / Agents** &nbsp; LangChain · LangGraph · LangSmith · RAG · Groq · Gemini · OpenAI
**Backend** &nbsp; Python · FastAPI · Go (Gin) · PostgreSQL · SQLAlchemy
**Frontend** &nbsp; TypeScript · Next.js · React · Angular (NgRx) · Vue 2
**Mobile** &nbsp; Flutter (Dart, BLoC)
**ML / Data** &nbsp; PyTorch · TensorFlow/Keras · scikit-learn · XGBoost · pandas · NumPy · SciPy · OpenCV
**Infra** &nbsp; Docker · Nginx · AWS (EC2) · Google Cloud Run · Vercel

---

### 📫 Connect
[LinkedIn](https://www.linkedin.com/in/parinya-duangklang/) · [Portfolio chatbot](https://parinya-chatbot.vercel.app) · Bangkok, TH
