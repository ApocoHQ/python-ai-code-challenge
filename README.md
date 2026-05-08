# 🤖 Apoco AI Code Challenge

Your mission is to build and evaluate a smart, LLM-powered Q&A Agent with inline citations.
This challenge is aimed at **AI Research and AI Engineers** — we care as much about your understanding of *why* things work as about the working implementation itself. Show us your depth of thinking, your evaluation methodology, and how you reason about the limits of your system.


## 🛠️ Tech Stack

Choose your language — both are fully supported:

- **Python 3.x** — with open-source libraries (HuggingFace `transformers`, `torch`, etc.)
- **TypeScript / Node.js** — with open-source libraries (`ollama`, `@huggingface/inference`, `transformers.js`, etc.)

- **Lightweight Open-source LLM running locally** (e.g., [Llama 3.1:8B](https://huggingface.co/meta-llama/Llama-3.1-8B-Instruct), [Granite 3.3:8B](https://huggingface.co/ibm-granite/granite-3.3-8b-instruct), or similar) — we recommend serving it via [Ollama](https://ollama.com)

---

## 🎯 Objectives

> [!IMPORTANT]
> You must implement the agent yourself. Utility libraries are fine (e.g., HTTP clients, embedding models, API wrappers, tokenizers). What is **not** allowed is using pre-built pipelines that handle retrieval, search, or orchestration for you — e.g., LangChain agents, LlamaIndex query engines, or similar tools that do the core work on your behalf.

### 1. Build a RAG-based Q&A Agent
- Retrieve relevant context for each user question from an external source (e.g., Wikipedia).
- Generate answers **with inline citations** referencing the retrieved sources.
- Minimize hallucinations and handle irrelevant or malicious inputs robustly.
- Clearly indicate when an answer cannot be provided based on available sources.
- The agent must be accessible via a **chat interface** — a terminal UI or a simple web UI are both acceptable.

### 2. Evaluation & Analysis

This section is a core part of the challenge — not an afterthought.

- Design and implement an evaluation pipeline (automated or manual) to assess your agent’s performance.
  - Define and justify the metrics you chose (e.g., factual accuracy, citation correctness, answer relevance, robustness to adversarial input). Explain *why* each metric matters for this use case.
  - Include a curated set of test questions that cover different difficulty levels and edge cases. Report results and discuss what they reveal.
- **Error analysis:** Identify specific failure modes. What types of questions does the agent struggle with and why? Is it a retrieval problem, a generation problem, or a prompt design problem?
- **Retrieval analysis:** How does the quality of retrieved context affect answer quality? What happens when retrieval returns irrelevant or partially relevant content?

### 3. Documentation & Reflection

- **Design decisions:** Go beyond *what* you built — explain *why*. Why this chunking strategy? Why this retrieval approach over alternatives? What trade-offs did you make and what would you do differently with more time?
- **Prompt design:** Share and discuss your prompt(s). How did you arrive at them? What did you try that didn’t work?
- **Ethical & safety considerations:** Discuss how you addressed hallucination, bias, prompt injection, and user safety.
- **Improvement ideas:** Suggest concrete, technically grounded ways to improve the system — not just "use a bigger model".

---

## 🌟 Bonus Tasks (Optional)

- **Dockerize** your application.
- **Configurability:** Allow switching between models, data sources, etc.
- **Experiment with fine-tuning.**
- **Your creative idea! 💡**

---

## 🧑‍⚖️ Assessment Criteria

- **Depth of understanding:** Do the design decisions, evaluation methodology, and error analysis show genuine understanding of RAG systems and their failure modes?
- **Evaluation rigor:** Are metrics well-chosen and justified? Is the error analysis specific and insightful rather than generic?
- **Technical correctness:** Does the agent work as specified? Are citations grounded in the retrieved sources?
- **Code quality:** Is the code clean, modular, and well-documented?
- **Communication:** Are reasoning and trade-offs explained clearly? Would another engineer understand your choices?
- **Creativity & initiative:** Are there thoughtful improvements, novel approaches, or extra features?

---

## 📝 Submission Guidelines

- Create a private GitHub repository and invite **@Tomas2D**.
- Let us know when the project is ready by sending an email to **tomas.dvorak@apoco.com**.

---

## ❓ Need Clarification?

Feel free to ask questions.
We value both technical skill and critical thinking.
