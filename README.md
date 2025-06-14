# 🤖 LLM-Powered Chatbot with LangChain & Groq API

This project demonstrates my ability to build a chatbot using a Large Language Model (LLM). It uses [LangChain](https://www.langchain.com/) and the [Groq API](https://groq.com/) to enable dynamic conversation with memory.

## What It Does

- Builds a functional chatbot using a Groq-powered LLM (`Gemma2-9b-It`)
- Retains conversation history using a custom memory class
- Uses prompt templates to format input for the model
- Great foundation for more advanced applications like RAG or AI agents

## Why I Built This

This notebook is part of my exploration into LLM-based applications. I built this to understand how conversational memory, prompt engineering, and API integration work together in production-quality AI tools.

## Tech Stack

- **LangChain** — framework for LLM applications
- **Groq API** — fast inference engine for LLMs
- **Python** — primary programming language
- **Jupyter Notebook** — for code walkthrough and testing
- **dotenv** — for managing API keys securely

## Setup

1. Install dependencies:

    ```bash
    pip install langchain python-dotenv
    ```

2. Create a `.env` file in the root folder with:

    ```
    GROQ_API_KEY=your_groq_api_key_here
    ```

3. Run the notebook:

    ```bash
    jupyter notebook chatbot2.ipynb
    ```

## Project Files

- `chatbot2.ipynb` — Main notebook with full chatbot implementation
- `.env` — For storing API keys (add this to `.gitignore`)
- `README.md` — You're reading it!

## Future Improvements

- Add a UI using Gradio or Streamlit
- Extend to Conversational RAG with external documents
- Add persona memory or tool use via LangChain agents

## Contact

Feel free to connect with me:

- GitHub: https://github.com/iqrai1
- LinkedIn: https://www.linkedin.com/in/iqrajannat/

