# 🐍🤖 Apoco AI Code Challenge

Your mission is to build and evaluate a smart, LLM-powered Q&A Agent with inline citations.
Show us your practical skills, theoretical understanding, and communication style!


## 🛠️ Tech Stack

- **Python 3.x**
- **Lightweight Open-source LLM** (e.g., [Llama 3.1:8B](https://huggingface.co/meta-llama/Llama-3.1-8B-Instruct), [Granite 3.3:8B](https://huggingface.co/ibm-granite/granite-3.3-8b-instruct), or similar)
- **Any open-source libraries** (HuggingFace, PyTorch, inference provider SDKs, etc.)

---

## 🎯 Objectives

> !IMPORTANT
> You must do the agent implementation by yourself; using existing solutions from frameworks is not allowed.

### 1. Build a RAG-based Q&A Agent
- Retrieve relevant context for each user question from an external source (e.g., Wikipedia).
- Generate answers **with inline citations** referencing the retrieved sources.
- Minimize hallucinations and handle irrelevant or malicious inputs robustly.
- Clearly indicate when an answer cannot be provided based on available sources.

### 2. Evaluation & Analysis
- Design and implement an evaluation pipeline (automated or manual) to assess your agent’s performance.
  - Use relevant metrics (e.g., factual accuracy, citation correctness, robustness to adversarial input).
  - Include a small set of test questions and report the results.
- Error analysis: Why the agent can fail in some cases and why is it happening?

### 3. Documentation & Reflection

- **Code documentation:** Comment your project and document the complex parts.
- **Design decisions:** Briefly explain your choices (model, retrieval method, prompt design, etc.).
- **Ethical & safety considerations:** Discuss how you addressed hallucination, bias, and user safety.
- **Improvement ideas:** Suggest concrete ways to further improve your agent.

---

## 🌟 Bonus Tasks (Optional)

- **Dockerize** your application.
- **BeeAI Integration:** Wrap your agent in a BeeAI Platform-compatible server so it can be registered and used locally (UI/CLI).
- **Configurability:** Allow switching between models, data sources, etc.
- **Experiment with fine-tuning.**
- **Your creative idea! 💡**

---

## 🧑‍⚖️ Assessment Criteria

- **Technical correctness:** Does the agent work as specified? Are citations accurate?
- **Code quality:** Is the code clean, modular, and well-documented?
- **Evaluation rigor:** Are the evaluation and error analysis meaningful?
- **Communication:** Are design decisions and ethical considerations clearly explained?
- **Creativity & initiative:** Are there thoughtful improvements or extra features?

---

## 📝 Submission Guidelines

- Create a private GitHub repository and invite **@Tomas2D**.

---

## ❓ Need Clarification?

Feel free to ask questions (tomas.dvorak@apoco.com).
We value both technical skill and critical thinking.
