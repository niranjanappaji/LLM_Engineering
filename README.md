# LLM_Engineering

A hands-on journey into **Large Language Models and Generative AI**, where I learn by building, experimenting, and understanding what happens behind the APIs.

I created this repository to move beyond the theoretical understanding of LLMs and explore how they work in real-world applications through a series of practical projects.

## What I'm Exploring

Through these projects, I aim to build a practical understanding of:

* Large Language Models (LLMs)
* Transformers and attention
* Tokenization and embeddings
* Context windows
* Prompt engineering
* Model parameters and inference
* Cloud vs. local LLMs
* Open-source and smaller language models
* RAG and vector databases
* Fine-tuning and model adaptation
* LLM evaluation
* AI agents and tool calling
* Building production-oriented LLM applications

The goal is not just to **use LLMs**, but to understand the concepts behind them and the engineering decisions involved in building applications with them.

---

## Projects

### 1. Web Summarizer

My first hands-on LLM project — a web-page summarization pipeline that takes a URL, extracts and cleans the webpage content, and generates a summary using different language models.

**Pipeline:**

```text
URL
 ↓
Web Scraping
 ↓
Content Extraction & Cleaning
 ↓
Tokenization
 ↓
LLM
 ↓
Summary
```

For this project, I experimented with different approaches:

* **OpenAI** — cloud-based frontier LLM
* **BART-large-CNN** — local, task-specific summarization model
* **TinyLlama** — small, local generative LLM

The project helped me understand concepts such as **tokenization, context windows, prompting, inference, model limitations, and the trade-offs between cloud and local models**.

[`2_LLM_Web_Summarizer.ipynb`](./2_LLM_Web_Summarizer.ipynb)

---

### 2. Company Brochure Generator

An LLM-powered application that automatically researches a company's website and generates a concise company brochure.

The application combines web scraping, HTML parsing, LLM-based link selection, prompt engineering, and streamed LLM generation.

**Pipeline:**

Company Website
       ↓
Fetch Landing Page
       ↓
Extract Text + Links
       ↓
LLM Selects Relevant Pages
       ↓
Fetch Relevant Pages
       ↓
Combine Website Content
       ↓
LLM Generates Brochure
       ↓
Markdown Output

**Key concepts explored**

Web scraping with Requests
HTML parsing with BeautifulSoup
Content extraction and cleaning
LLM-based information selection
Structured JSON output from LLMs
Prompt engineering
Context management
API-based LLM applications
Streaming LLM responses
Production-oriented code documentation
Error handling and resilient processing
Technology Stack
Python
OpenAI API
Requests
BeautifulSoup
Google Colab
Markdown

**Project: Company Brochure Generator**

More projects will be added as I continue exploring different areas of LLM engineering.

---

## Learning Approach

For each project, I try to follow a simple approach:

**Learn → Build → Experiment → Compare → Understand → Document**

Rather than only following tutorials, I want to experiment with different models and approaches, understand their limitations, and document what I learn along the way.

---

## Technologies

The technologies will evolve as the projects grow, but some of the tools I am currently exploring include:

* Python
* PyTorch
* Hugging Face Transformers
* OpenAI API
* LangChain / LlamaIndex
* Vector Databases
* RAG
* Local LLMs
* Google Colab

---

## Why This Repository?

LLMs are evolving rapidly, and there is a lot to learn.

This repository is my attempt to build that knowledge **hands-on, one project at a time**.

I am using these projects to bridge the gap between:

> **"I understand how LLMs work"**

and

> **"I can actually build applications using LLMs and understand the engineering decisions behind them."**

This repository will continue to evolve as I learn, experiment, and build more.
