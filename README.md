# Mem0 + Agno Interactive Agent Demo

## Overview

This project showcases a minimal but powerful example of building AI agents that can **store**, **recall**, and **reason** using long-term memory and language models.

It combines three major components:
- **Agno Agent Framework** – to define agent behaviors like storing or retrieving.
- **Mem0 Memory Client** – to persist and search user memory.
- **Hugging Face LLM** – to enable intelligent, context-aware responses.

The entire system runs as a **simple command-line interface**, and demonstrates core ideas in AI agent workflows:
- **Agent chaining** (one agent calling another),
- **Persistent memory** integration,
- **LLM-enhanced reasoning**.

It is suitable for beginners learning agent development, as well as researchers prototyping memory-augmented agents.

---

## Objectives

- Understand how to use `Mem0` to store and retrieve context.
- Build modular agents using `Agno`.
- Create smart reasoning agents with LLM + memory integration.
- Demonstrate how agents can be composed into chains for more complex logic.

---

## Installation

Use these commands in Google Colab or a Python 3.8+ environment:

```bash
!pip install agno
!pip install mem0ai
!pip install transformers
