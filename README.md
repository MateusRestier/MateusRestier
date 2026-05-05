<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&amp;color=gradient&amp;customColorList=24&amp;height=180&amp;section=header&amp;text=Mateus%20Restier&amp;fontSize=52&amp;fontColor=ffffff&amp;fontAlign=50&amp;fontAlignY=38&amp;desc=Data%20Scientist%20%7C%20AI%20and%20Cloud%20Data%20Engineering&amp;descAlign=50&amp;descAlignY=58&amp;descSize=18" />
<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&amp;size=16&amp;pause=1200&amp;color=58A6FF&amp;center=true&amp;vCenter=true&amp;width=480&amp;lines=RAG+%26+LLM+Orchestration;Vector+Search+%26+Embeddings;Machine+Learning+%26+Forecasting;Cloud+Data+Engineering+(AWS+%2F+Snowflake);Turning+complex+data+into+strategic+insights" alt="Typing SVG" />
  <br/>
  <a href="https://www.linkedin.com/in/mateus-restier">
    <img src="https://img.shields.io/badge/LinkedIn-Mateus%20Restier-blue?style=for-the-badge&amp;logo=linkedin" />
  </a>
  <a href="mailto:restier2001@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-restier2001@gmail.com-red?style=for-the-badge&amp;logo=gmail&amp;logoColor=white" />
  </a>
</p>

---

### 🧠 About Me

I'm a **Data Scientist** based in Rio de Janeiro, Brazil 🇧🇷.
Currently, I work at **FGV IBRE**, focusing on **Generative AI**, **Machine Learning**, and **Data Engineering** within the **AWS** ecosystem. My work involves building advanced NLP pipelines, developing classification models, and optimizing cloud data processes using **Snowflake** and **Streamlit**.

I hold a **B.Sc. in Computer Science** and have a strong background in automating business processes and BI from my previous experiences at **Bagaggio** and **Enel**.

**Fun fact:** Before diving into data, I was a **professional e-sports player**, a journey that sharpened my resilience, strategic thinking, and ability to perform under high pressure 🎮.

---

### 🛠️ Tech Stack

**Languages & Frameworks**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit_Learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=for-the-badge&logo=selenium&logoColor=white)

**Cloud & Data Engineering**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=for-the-badge&logo=duckdb&logoColor=black)
![Dagster](https://img.shields.io/badge/Dagster-4F43DD?style=for-the-badge&logo=dagster&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

**Vector Stores & AI Infra**

![pgvector](https://img.shields.io/badge/pgvector-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-FF3E00?style=for-the-badge&logoColor=white)
![Google Gemini](https://img.shields.io/badge/Google_Gemini-4285F4?style=for-the-badge&logo=google&logoColor=white)
![Azure OpenAI](https://img.shields.io/badge/Azure_OpenAI-0089D6?style=for-the-badge&logo=microsoft-azure&logoColor=white)
![Google Earth Engine](https://img.shields.io/badge/Google_Earth_Engine-4285F4?style=for-the-badge&logo=google&logoColor=white)

---

### 🚀 Featured Projects

#### 🔹 Insight Invest — [insight-invest](https://github.com/MateusRestier/insight-invest) 🔓
> 🌐 [Live app](https://insight-invest.up.railway.app/) — Automated stock analysis system that scrapes fundamental indicators from Investidor10 via **BeautifulSoup4**, stores them in **PostgreSQL**, and trains **scikit-learn Random Forest** models for both price forecasting (regressor) and performance classification. A daily **schedule**-based orchestrator runs scraping, multi-day predictions, and recommendations automatically. Results are explored through a **Dash/Plotly** dashboard with Bootstrap theming, backed by Docker Compose.

#### 🔹 COPOM RAG System — [copom-vector-pipeline](https://github.com/MateusRestier/copom-vector-pipeline) · [copom-rag-api](https://github.com/MateusRestier/copom-rag-api) · [copom-streamlit](https://github.com/MateusRestier/copom-streamlit) 🔓
> 🌐 [Live app](https://copom-rag.streamlit.app/) — End-to-end RAG system for Q&A over COPOM (Brazilian Monetary Policy Committee) documents. The pipeline downloads meeting minutes and communications from the BCB Open Data API, parses PDFs with **pdfplumber**, chunks with **LangChain** + tiktoken, embeds with **Google Gemini**, and stores 1536-dim vectors in **PostgreSQL + pgvector** (HNSW index). A **FastAPI** service retrieves chunks via cosine search, optionally reranks with LLM, and generates cited answers with Gemini. A **Streamlit** app delivers the Q&A interface, document filters, and an admin panel with live ingestion logs.

#### 🔹 Automated Economic Releases — [automated-economic-releases](https://www.linkedin.com/in/mateus-restier/details/projects/) 🔒
> Streamlit platform that automates press release generation for 15+ FGV IBRE economic indicators. Ingests Excel data via pandas/openpyxl, assembles few-shot prompts from historical bulletins, and calls **Azure OpenAI (GPT-4o)** to generate narratives. Final output is rendered as a formatted Word (.docx) via **docxtpl** (Jinja2) and logs downloads to **Snowflake**. Optionally enriches context via a RAG API before generation.

#### 🔹 Document RAG System — [document-vector-pipeline](https://www.linkedin.com/in/mateus-restier/details/projects/) · [document-rag-framework](https://www.linkedin.com/in/mateus-restier/details/projects/) 🔒
> End-to-end semantic search and RAG system for Portuguese-language journalism and economic articles. The pipeline fetches from **MongoDB/AWS DocumentDB**, cleans noisy text with **spaCy** (pt_core_news_sm) + NLTK, generates dense embeddings via **sentence-transformers**, and stores them in **Qdrant** with SHA-256 deduplication and checkpoint/resume support. A **LangGraph**-orchestrated framework then enriches economic analysis text by querying Qdrant across multiple collections, scoring chunk relevance with an LLM, and integrating context via **Azure OpenAI (GPT-4o)** — with configurable quality thresholds and YAML prompt overrides. Built for **AWS SageMaker** deployment.

#### 🔹 Nightsight Analytics — [nightsight-analytics](https://www.linkedin.com/in/mateus-restier/details/projects/) 🔒
> Monthly economic activity monitor for all 5,570 Brazilian municipalities derived from **VIIRS/DNB** nighttime satellite imagery (NASA/NOAA). Batch-extracts radiance data via **Google Earth Engine**, applies Winsorization (p99), IHS transform, and temporal Z-score normalization per municipality, then loads into **Snowflake**. An interactive **Streamlit + PyDeck** WebGL dashboard renders choropleth maps, municipal time series, and regional rankings.

#### 🔹 Sound DNA — [sound-dna](https://github.com/MateusRestier/sound-dna) 🔓
> End-to-end music genre classification pipeline: ingests tracks from YouTube via **yt-dlp**, stores metadata in **MongoDB**, and extracts 369 audio features per track using **librosa** (MFCCs, Chroma, Spectral Contrast, ZCR, RMS, Tempogram). Trains **XGBoost** and **Random Forest** classifiers, and explores clusters via PCA → K-Means → t-SNE. A **Streamlit** app accepts YouTube links or file uploads and returns real-time genre predictions with waveform, mel-spectrogram, and MFCC visualizations.

#### 🔹 Scheduled Action Bot — [scheduled-action-bot](https://www.linkedin.com/in/mateus-restier/details/projects/) 🔒
> Human-in-the-loop browser automation system with a multi-layer scheduling architecture. A **FastAPI** app deployed on **Render** (Docker) stays alive via UptimeRobot + **GitHub Actions** keepalive. At scheduled times, **cron-job.org** triggers the API, which reads email confirmations via **IMAP** and — upon approval — dispatches a **Selenium** (Chrome headless) agent to execute the browser workflow with randomized timing delays. Action results are reported back via **Resend API**.

#### 🔹 Competitor Analysis — [competitor-analysis](https://www.linkedin.com/in/mateus-restier/details/projects/) 🔒
> Parallel web scraping and data intelligence system that monitors 6 Brazilian e-commerce competitors across 12 product categories, extracting 20+ attributes per product. Each retailer has a dedicated **Selenium + BeautifulSoup4** scraper tailored to its DOM structure, with hybrid extraction (JSON-LD structured data + CSS selectors), dynamic scroll/pagination, and user-agent spoofing. A **ThreadPoolExecutor** runs all 6 scrapers concurrently, bulk-inserts results into **SQL Server** via **SQLAlchemy + pyodbc** (parameter-limit-aware batching), and passes the data through a 50+ rule normalization engine (colors, sizes, materials, attribute inference). Final output feeds a **Power BI** dashboard for pricing and product mix analysis.

#### 🔹 Football DataOps Lakehouse — [football-dataops-lakehouse](https://github.com/MateusRestier/football-dataops-lakehouse) 🔓
> Local data lakehouse replicating AWS architecture (S3 → Athena → MWAA) entirely on open-source tooling. Uses **Terraform** to provision **MinIO** buckets, **Dagster** to orchestrate a medallion pipeline (raw → validated → trusted) over StatsBomb open data, **Great Expectations** for data quality gates (coordinates, IDs), and **DuckDB** for stateless Parquet queries. Full **Docker Compose** setup with **GitHub Actions** CI/CD.

#### 🔹 JoyBind — [joybind](https://github.com/MateusRestier/joybind) 🔓
> 🌐 [Download Now](https://github.com/MateusRestier/joybind/releases) — Windows desktop app that maps any USB/Bluetooth gamepad to keyboard, mouse, and macro sequences — no drivers required. Built with **customtkinter** (GUI), **pygame** (60 Hz joystick polling), and **pyautogui/pynput** (OS-level input simulation via Windows SendInput for Raw Input compatibility). Supports key combos, hold-while-pressed, timed macros, multi-step action sequences, analog stick → mouse, and JSON-based preset system. Distributed as a standalone **.exe** via PyInstaller.

---

### 🎯 Currently Focused On

- 🤖 **RAG & LLM Orchestration:** Building LangGraph-based pipelines with multi-query generation, LLM relevance validation, and vector stores (pgvector, Qdrant) for production economic analysis systems.
- 🧮 **Vector Search & Embeddings:** Designing production ETL pipelines for large text corpora — from noisy ingestion and NLP preprocessing to dense embedding storage and semantic retrieval.
- 🧠 **Machine Learning:** Applying classification, forecasting, and pattern recognition models across domains — from financial time series to audio feature engineering.
- ☁️ **Cloud Architecture:** Optimizing data pipelines and efficiency on **AWS** and **Snowflake**.

---

### 🤝 Let's Connect!

Whether it's about **AI, Cloud Engineering, Automation, or Retro Gaming**, I'm always happy to chat!
📬 [LinkedIn](https://www.linkedin.com/in/mateus-restier) | ✉️ restier2001@gmail.com

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&amp;color=gradient&amp;customColorList=24&amp;height=100&amp;section=footer" />
