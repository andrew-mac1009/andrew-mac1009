# AI Chatbot with Gradio and LangChain

A modern chatbot interface using Gradio, LangChain, and Ollama.

## Prerequisites

- Python 3.8+
- Ollama installed and running locally
- Llama2 model downloaded in Ollama

## Installation

1. Create a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Make sure Ollama is running with Llama2 model installed:
```bash
ollama run llama2
```

## Running the Application

1. Start the application:
```bash
python src/app.py
```

2. Open your browser and navigate to `http://localhost:7860`

## Features

- Clean and intuitive chat interface
- Persistent chat history
- Example prompts
- Modern UI with Gradio's Soft theme
- Powered by Llama2 through Ollama

## Project Structure

- `src/app.py`: Main application entry point
- `src/llm.py`: LLM model configuration
- `src/chat_history.py`: Chat history management
- `requirements.txt`: Project dependencies
