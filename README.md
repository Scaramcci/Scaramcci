# Kunyuan Zhong

<!--
GitHub profile README for Scaramcci/Scaramcci.
Replace YOUR_PROFESSIONAL_EMAIL before publishing if you want contact by email.
-->

[![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)](https://www.python.org/)
[![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)](https://pytorch.org/)
[![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat&logo=huggingface&logoColor=black)](https://huggingface.co/)
[![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/)
[![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)](https://www.docker.com/)
[![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)](https://www.linux.org/)

Incoming Master's student at CUHK-Shenzhen. CS undergraduate at Nankai University. Interested in LLM systems, RAG/Agents, and AI for Software Engineering.

I enjoy building small but complete research-oriented systems: from data processing and model adaptation to evaluation, serving, and reproducible experiment workflows. I try to keep my projects inspectable, testable, and honest about their current limitations.

## Research Interests

- LLM Systems & Post-Training
- RAG and Tool-Use Agents
- AI for Software Engineering
- Evidence-Grounded LLM Reasoning
- LLM Evaluation and Reproducible Experimentation

## Selected Projects

### [Mini-LLM Post-Training Lab](https://github.com/Scaramcci/Mini-LLM-PostTraining-Lab)

A staged LLM research engineering project for studying the mechanics of small-scale LLM pretraining, post-training, serving, and tool-use evaluation.

- Covers nanoGPT-style causal LM pretraining, tokenizer/data inspection, toy SFT data validation, Qwen LoRA SFT, DPO experiments, and a minimal tool-use agent.
- Maintains scripts, configs, experiment logs, and result summaries so each stage can be inspected and rerun.
- Currently extends toward GRPO-style reward experiments and vLLM-based serving evaluation; it is not intended to be a production-grade LLM platform.

### [Metaware Counseling Agent](https://github.com/Scaramcci/Metaware-counseling-Agent)

A backend-only, Chinese-first deterministic RAG/Agent MVP for parent-child psychological support and family education scenarios.

- Built with FastAPI APIs, Pydantic schemas, local Markdown knowledge loading, deterministic risk classification, and safety-first routing.
- Handles high-risk inputs through a crisis-safe route instead of ordinary retrieval, and includes privacy-aware AgentTrace summaries.
- Includes deterministic offline evaluation and security regression tests for trace safety, path filtering, high-risk retrieval bypass, and secret/config exposure.
- Related competition project won the Gold Award in the Tianjin Regional Competition of the China International College Students' Innovation Competition.

### Evidence-Grounded Fact-Checking System Based on LLMs

Undergraduate graduation project; repository not public yet.

- Designs an open-domain fact-checking framework with multi-perspective query generation, evidence retrieval, deduplication, and credibility-based reranking.
- Builds an atomic-fact verification pipeline for decomposing complex claims and producing traceable verdicts with explicit evidence attribution.
- Uses case-driven evaluation to study retrieval quality, reasoning transparency, and failure modes.

## Technical Stack

- **Programming:** Python, C++, Java, Bash
- **LLM / ML:** PyTorch, HuggingFace Transformers, TRL, LangChain, RAG, Agent tool use, LoRA/SFT, DPO basics, prompt engineering
- **Systems:** Linux, Docker, Git, FastAPI, RESTful APIs, GPU server environment setup, reproducible experiments
- **AI-Assisted Development:** Claude Code, Codex, GitHub Copilot for codebase exploration, rapid prototyping, refactoring, testing, and documentation

## Contact

- GitHub: [Scaramcci](https://github.com/Scaramcci)
- Email: YOUR_PROFESSIONAL_EMAIL
