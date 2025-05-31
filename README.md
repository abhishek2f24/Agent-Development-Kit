# Agent Development Kit (ADK) Crash Course

This repository contains examples for learning Google's **Agent Development Kit (ADK)** — a powerful framework for building LLM-powered agents.

---

## 🚀 Getting Started

### ✅ Setup Environment

You only need to create one virtual environment for all examples in this course:

```bash
# Create virtual environment in the root directory
python -m venv .venv

# Activate (each new terminal)
# macOS/Linux:
source .venv/bin/activate
# Windows CMD:
.venv\Scripts\activate.bat
# Windows PowerShell:
.venv\Scripts\Activate.ps1

# Install dependencies
pip install -r requirements.txt
```

Once set up, this environment will work for all examples in the repository.

---

## 🔐 Setting Up API Keys

1. Create an account on [Google Cloud](https://cloud.google.com/?hl=en)  
2. Create a new project  
3. Go to [Google AI Studio](https://aistudio.google.com/apikey) and create an API key  
4. Assign the key to your project and connect to a billing account  

Each example folder contains a `.env.example` file. To run any project:

```bash
# Navigate to the example folder
cd examples/example-folder

# Rename the env file
mv .env.example .env
```

Then, open `.env` and update your API key:

```
GOOGLE_API_KEY=your_api_key_here
```

Repeat this for each example you want to run.

---

## 📂 Examples Overview

Each folder demonstrates a specific ADK concept:

1. **Basic Agent** – Build a simple agent that responds to queries.  
2. **Tool Agent** – Enhance agents with tools to perform additional actions.  
3. **LiteLLM Agent** – Switch between LLMs using LiteLLM abstraction.  
4. **Structured Outputs** – Use Pydantic schemas for structured responses.  
5. **Sessions and State** – Maintain memory across multiple interactions.  
6. **Persistent Storage** – Store agent data beyond runtime.  
7. **Multi-Agent** – Orchestrate multiple agents for complex tasks.  
8. **Stateful Multi-Agent** – Keep state across multi-turn conversations.  
9. **Callbacks** – Monitor agent behavior with event callbacks.  
10. **Sequential Agent** – Process tasks in defined pipeline steps.  
11. **Parallel Agent** – Run concurrent tasks with parallel agents.  
12. **Loop Agent** – Refine output iteratively using feedback loops.

---

## 📚 Official Documentation

Explore the official ADK documentation:  
[https://google.github.io/adk-docs/get-started/quickstart](https://google.github.io/adk-docs/get-started/quickstart)

---

## 💬 Support

Need help or want to connect with other developers?

Join our **AI Developer Accelerator** community on Skool:

- Weekly coaching and support calls  
- Early access to YouTube project code  
- Network of developers from all skill levels  
- Behind-the-scenes insights

---

Happy coding! 🚀
