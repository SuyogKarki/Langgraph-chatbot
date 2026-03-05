# LangGraph Chatbot

This repository contains a collection of Jupyter notebooks and examples for building AI agents and chatbots using [LangGraph](https://python.langchain.com/docs/langgraph/).

## Contents

### BasicChatBot/
This directory features detailed notebook walk-throughs covering key LangGraph concepts:

- **`basicChatBot.ipynb`**: Demonstrates the foundational setup of a simple Chatbot. It covers core state management, defining nodes, and rendering basic graph structures.
- **`ReactAgent.ipynb`**: Implements a ReAct (Reasoning and Acting) agent. This notebook illustrates how an agent can iteratively reason about a user's problem and autonomously decide which tools to use.
- **`HumanInLoop.ipynb`**: Explores the human-in-the-loop pattern. It showcases how to insert breakpoints into graph execution to request user approval or gather explicit human feedback before proceeding with specific steps.

## Requirements and Setup

This project uses `uv` for dependency management.

1. **Clone the repository:**
   ```bash
   git clone https://github.com/SuyogKarki/Langgraph-chatbot.git
   cd Langgraph-chatbot
   ```

2. **Install dependencies:**
    Ensure you have [uv](https://github.com/astral-sh/uv) installed, then run:
    ```bash
    uv sync
    ```
    *Alternatively, you can install from the `requirements.txt` using standard `pip`.*

3. **Environment Variables:**
   Create a `.env` file in the root directory to store your required API keys (e.g., `GROQ_API_KEY`, `TAVILY_API_KEY`, or specific LLM keys used in the notebooks).

## Usage
Launch Jupyter Notebook or JupyterLab to interact with the notebooks located in the `BasicChatBot/` directory.

```bash
jupyter notebook
```
