# 🚀 Multi-Model Interactive Prompt Engineering Guide

Welcome to the diversified interactive tutorial for prompt engineering. This repository contains step-by-step guides, Jupyter notebooks, and exercises to master optimal prompt writing across multiple AI model architectures: **Anthropic Claude**, **Google Gemini**, and **OpenAI GPT**.

---

## 📂 Repository Structure

The tutorials are organized by provider to help you compare prompting frameworks:

### 1. 🤖 [Claude (Anthropic)](./claude)
Contains the original Anthropic interactive prompt engineering courses:
*   **[Anthropic 1P Direct API](./claude/Anthropic%201P)**: Direct integration notebooks (Chapters 1 to 9 + Appendices).
*   **[Amazon Bedrock Integration](./claude/AmazonBedrock)**: Notebooks and code configured for running Claude on Amazon Bedrock.

### 2. ♊ [Gemini (Google)](./gemini)
Contains interactive tutorials optimized for Google's Gemini models (Gemini 1.5 Pro/Flash):
*   **[Gemini Prompt Anatomy & Schemas](./gemini/01_Gemini_Prompt_Structure.ipynb)**: Mastering system instructions, Generation Configs, multi-modal files, and strict JSON schemas.

### 3. 🎯 [GPT-4o (OpenAI)](./gpt)
Contains interactive tutorials optimized for OpenAI's GPT models (GPT-4o/GPT-4o-mini):
*   **[GPT-4o Message Schema & Parameters](./gpt/01_GPT_Prompt_Structure.ipynb)**: Organizing System, User, and Assistant message structures, configuring temperatures, and returning valid JSON formats.

---

## 📈 Learning Goals
After working through these guides, you will be able to:
1.  **Understand Model Nuances**: Discern why Claude loves XML tags, how Gemini handles typed JSON schemas, and how GPT processes system instruction blocks.
2.  **Avoid Hallucinations**: Write defensive prompts that prevent models from inventing false facts.
3.  **Format Outputs**: Request and receive structured data outputs (Markdown, JSON, XML) reliably.
4.  **Chaining & Tools**: Learn advanced methods like prompt chaining, few-shot prompting, and tool use parameter designs.

---

## 📄 License
This project is licensed under the Apache License 2.0 or MIT License (inherited from the original Anthropic upstream).