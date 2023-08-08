# 🐍 🤖 Python AI Code Challenge

This repository contains a coding exercise for new developers joining us. 

## 📜 What we want you to build

You will be building an autonomous AI Agent which is able to reason over Generative AI Python SDK (IBM) documentation.
We can ask your application (chatbot) on documentation topics; as a bonus, your application can even code and browse the web!

**Technology Stack**: Python, LLM, [LangChain](https://python.langchain.com/), [Pinecone](https://www.pinecone.io/) or any other Vector Store.   

### 🎯 Objectives

- Create an application which allows the user to query our SDK documentation.
  - Agent remembers conversation context.
  - Agent handles large conversations.
  - Every response related to the SDK documentation must contain sources (relevant links to the documentation page).
- Introduce UI for communication with the agent ([Streamlit](https://streamlit.io/) / [React](https://react.dev/) whatever you want!)
  - Handle edge cases, crashes.
  - (optional) Use streaming for responses.
  - (optional) Allow the user to upload file(s). 
- (optional) Agent can lookup for specific facts on the web (Google / DuckDuckGo).
- (optional) Agent can execute Python code.
- (optional) Agent can work with files (CSV / PDF).
- (optional) One can interact with the Agent via CLI.
- (optional) One can interact with the Agent via API (Rest/gRPC).

### 🔗 Links

- GenAI Python SDK (https://github.com/IBM/ibm-generative-ai) with HTML documentation (https://ibm.github.io/ibm-generative-ai/).
- (optional) GenAI Node.js SDK (https://github.com/IBM/ibm-generative-ai-node-sdk).

### 📝 Notes
- Be creative. Everything extra/custom is appreciated 🦄
- You can use more technologies, but those mentioned are required.
- Explain your decisions and choices. We want to see you know what you are doing.
- Document your code, mainly the parts related to LLM (parameters, sizes, etc.).
- Describe how the final application works in general.
