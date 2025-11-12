# Chatbot Using LangChain OpenRouter API And LLAMA 3.2

A simple chatbot application built with LangChain, Streamlit, and OpenRouter API, utilizing open-source language models.

## Features

- Interactive chat interface using Streamlit
- Integration with OpenRouter API for accessing GPT-OSS-20B model
- LangChain framework for prompt management and output parsing
- LangSmith tracking for monitoring and debugging


## Screenshot

### Langchain With LLAMA 3.2

### Langchain With Openrouter API


## Prerequisites

- Python 3.8+
- OpenRouter API key
- LangChain API key (optional, for tracking)

## Installation

1. Clone the repository:
```bash
git clone https://github.com/SwayamSat/CHATBOT-USING-LANGCHAIN-OPENROUTER_API-AND-OPEN-SOURCE-MODEL.git
cd Chatbot
```

2. Install required packages:
```bash
pip install -r requirements.txt
```

3. Create a `.env` file in the project root and add your API keys:
```
OPENROUTER_API_KEY=your_openrouter_api_key_here
LANGCHAIN_API_KEY=your_langchain_api_key_here
```

## Usage

Run the Streamlit application:
```bash
streamlit run openrouter_api.py
```

The application will open in your default browser. Enter your query in the text input field and get responses from the AI assistant.

## Project Structure

- `openrouter_api.py` - Main Streamlit application with OpenRouter API integration
- `locallama.py` - Alternative implementation (if using local models)
- `requirements.txt` - Python dependencies
- `.env` - Environment variables (not included in repo)

## Technologies Used

- **LangChain** - Framework for building LLM applications
- **Streamlit** - Web application framework
- **OpenRouter API** - Access to various open-source models
- **Python-dotenv** - Environment variable management

