# 🤖 AI Portfolio — Experiments & Projects

A collection of hands-on AI experiments ranging from quick frontier-model prototypes to full fine-tuning pipelines for open-source LLMs.

---

## 📁 Repository Structure

```
my_ai_portfolio/
└── ai_experiments/
    ├── Frontier Model Projects (01–08)
    ├── ML Pipeline Deep-Dive (09, parts 1–8)
    ├── Ensemble & Modal Deployment (10, parts 1–2)
    ├── Dockerfile
    ├── Makefile
    └── pyproject.toml
```

---

## 🚀 Projects Overview

### Frontier Model Experiments

| # | Project | Description |
|---|---------|-------------|
| 01 | **Webpage Summarizer** | Scrapes and summarizes web pages using a frontier LLM |
| 02 | **Brochure Generator** | Generates polished marketing brochures from raw content |
| 03 | **Tech Explainer** | Explains complex technical concepts in plain language |
| 04 | **TriBot Debate** | Three-agent debate system where AI personas argue different sides of a topic |
| 05 | **WeatherMate AI Agent** | Agentic assistant that fetches and reasons over live weather data |
| 06 | **Meeting Minute Assistant** | Transcribes and structures meeting notes into actionable summaries |
| 07 | **Data Generator** | Generates synthetic datasets for downstream ML tasks |
| 08 | **RAG QA Assistant** | Retrieval-Augmented Generation pipeline for document question answering |

---

### 🔬 Project 09 — Full ML Pipeline Deep-Dive (8 Parts)

An end-to-end machine learning series covering data preparation through fine-tuned model evaluation.

| Part | Notebook | Description |
|------|----------|-------------|
| 1 | `09_part1_data_curation` | Dataset collection, cleaning, and curation |
| 2 | `09_part2_tradml_vs_frontier` | Benchmarking traditional ML vs. frontier LLMs |
| 3 | `09_part3_e5embeddings_rag` | RAG pipeline using E5 embeddings |
| 4 | `09_part4_ft_gpt4omini` | Fine-tuning GPT-4o Mini on a custom dataset |
| 5 | `09_part5_llama31_8b_quant` | Quantized inference with Llama 3.1 8B |
| 6 | `09_part6_ft_llama_qlora` | Fine-tuning Llama with QLoRA (parameter-efficient) |
| 7 | `09_part7_eval_llama_qlora` | Evaluating the QLoRA fine-tuned Llama model |
| 8 | `09_part8_summary` | Summary, results comparison, and lessons learned |

---

### ☁️ Project 10 — Ensemble Model & Cloud Deployment (2 Parts)

| Part | Notebook | Description |
|------|----------|-------------|
| 1 | `10_part1_ensemble_model` | Building an ensemble of multiple models for improved accuracy |
| 2 | `10_part2_modal` | Deploying the model to [Modal](https://modal.com) for scalable cloud inference |

---

## 🛠️ Setup & Usage

### Prerequisites

- Python 3.10+
- [uv](https://github.com/astral-sh/uv) (fast Python package manager)
- Docker (optional, for containerized runs)

### Install Dependencies

```bash
uv sync
```

Or using pip:

```bash
pip install -r requirements.txt
```

### Run with Docker

```bash
docker build -t ai-experiments .
docker run ai-experiments
```

### Using the Makefile

```bash
make help       # List available commands
make install    # Install dependencies
make run        # Run default experiment
```

---

## 🧠 Key Techniques Covered

- **Prompt Engineering** with frontier models (GPT-4o, Claude)
- **Retrieval-Augmented Generation (RAG)** with E5 embeddings
- **Fine-tuning** GPT-4.1 Nano via OpenAI API
- **QLoRA / PEFT** fine-tuning for Llama 3.1 8B
- **Quantized inference** with bitsandbytes
- **Ensemble modeling** for improved predictions
- **Cloud deployment** with Modal
- **Agentic workflows** with tool use

---

## 📊 Results Snapshot

| Approach | Notes |
|----------|-------|
| Traditional ML baseline | Starting benchmark |
| Frontier model (zero-shot) | Strong out-of-the-box performance |
| RAG pipeline | Improved factual accuracy on domain docs |
| Fine-tuned GPT-4.1 Nano | Task-specific gains with small dataset |
| QLoRA Llama 3.1 8B | Comparable quality, fully open-source & local |
| Ensemble | Best overall performance |

---

> Built as a portfolio of practical AI engineering — from quick prototypes to production-ready pipelines.