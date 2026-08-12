# Langchain Agent

A minimal LangChain-based agent project built for experimentation and learning. This repository demonstrates how to set up a Python environment, install dependencies, and run a simple agent-driven application using environment-based API keys.

## Features

- Simple LangChain agent scaffold
- Environment variable support via `.env`
- Example app entrypoints: `app.py`, `main.py`
- Notebook research work in `research/agent_demo.ipynb`

## Technology

- Python 3.11
- LangChain
- OpenAI API
- dotenv for environment configuration

## Architecture

This repository is organized as a small Python agent project:

- `app.py` - Primary application script for launching the agent logic.
- `main.py` - Secondary entrypoint, typically used for testing or demo execution.
- `requirements.txt` - Python dependencies required to run the project.
- `.env` - Local environment variables containing API keys.
- `research/agent_demo.ipynb` - Jupyter notebook for experimentation and development notes.

The application follows a simple architecture:

1. Load configuration from `.env`.
2. Initialize the agent and language model client.
3. Execute the agent workflow through `app.py` or `main.py`.

<br/>

## Getting Started

<br/>

https://app.tavily.com/home


<br/>

```shell
$ uv init
$ uv venv
$ source .venv/bin/activate
$ uv add -r requirements.txt
$ uv add ipykernel
```


### Run the Project

Use one of the Python entrypoints:

```bash
python app.py
```

or

```bash
python main.py
```