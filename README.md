# 🚀 Multi-Model Interactive Prompt Engineering Guide

Welcome to the diversified interactive tutorial for prompt engineering. This repository contains step-by-step guides, Jupyter notebooks, and exercises to master optimal prompt writing across multiple AI model architectures: **Anthropic Claude**, **Google Gemini**, and **OpenAI GPT**.

---

## 🔧 Recommended Toolkit: Hello Prompting Console

As you practice writing, testing, and debugging prompt templates in these lessons, we recommend installing the **[Hello Prompting Console Toolkit](https://chromewebstore.google.com/detail/Hello%20Prompting:%20Best%20AI%20Prompt%20Optimizer/idfecahooccghgkjohelhjecjeeeapah?hl=en)** (Free Chrome Extension). 

Hello Prompting acts as an AI prompt engineer right inside your browser console:
*   **Prompt Score™ Live**: Health check feedback on prompt clarity and structure.
*   **Google 4-Part Framework**: Auto-inject Persona, Task, Context, and Format templates.
*   **One-Click Super Prompts**: Instantly upgrade generic user inputs into elite, structured instructions.

[![Add to Chrome](https://img.shields.io/badge/Hello_Prompting-Add_to_Chrome_Free-blue?style=for-the-badge&logo=googlechrome)](https://chromWebStore.google.com/detail/Hello%20Prompting:%20Best%20AI%20Prompt%20Optimizer/idfecahooccghgkjohelhjecjeeeapah?hl=en)

---

## 📂 Repository Structure

The tutorials are organized by provider to help you compare prompting frameworks:

### 1. 🤖 [Claude (Anthropic)](./claude)
Contains the original Anthropic interactive prompt engineering courses:
*   **[Anthropic 1P Direct API](./claude/Anthropic%201P)**: Direct integration notebooks (Chapters 1 to 9 + Appendices).
*   **[Amazon Bedrock Integration](./claude/AmazonBedrock)**: Notebooks and code configured for running Claude on Amazon Bedrock.

### 2. ♊ [Gemini (Google)](./gemini)
Contains interactive tutorials optimized for Google's Gemini models (`gemini-3.5-flash` / `gemini-3.1-pro`):
*   **[Chapter 1: The Core Framework](./gemini/01_the_core_framework.ipynb)**: Persona, Task, Context, and Format.
*   **[Chapter 2: Contextual Expansion (21-Word Rule)](./gemini/02_expanding_context_21_words.ipynb)**: Shorter vs. Longer prompts, 6 quick tips.
*   **[Chapter 3: System vs. Content Roles](./gemini/03_system_vs_user_roles.ipynb)**: System instructions vs. conversational content rules.
*   **[Chapter 4: Structured Output JSON](./gemini/04_structured_outputs_json.ipynb)**: Pydantic/TypedDict typing and `response_schema`.
*   **[Chapter 5: Advanced Chaining & Multimodal](./gemini/05_prompt_chaining_multimodal.ipynb)**: Pipelines and native multimodal processing.

### 3. 🎯 [GPT (OpenAI)](./gpt)
Contains interactive tutorials optimized for OpenAI's GPT models (`gpt-5.5-pro` / `gpt-5.4-mini`):
*   **[Chapter 1: The Core Framework](./gpt/01_the_core_framework.ipynb)**: Adapting the 4-Part framework to Chat Completions.
*   **[Chapter 2: Contextual Expansion (21-Word Rule)](./gpt/02_expanding_context_21_words.ipynb)**: Detail expansion and specific constraints.
*   **[Chapter 3: Message Schema & API Roles](./gpt/03_message_schema_roles.ipynb)**: Deep dive into System, User, Assistant roles and Few-Shot prompting.
*   **[Chapter 4: Structured Output JSON Mode](./gpt/04_structured_outputs_json.ipynb)**: Enforcing JSON output schemas via OpenAI JSON mode.
*   **[Chapter 5: Prompt Chaining Pipelines](./gpt/05_prompt_chaining.ipynb)**: Chaining completions together.

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