# agenticai-fundamentals
# 🧠 **DMSx Agentic AI Prep Program**
Pre-Requisites + Day 1 Hands-On Learning Guide*
**By D. Meenakshi Sundaram — Founder, DMS Academy | AI Educator**
## 🌟 Overview
Welcome to the official **Pre-Learning Guide** for the
**DMSx Agentic AI Hands-On Certification Program**.
This page gives you EVERYTHING you need **before Day 1**, including:
* Pre-requisites
* Tools installation
* Day 1 lesson plan
* Hands-on code
* Video references
* Downloads
## 🔥 Who Is This Guide For?
* Working professionals (Tech + Non-tech)
* Faculty Members
* AI beginners
* Students
* Developers transitioning to **Agentic AI**

# 🧩 Pre-Requisites Before Day 1

| Topic                | Why Important?            | Trusted Link                                                                                                             |
| -------------------- | ------------------------- | ------------------------------------------------------------------------------------------------------------------------ |
| Basics of AI/LLMs    | Understand agent workflow | https://www.youtube.com/watch?v=qbIk7-JPB2c)                               |
| Prompt Engineering   | Build agent logic         | https://platform.openai.com/docs/guides/prompt-engineering
| Python Basics        | Needed for hands-on       | https://www.learnpython.org                                                             |
| VS Code Basics       | Coding environment        | https://code.visualstudio.com/docs                                                 |
| APIs Basics          | Agents call tools/APIs    | https://youtu.be/GZvSYJDk-us                                                           |
| LangChain Intro      | Framework for agents      | https://python.langchain.com/docs/introduction
| Install Python 3.10+ | Required                  | https://www.python.org/downloads                                                  |

# 📘 Day 1 — Full Lesson Plan

## 🟦 Module 1 — Intro to Agentic AI
**Concepts:**
* Shallow Agents vs Deep Agents
* Autonomous decision-making
* RAG overview
**Video:**
[https://youtu.be/ajBQ2C04YjU](https://youtu.be/ajBQ2C04YjU)

## 🟩 Module 2 — Environment Setup

| Step              | Command / Link                                                                   |
| ----------------- | -------------------------------------------------------------------------------- |
| Install Python    | https://python.org/download                     |
| Install VS Code   | https://code.visualstudio.com/download |
| Install LangChain | `pip install langchain openai`                                                   |
| Install Ollama    | https://ollama.ai/download                       |

## 🟧 Module 3 — Your First LLM Agent (Hands-On)

Create the file `/day1/first-agent.py` and paste:

from langchain_openai import ChatOpenAI

model = ChatOpenAI(model="gpt-4o-mini")

response = model.invoke("Hello! What can you do?")
print(response.content)
**Video:**
https://www.youtube.com/watch?v=KcPZxxv-0a0
## 🟥 Module 4 — Tools, Memory & Planning Agent

| Topic                | Resource Link                                                                                                                  |
| -------------------- | ------------------------------------------------------------------------------------------------------------------------------ |
| LangChain Tools      | https://python.langchain.com/docs/concepts/tools                         |
| Memory               | https://python.langchain.com/docs/concepts/memory                       |
| Plan & Execute Agent | https://python.langchain.com/docs/tutorials/plan_and_execute

# 📝 Day 1 Assignment

✔ Build a simple AI assistant
✔ Add memory
✔ Add a calculator tool
✔ Run the model locally using Ollama
✔ Upload your code to GitHub
# 📦 Downloads

Will be added inside `/resources`:

* `installation-guide.pdf`
* `day1-starter.zip`
* `slides.pdf`

# 🤝 Contact

**D. Meenakshi Sundaram**
Founder, DMS Academy
📧 mailto:dmsmytech@gmail.com
🔗 LinkedIn: https://www.linkedin.com/in/dmsmtech

# ⭐ Want to Continue?
Day 2–5 content will be released soon on this page.

# END OF README
