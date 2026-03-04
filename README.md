# 🧠 AI Experiments Repository

This repository contains multiple AI experiments exploring Large Language Models (LLMs), frontier models, and open-source models across different real-world use cases.

The goal of this repository is to experiment, build, and deploy practical AI systems using modern LLM architectures.

---

## 🚀 Scope of Experiments

This repo includes projects built using:

- Frontier LLM APIs
- Open-source LLMs (LLaMA, Mistral, etc.)
- Transformer-based models
- Retrieval-Augmented Generation (RAG)
- Speech-to-Text systems
- Gradio-based AI applications
- Quantized and optimized local models

Each project inside `my_ai_portfolio/` focuses on a specific AI workflow or application.

---

# 📁 Project Structure
my_ai_portfolio/
├── meeting_minutes.py
├── (future AI projects...)
└── ...

More projects will be added over time.

---

# 🎙️ Meeting Minutes Assistant

## Overview

An end-to-end AI system that converts meeting audio into structured meeting minutes.

### 🔧 Tech Stack

- Whisper (Speech-to-Text)
- LLaMA (LLM for summarization)
- OpenAI Whisper model
- Hugging Face Transformers
- PyTorch
- Gradio (UI)

### 🏗️ Architecture

Audio Input  
↓  
Whisper (Transcription)  
↓  
Raw Transcript  
↓  
LLaMA (Structured Summarization Prompt)  
↓  
Formatted Meeting Minutes  

### ✨ Features

- Upload meeting audio
- Automatic transcription
- Structured summary generation
- Extracted key points
- Action items generation

---

# 🧪 Future Experiments

This repository will expand with:

- RAG systems
- Agent-based workflows
- Tool-calling LLM systems
- Quantized local LLM deployments
- Multi-modal experiments (audio + text + vision)

---

# 🛠️ Installation

```bash
pip install -r requirements.txt
